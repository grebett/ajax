ajax.js is a simple AJAX library written by [@fdaciuk](https://github.com/fdaciuk).

All documentation about the original library can be found in the library's [repository](https://github.com/fdaciuk/ajax)

This fork has been stripped of the build and test logic files, as we are not using it as a project repository but as a simple storage.

If you plan to reuse this work, I do encourage you to refer to the [original library](https://github.com/fdaciuk/ajax). For your information, you'll find below a brief resume of the differences between the two versions:

+ we got rid of deprecation notices
+ we restricted usage to browser only
+ we added `xhr.withCredentials = true` to handle CORS request credentials issues

As usual, `git diff` remains your true friend for a more complete understanding! :)
