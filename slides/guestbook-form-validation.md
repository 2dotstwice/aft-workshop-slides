## Validating the input

* Create an array called `$errors` in the post handler
* Add an error message to the array if `$name` is empty
* Add an error message to the array if `$message` is empty
* If the array is not empty after validating all the fields:
    * Render the `guestbook.twig` template
    * Pass the errors as `errors` in the options
    * Pass an array called `formValues` with keys `name` and `message`
    * Return the rendered HTML as a new `Response`
    
GIT Branch: <code class="branch">workshop/3-guestbook-validation</code>

