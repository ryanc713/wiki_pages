# Close on Outside Click

To close(hide) an element when a click is generated outside of the element itself, you must add an event listener to the window object.
We use the mouseup event to call an anonymous function. The element you want to close is then referenced and saved as a variable to access it easier.
Next we use an if statement that says if a click is not generated inside the element, or the element's parent, then close(hide) the element.

**Javascript**
````javascript
window.addEventListener('mouseup', function(e){
  var x = document.getElementById('ELEMENT_ID');
  if(e.target != x && e.target.parentNode != x){
    x.style.display = 'none';
  }
});
````
