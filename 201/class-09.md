# Reading Class 09

HTML Forms

1) Web forms are a way to collect information from user inputs. The data taken in can be stored, or taken to immediately update the interface.

2) The bigger the form, the risk of losing users attention is higher. Forms should be simple, short and ask exactly what is needed to function.

3) `<form>` - This element defines a form as a containter element. Specifically containing forms.
`<label>` - This element represents a caption that corresponds to the item on the UI.
`<input>` - This element is used to create interactive controls for web forms to accept inputs from the user.
`<textarea>` - This element represents a multi-line text editing area, when a sizeable chuck of free-form text is accepted.
`<button>` - This element creates a button where a user can clicking to cause an action.

JS Events

1) Events on a webpage are any actions or occurance that happens on a webpage, quantifies by some sort of signal. When something happens on a page, for example, a click happened, that action is recorded and labled as an event.

2) The `addEventListener()` requires the name of the event to look out for, and a function to run when the event was "heard", or in response to the event that was named.

3) The event object is the object that is passed automatically to the event handler function so additional information or extra feature can be added to the event object specifically. The event object passed will be the reference the event occured upon.

4) Difference between event bubbling and event capture is the order of how the event is proprogated to the end destination element. Event bubbling will fire the event from the most innermost element and propogate upward to the parent element, whereas even capture will fire the event on the least nested element and then all the way to the innermost nested element.

## Things I want to know more about

More use case of event bubbling and event capture. It seems natural to be using event bubbling as a default, but there were examples of when to use event capture.
