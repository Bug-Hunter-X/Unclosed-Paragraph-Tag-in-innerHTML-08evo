# Unclosed Paragraph Tag in innerHTML

This repository demonstrates a subtle HTML bug that arises from improperly using `innerHTML` to add HTML content. The bug causes an unclosed paragraph tag, leading to potential rendering issues and unexpected behavior.

## Bug Description
The `bug.html` file contains a script that appends a new paragraph using `innerHTML`. However, the closing tag (`</p>`) is missing from the appended string. This can lead to various problems, such as malformed HTML and rendering inconsistencies.

## Solution
The `bugSolution.html` file provides a corrected version.  It shows how to correctly append a complete HTML element to avoid the issue.  It demonstrates best practice of using DOM manipulation for adding elements safely and reliably.