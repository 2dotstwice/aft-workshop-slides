##  User registration

* `GET /user/registration` should render `registration.twig` and return it in a `Response`
* `POST /user/registration` should get the values of `username`, `password`, `passwordConfirmation`, `name` and `email`
* All values should not be empty, and `password` and `passwordConfirmation` should be the same
* In case of errors, render the `registration.twig` template with `errors` and `formValues`
* Otherwise, save the user using a function `saveUser($user)` (key by username). Afterwards, redirect to `/user/login`

GIT Branch: <code class="branch">workshop/5-registration</code>


