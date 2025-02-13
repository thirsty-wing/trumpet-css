# Implementation Notes

We don't do smooth scrolling for input validation. All browsers except chrome disregard it and chrome discards the validation info when smooth scroll is used.

We needed to use display: flex on text-button. Using inline-block made the text of an anchor element rise to the top. Could not resolve it.

We use the disabled attribute on a button to show a text-button/icon-button as disabled. Using the disabled attribute on a button disables both click and tabbed focus then activation. There's no way to actually disable a link or a label, so we shouldn't pretend these can be disabled.
