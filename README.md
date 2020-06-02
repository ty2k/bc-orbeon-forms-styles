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
