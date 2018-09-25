# date-input-polyfill-react
Just include this simple script and IE, Firefox, and OS X Safari will support `<input type="date">`, without any dependencies, not even jQuery!

Support dynamically created inputs, so can be used in single page applications.

Forked from [date-input-polyfill](https://github.com/jcgertig/date-input-polyfill) to make it work with React >= 15.6 (and probably breaking compatibility with anything other than React, never tested that).

The changes to support React have been based on comments and code by:
Grin : https://stackoverflow.com/a/46012210/1141255
Brian Mann : https://github.com/cypress-io/cypress/issues/647#issuecomment-335829482 and https://github.com/cypress-io/cypress/commit/4a56ca83b3b6e19ec57d10a8160f54f513e8f8ec

## Install
`npm install --save date-input-polyfill-react`
