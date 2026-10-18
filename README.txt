Assignment 4 - Forms and Validation
Ardak Kazykhan, IT-2510
https://github.com/ardkzhn0111/assignment4-forms

Open index.html in a modern browser. No installation or build is needed.
Bootstrap CSS and Montserrat fonts are included locally, so the forms work offline.

task1.html - train ticket form
task2.html - AITU Hack 2026 registration
task3.html - corrected cafe reservation
style.css - shared design and feedback styles

This is a front end assignment, with no booking, registration or password storage.
Task 1 and Task 3 use a demonstration GET destination. Task 2 uses POST so a
password is not placed in the URL; saving a registration requires a server endpoint.
Use invented values when demonstrating the forms.

No application JavaScript, pattern attributes or novalidate attributes are used.
Validation is native HTML. CSS :user-invalid reveals feedback after interaction
or a submission attempt. The initial page has no red errors.

Task 1 starts empty to make the native reset button empty all fields.
The report screenshots contain entered example cities and selected options.
The mobile button order uses column-reverse; the HTML order stays Clear then Find.
CSS contains no fixed layout widths and no absolute positioning.

Checks: 69 browser checks passed, including 42 text/number/date/time/URL cases,
radio/select/checkbox rules, maxlength, keyboard controls, reset and phone layout.
W3C Nu Validator: task3.html returned zero errors and zero warnings.
Bootstrap 5.3.8 is MIT licensed. Montserrat uses the SIL Open Font License.

References
https://getbootstrap.com/docs/5.3/forms/overview/
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:user-invalid
