# Register an element
To register a new element, call the Polymer function, which _registers_ a new element with the browser. Registering an element associates a tag name with a prototype, so you can add properties and methods to your custom element. The custom element’s name **must contain a dash (-)**.

The Polymer function takes as an argument an object that defines your element’s prototype.

## This sample
This sample uses a lifecycle callback to add contents to the `<proto-element>` when it’s initialized. When a custom element finishes its initialization, the **ready** lifecycle callback is called. The **ready** callback is a great place to do constructor-like initialization work.
