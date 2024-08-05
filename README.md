# Setup and Usage

## 1. HTML Structure

### DOCTYPE & HTML

The document is defined with HTML5 standards using `<!DOCTYPE html>`.

### Head Section

Includes the charset, viewport settings, page title, Font Awesome CDN for icons, and a link to the external CSS file.

### Body Section

Contains the main container for the form, including the structure for the sign-in form, input fields, and social media buttons.

## 2. CSS Stylesheet

### Global Styles

The `*` selector sets default margin and padding to 0 and includes `box-sizing: border-box`. The font family is set to "Poppins".

### Container & Form Layout

- **.container:** Sets the form's background and positions it relative to the viewport.
- **.form-container:** Positions the form absolutely within the container.
- **.sign-in-up-form:** Centers the form using absolute positioning and transformation.
- **form:** Styles the form itself, including dimensions, padding, background, and border-radius.

### Input Fields

- **.input-field:** Styles each input field with a grid layout for the icon and input box, including margin, padding, and border-radius.
- **.input-field i:** Styles the icon within the input field.
- **.input-field input:** Styles the input box, including placeholder styling.

### Buttons and Links

- **.btn:** Styles the form's submit button with background color, text color, and hover effects.
- **.social-icon:** Styles the social media icons, including layout, size, border, and hover effects.
