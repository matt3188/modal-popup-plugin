# modal-popup-plugin

Plugin to save rewriting modal popup code over and over.

##CORE FUNCTIONALITY
This plugin should:

- Build a modal element and add it to the page
- Add any classes specified in the `className` option to the modal
- If the `closeButton` option is true, add a close button
- If the `content` option is a HTML string, set it as the modal’s content
- If the `content` option is a domNode, set it’s interior content as the modal’s content
- Set the modal’s `maxWidth` and `minWidth` respectively
- Add an overlay if the `overlay` option is true
- When opened, add a `modal-open` class that we can use with our CSS to define an open state.
- When closed, remove the `modal-open` class.
- If the modal’s height exceeds the viewport’s height, also add a `modal-anchored` class so that we can handle that scenario

##Road map
- Add the ability to close modal with `ESC` key
- Add library of animations that can be added to the popup
- 