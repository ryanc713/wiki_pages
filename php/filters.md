# PHP Sanitize and Filter Functions

| Function |	Description |
|----------|--------------|
| filter_has_var() |	Checks if variable of specified type exists |
| filter_id() |	Returns the ID number of a specified filter |
| filter_input() |	Gets a specific external variable by name and optionally filters it |
| filter_input_array() |	Gets multiple external variables and optionally filters them |
| filter_list() |	Returns an array of all supported filters |
| filter_var_array() |	Gets multiple variables and optionally filters them |
| filter_var() |	Filters a variable with a specified filter |

| ID |	Description |
|----|--------------|
| FILTER_SANITIZE_EMAIL |	Remove all characters except letters, digits and !#$%&'*+-/=?^_\`{|}~@.[] |
| FILTER_SANITIZE_ENCODED |	URL-encode string, optionally strip or encode special characters. |
| FILTER_SANITIZE_MAGIC_QUOTES |	Apply addslashes(). |
| FILTER_SANITIZE_NUMBER_FLOAT |	Remove all characters except digits, +- and optionally .,eE |
| FILTER_SANITIZE_NUMBER_INT |	Remove all characters except digits, plus (+) and minus (-) sign. |
| FILTER_SANITIZE_SPECIAL_CHARS |	HTML-escape '"<>& and characters with ASCII value less than 32, optionally strip or encode other special characters. |
| FILTER_SANITIZE_STRING |	Strip tags, optionally strip or encode special characters. |
| FILTER_SANITIZE_STRIPPED |	Alias of "string" filter. |
| FILTER_SANITIZE_URL |	Remove all characters except letters, digits and $-_.+!*'(),{}|\\^~[]\`<>#%";/?:@&= |
| FILTER_UNSAFE_RAW | 	Do nothing, optionally strip or encode special characters. |

| ID |	Description | 
|----|--------------|
| FILTER_VALIDATE_BOOLEAN |	Returns TRUE for "1", "true", "on" and "yes". Returns FALSE otherwise. |
| FILTER_VALIDATE_EMAIL |	Validates value as e-mail. |
| FILTER_VALIDATE_FLOAT |	Validates value as float. |
| FILTER_VALIDATE_INT |	Validates value as integer optionally from the specified range. |
| FILTER_VALIDATE_IP |	Validates value as IP address, optionally only IPv4 or IPv6 or not from private or reserved ranges. |
| FILTER_VALIDATE_REGEXP |	Validates value against regexp, a Perl-compatible regular expression. |
| FILTER_VALIDATE_URL |	Validates value as URL, optionally with required components. |
