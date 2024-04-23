**1. Window Object**
The window object is the top-level object in the Browser Object Model (BOM) and represents the browser window. It acts as a global object for the JavaScript code running in that window. Here are some of its key features and functions:

**Global Scope:** All global JavaScript objects, functions, and variables automatically become members of the window object.

**Window Properties and Methods:** It includes properties like window.innerHeight, window.innerWidth (which give the height and width of the content area of the browser window), and methods like window.open(), window.close(), which are used to control the browser window itself.

**Control Over the Browser:** The window object provides functions to control the browser, such as navigating to a new page (window.location) or setting timers (setTimeout(), setInterval()).

**Host Objects:** Apart from standard ECMAScript objects, the window object hosts other objects specific to the web environment like navigator, history, screen, etc.
Global JavaScript Environment: Any JavaScript executed in the browser context is done within the scope of the window object.

**2. Document Object**
The document object is a part of the Document Object Model (DOM) and represents the content of the web page loaded in the browser window. It serves as the entry point to the page's content and structure:

**Page Content:** The document object provides structured access to the HTML and XML content of the page. It has properties that refer to other elements on the page, like document.documentElement (which refers to the <html> element), document.body, etc.

**DOM Manipulation:** It provides methods to manipulate the content, structure, and style of the web page, such as document.createElement(), document.getElementById(), document.querySelectorAll(), etc.

**Event Handling:** The document object can be used to handle events through methods like document.addEventListener() and document.removeEventListener().

**Interaction with the Web Page:** Through the document object, developers can read and modify the current page, interact with form elements, change styles dynamically, and respond to user interactions.

**Relationship Between Window and Document**
The document object is actually a property of the window object (window.document). This reflects their relationship: the window is the container that includes a document along with other objects and APIs that interact at the browser level.

Every window has exactly one document associated with it, but the content of this document can change (for example, when navigating to a new page within the same browser window).

In summary, the window object is your interface to the web browser, and the document object is your interface to the content of a specific web page. Each has distinct responsibilities, but they are interconnected, providing a comprehensive API for interacting with web pages and the browser.