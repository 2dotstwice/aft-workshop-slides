##  User logout

* On `GET /user/profile`, add `logoutUrl` option to template 
* `GET /user/logout` 
    * `$app['session']->remove('username')` to unset the username
    * Redirect to `/user/login`
    
GIT Branch: <code class="branch">workshop/7-logout</code>
