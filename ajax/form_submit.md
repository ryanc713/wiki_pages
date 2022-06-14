# Ajax Form Submit Example

````javascript
$(document).ready(function () {

//Add click event listener on Submit Button
  $('SUBMIT_BTN').click(function (e) {

  // Prevent form from being submitted
    e.preventDefault();
    // Set input field value to variables for easy reference
    var name = $('#name').val();
    var email = $('#email').val();
    var message = $('#message').val();

    // Call ajax method
    $.ajax
      ({
        type: "POST",

        // Where to send the form data for processing
        url: "form_submit.php",

        // Send form data in key:value pairs
        data: { "name": name, "email": email, "message": message },
        success: function (data) {
          $('.result').html(data);
          $('FORM_ID')[0].reset();
        }
      });
  });
});
````
