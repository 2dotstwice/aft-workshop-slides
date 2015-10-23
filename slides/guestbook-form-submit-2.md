## Submitting the form (2)

* Create a function called `saveGuestbookEntry($entry)`
* Encode the data using `json_encode()`
* Write the data to a file called `files/guestbook-entries.json` using `file_put_contents()`
* Return a `RedirectResponse` to `/guestbook`

GIT Branch: <code class="branch">workshop/2-guestbook-post</code>
