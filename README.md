# Silent Failure: Accessing Non-Existent Element by ID

This repository demonstrates a common, yet often overlooked, error in HTML and JavaScript: attempting to access a non-existent element by its ID.  This typically results in a `TypeError` which may not be immediately apparent.

The `bug.html` file shows a situation where JavaScript tries to manipulate an element ("nonExistentElement") that does not exist in the HTML structure.  This results in a failure, but without proper handling, the error is often missed.

The solution in `bugSolution.html` demonstrates adding a simple check to ensure that the element exists before attempting to modify its content, providing a more robust handling of potential errors.