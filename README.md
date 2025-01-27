# Uncommon HTML Error: Invalid Tag within innerHTML

This repository demonstrates an uncommon HTML error that can occur when using the `innerHTML` property to dynamically generate HTML content.  The error arises from including an invalid HTML tag within the string assigned to `innerHTML`. 

The bug is demonstrated in `bug.html`. The solution is provided in `solution.html`.  The solution involves proper validation of the dynamically generated HTML, which is best done using a template system or a DOM manipulation technique that avoids directly using `innerHTML` with untrusted content.