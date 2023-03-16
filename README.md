# goit-markup-hw-05

## Module 5: Positioned elements

### Add decorative effect animations to the layout pages from the homework layout #5.

### Project requirements
«A1» All styles are written in one file styles.css, which is located in the css folder.

«A2» The source code is formatted with Prettier.

«A3» All images and textual content are taken from the layout.

«A4» A style normalizer Modern-normalize is connected to all HTML pages.

«A5» The code is written in accordance with the guidelines.

«A6» The modal window script is connected to HTML by a separate  Modal.js file.

### Layout requirements
«B1» HTML markup of all layout elements is done.

«B2» Tags are used according to their semantic content.

### Project design requirements
«C1» Transitions are made for all hover and focus effects (color, background, shadow). Time - 250ms, time distribution function - cubic-bezier(0.4, 0, 0.2, 1).

«C2» Transitions and animations explicitly specify animated properties. There is no all value anywhere.

«C3» In the main navigation, with the help of the ::after, the link of the current page (on which the user is currently located) is underlined.

«C4» The text overlay on the Portfolio page cards appears on hover and focus anywhere on the card.

«C5» The blue overlay in the cards of the Portfolio page moves out from the bottom, as shown in the video.

«C6» Pseudo-elements have no text content in the content property. They are used exclusively for decorative purposes.

### Modal window requirements
«D1» The marking and design of the "backdrop" (dark translucent background) of the modal window has been completed.

«D2» "Backdrop" fills 100% of the height and width of the browser viewport and is fixed in it.

«D3» Completed marking and design of the modal window.

«D4» The modal window is positioned vertically and horizontally in the middle of the backdrop.

«D5» The markup and design of the button to close the modal window in the upper right corner has been completed.

«D6» Initially, the modal window and the backdrop are hidden using the is-hidden class on the backdrop, the selector of which uses the visibility, opacity і pointer-events properties.

«D7» If you remove the is-hidden - class from the backdrop, the backdrop and a modal window appear.

«D8» The appearance and hiding of the modal window is animated using a transition with an arbitrary effect, such as scale or translate, and opacity.

#### Opening/closing the modal window​ requirements

A modal window with an application form opens after clicking on the"Order service button". 

In order for the script to work, you need to add special attributes to the markup, by which the script searches for elements:

data-modal-open - for the modal window opening button.

data-modal-close - for the close button.

data-modal - for the backdrop of the modal window.

Before the closing body tag, add a script tag with a link to the script file for the modal window. 
