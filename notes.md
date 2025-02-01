# Implementation Notes

We don't do smooth scrolling for input validation. All browsers except chrome disregard it and chrome discards the validation info when smooth scroll is used.

We needed to use display: flex on text-button. Using inline-block made the text of an anchor element rise to the top. Could not resolve it.
