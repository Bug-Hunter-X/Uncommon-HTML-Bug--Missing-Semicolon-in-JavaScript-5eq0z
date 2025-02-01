# Uncommon HTML Bug: Missing Semicolon in JavaScript

This repository demonstrates a subtle bug in HTML where a missing semicolon in a JavaScript code snippet unexpectedly alters the visibility of an HTML element. The bug arises from the interaction between the `display` and `visibility` CSS properties.

## Bug Description

A `div` element is initially hidden by setting its `display` property to `'none'`. Then, an attempt is made to make it visible again by setting the `visibility` property to `'visible'`. However, due to the missing semicolon after the first assignment, the second line of JavaScript isn't executed correctly.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe that the text within the `div` element remains hidden, even though the `visibility` property is set to `visible`.

## Solution

The bug is fixed by simply adding the missing semicolon to the first line of JavaScript.

## Lesson Learned

This illustrates the importance of paying close attention to syntax details, particularly semicolons, in JavaScript. A seemingly minor omission can have significant and unexpected consequences.