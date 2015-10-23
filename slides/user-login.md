##  User login

* `GET /user/login` should render `login.twig` with `submitUrl`
* `POST /user/login` should get `username` and `password` from the post data
* Read the user data and compare the passwords
* Incorrect user/pwd: Render `login.twig` with `errors`
* Correct username and password:
    * Set the username on `$app['session']` with key `username`
    * Redirect to `/user/profile`
* `GET /user/profile` should render `profile.twig` with `username`

GIT Branch: <code class="branch">workshop/6-login</code>
