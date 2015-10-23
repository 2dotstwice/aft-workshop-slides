## Submitting the form (1)

* Route `POST /guestbook`
* Use `$request->request->get(...)` to get the POST data
* Create an `array` with all the data for the entry:
    * `id` (use `uniqid()`)
    * `created` (use `time()`)
    * `name`
    * `message`

GIT Branch: <code class="branch">workshop/2-guestbook-post</code>
