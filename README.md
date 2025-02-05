# Uncommon HTML Error: Unexpected innerHTML behavior

This repository demonstrates an uncommon error related to the use of `innerHTML` in HTML and JavaScript.  Incorrectly appending to `innerHTML` can lead to unexpected behavior and potential security vulnerabilities if not handled correctly.

The `bug.html` file showcases the problem, and `bugSolution.html` provides a corrected approach using `insertAdjacentHTML`.

## Bug Description
Modifying an element's `innerHTML` by appending to it can lead to duplicated content. This is because the original content is replaced by the new content along with the original content.  Using `insertAdjacentHTML` allows for more controlled manipulation of the DOM.