##  Access restriction

* Use `before()` on the routes you want to restrict access to.
* Eg. `/guestbook` and `/user/profile`
* Check whether or not a username is set in the session data
* If not, redirect to `/user/login`
* http://silex.sensiolabs.org/doc/middlewares.html#route-middlewares
