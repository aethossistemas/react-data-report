# react-data-report
ReactJS component to preview data and export it as PDF file.

The user will be able to choose the items per page, the page format (portrait / landscape) and the page size (a4 / letter / legal).

Columns in table can be easily hide using style. Please refer to [App.css](test/src/App.js) to see an example.

### Example:

Please refer to the [test](test/src/App.js) file to see how works.

To run the test:
1. Clone the repository
2. Execute in console:
```BASH
Linux
cd test
npm install
cd node_modules
ln -s ../../ react-data-report
cd ..
npm start
```

```BASH
Windows
cd test
npm install
cd node_modules
mklink /d comp C:\react-data-report
cd ..
npm start
```

mklink /d 

### General Usage

As you will be able to see in [test](test/src/App.js) in order to use the component we need to importe it as:
```JAVASCRIPT
import Report from 'react-data-report';
```

Then, in the render method we can just call it like:

```JAVASCRIPT
<Report data={example} opening={(<h1>This is an opening content.</h1>)}/>
```

Where data is an array of objects as you can see in this [example](test/src/example.json) file.

### Installation

Install this component is easy, just use npm as:
```BASH
npm install @weknow/react-data-report
```
