## [reading-notes](https://cheryldee.github.io/reading-notes/)
### HTML Forms
#### How to Structure a Web Form
  1. Web forms are a very powerful tool for interacting with users — most commonly they are used for collecting data from users, or allowing them to control a user interface. 
  2. Creating forms with fewer inputs will improve the user experience; smaller forms have higher conversion rates., and reducing the data collected has a chance of reducing privacy concerns, although this depends greatly on the data. Keep the design of the form simple, don't go overboard and make things confusing.
  3. Input element is the most important for capturing information which serves the purpose of the form. Next is the label element is useful for screen readers which will read aloud the label when the user focus on the input element. It is also important to help user who have problems with clicking on very small radio buttons and checkboxes because the label element toggles the buttons/checkbox. the select element is used for drop-down lists to help users choose the options they need. Number five is the textarea that allows users to input comments and questions as a source of additional information.
  4. Events are actions that happen when a button is click or mouse-over, it signals a reaction when an event-listener is in place, such as an image displays when the mouse hovers over a button, or a video plays when the play button is clicked. These are a trigger and response events.
  5. The two arguments are the name of the event and a function to handle the event. Click is a string that listens for an event which calls upon the function to respond to the 'click'.
  6. All event objects in the DOM are based on the Event Object. Therefore, all other event objects (like MouseEvent and KeyboardEvent) has access to the Event Object's properties and methods.
  7. The processes of capturing and bubbling are means of event propagation in the HTML DOM API when an event happens inside an element within another element, and both of the elements have registered a handler. So, when an event occurs, the most nested element in which it happened becomes the "target element" ( event.target ).

[Main Page](https://cheryldee.github.io/reading-notes/)
