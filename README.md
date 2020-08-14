# BC Gov styles for Orbeon Forms

This repository holds CSS to add [BC Gov Design System styles](https://github.com/bcgov/design-system) to Orbeon Forms within CMS Lite.

To style your form, within your XML source (Advanced tab -> Edit Source), paste CSS (from `./src/styles.css`) into a `<xh:style>` tag as shown below:

```xml
...
<xh:head>
  <xh:title>Document Title</xh:title>
  <xh:style type="text/css">
    <!-- Paste CSS here -->
  </xh:style>
...
```

Orbeon publishes [CSS in Orbeon Forms documentation](https://doc.orbeon.com/form-runner/styling/css).


## Todo

- [ ] Hint text style
- [ ] "?" hint icon to the right of field labels
- [ ] Text input field focus style
- [ ] Text input field error and error message style
- [ ] Text input character counter style
- [ ] Text input and plain text area additional info bubble style
- [ ] Plain text area field style
- [ ] Plain text area field focus style
- [ ] Plain text area field error style
- [ ] Formatted text area field style
- [ ] Text field with suffix icon style
- [ ] Text field with suffix label style
- [ ] Text field with prefix icon style
- [ ] Text field with prefix label style
- [ ] Dropdown menu style
- [ ] Radio button style
- [ ] Yes/No control style
- [ ] Checkbox style
- [ ] Date input style
- [ ] Date input calendar button style/function
- [ ] Time input text field style
- [ ] Time input clock button style/function
- [ ] Single file attachment style
- [ ] Single file attachment uploading message style/function
- [ ] Multiple file attachment style
- [ ] Handwritten signature control style
- [ ] Image attachment control style
- [ ] Image annotation control style/function
- [ ] Primary button style
- [ ] Secondary button style
- [ ] Unstyled button style
- [ ] Add-on prefix and suffix button style
- [ ] Error message list style/function
- [ ] Wizard style navigation with stacked, pill-style buttons
- [ ] Text style for buttons
- [ ] Text style for wizard text
- [ ] Text style for control labels
- [ ] Text style for emphasized text
- [ ] Text style for body text, explanatory text, text input, lists, menus, other primary text
- [ ] Text style for control error messages
- [ ] Text style for hint text and secondary text
