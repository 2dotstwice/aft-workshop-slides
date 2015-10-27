##  Guestbook entries

* Create a function called `readGuestbookEntries()`
* Inside, read the contents of `files/guestbook-entries.json` using `file_get_contents()`
* Decode the JSON data using `json_decode($data, $assoc)` with the `$assoc` parameter set to `true` to convert it to an array
* Pass the result of the function wherever you render `guestbook.twig` as the `entries` option

GIT Branch: <code class="branch">workshop/4-guestbook-entries</code>

