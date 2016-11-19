# Chrome Dev Tools

[Command Line API Reference](https://developers.google.com/web/tools/chrome-devtools/console/command-line-reference)

#### Monitor DOM events and functions in Chrome
```JavaScript
// subscribe to events
monitorEvents(document.body, "click");

// unsubscribe from events
unmonitorEvents(document.body, "click")

// view event listeners registered on objects
getEventListeners(document);

// subscribe to functions
monitor(someFunction);
```

#### Design mode
```js
document.designMode = 'on'
```

#### Copy obj / var to buffer
```JavaScript
copy (someVariable)
```

#### Link to selected DOM element
```js
// link to selected DOM node
$0

// get JavaScript obj
console.dir($0)

// using JQuery
$($0).data()
```

#### Arrow functions in console
```js
// use arrow functions in console
performance.getEntries().filter(entry => entry.name)
```

# Command line

#### Find files
```js
find ./app/img/ -name '*some.svg'
```
#### Open current dir from webstorm
```js
wstorm .
```


# JavaScript

```js
// The Object.assign() method is used to copy the values of all enumerable own properties from one or more source objects to a target object.
let settings = Object.assign( {}, defaults, options1, options2 );
```
