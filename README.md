# Firebase Asynchronous Data Access Error

This repository demonstrates a common error in Firebase applications where data is accessed from a document snapshot before the asynchronous data loading operation has completed. This often leads to unexpected `undefined` values or errors.

The `firebaseBug.js` file shows how this error can occur. The `firebaseBugSolution.js` file presents a corrected version using promises or async/await to ensure data is loaded before access.

## How to reproduce the bug:
1. Clone this repo.
2. Set up a Firebase project and initialize Firebase in `firebaseBug.js`.
3. Run `firebaseBug.js` (you will likely see the error).