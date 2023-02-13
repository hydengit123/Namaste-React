## Namaste React Course by Akshay Saini
# _Chapter 01 - Inception_

## Q: What is Emmet?
A: Emmet is the essential toolkit for web-developers. It allows you to type shortcuts that are then expended into full pieces of code for writting HTML and CSS, based on an abbreviation structure most developers already use that expended into full fledged HTML markup and CSS rules.


## Q: Difference between a Library and Framework?
A: A Library is collection of packages that perform specific operations whereas a Framework contains the basic flow and architecture of an application. The major difference between them is the complexity. Libraries contains a number of methods that a developer can just call and use.
React JS is a library and Angular is a Framework.


## Q: What is CDN? Why do we use it?
A: A Content Delivery network(CDN) refers to a geographically distributed group of servers that work together to provide fast delivery of the internet content.
The main use of a CDN is to deliver content through a network of servers in a secure and efficient way.

## Q: Why is React known as React?
A: React is named as React because of its ability to react to changes in data.
React is called React because it was designed to be a declarative, efficient and flexible Javascript library for building user interfaces.
React is a javascript-based UI development library. Facebook/Meta and an open-source developer comminity run it.


## Q: What is crossorigin in script tag?
A: The crossorigin attribute sets the mode of the request to an HTTP CORS Request.
The purpose of crossorigin attribute is used to share the resources from one domain to another domain.
Basically it is use to handle the CORS request. It is use to handle the CORS request that checks wether it is safe to allow for sharing the resources from other domains.
### _Syntax_
```sh
<script crossorigin="anonymous|use-credentials">
```

## Q: What is difference between React and ReacDOM?
A: React is a javascript library for building User Interfaces whereas ReactDOM is also Javascript Library that allows React to intract with the DOM.
The React package contains React.createElement(), React.Component, React.Children and other helper methods related to elements and component classes. You can thing of these as the isomorphic or universal helpers that you need to build components. The react-dom package contains ReactDOM.render() and in react-dom/server we have the server-side rendering support with ReactDOMServer.renderToString() and ReactDOMServer.renderToStaticMarkup().

## Q: What is difference between react.development.js and react.production.js files via CDN?
A: Development is the stage of an application before it's made public while production is the term used for the same application when it's made public.
Development build is much slower than production build.


## Q: What is async and defer?
A: async - The async attribute is a boolean attribute. The Script is downloaded in parallel(in the background) to parsing the page and executed as soon as it is available (do not block HTML DOM construction during downloading process) and dont wait for anything.
### _Syntax_
```sh
<script src="demo_async.js" async></script>
```

defer - The defer attribute is a boolean attribute. The script is downloaded in parallel(in the background) to parsing the page and execute after the page has finished parsing(when browser finished DOM construction).
defer attribute tells the browser not to wait for the script. Instead, the browser will continue to process the HTML, build DOM.
### _Syntax_
```sh
<script src="demo_defer.js" defer></script>