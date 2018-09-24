# date-input-polyfill-react
Just include this simple script and IE, Firefox, and OS X Safari will support `<input type="date">`, without any dependencies, not even jQuery!

Support dynamically created inputs, so can be used in single page applications.

Forked from [date-input-polyfill](https://github.com/jcgertig/date-input-polyfill) to make it work with React.

## Install
`npm install --save date-input-polyfill-react`

## Features
* **Localization:** Specify the datepicker's locale by setting the
`lang` attribute of the `input` element.  The default locale is `en`.

    `<input type="date" lang="en" />`
