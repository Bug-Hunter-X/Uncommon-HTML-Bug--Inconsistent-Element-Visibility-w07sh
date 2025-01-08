# Uncommon HTML Bug: Inconsistent Element Visibility

This repository demonstrates a subtle bug related to element visibility in HTML and JavaScript.  The bug arises from toggling the display property of an element without first checking its current state, leading to inconsistent behavior.  The solution addresses this by adding a conditional check.

## Bug Description
The provided HTML code includes a div and a button. Clicking the button is intended to toggle the visibility of the div. However, due to a missing check for the current display style, repeated clicks can leave the div unexpectedly hidden or visible.

## Solution
The solution adds a conditional statement to determine whether the element is currently hidden or visible before modifying its display style. This ensures the display is properly toggled in all cases.