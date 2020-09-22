# BC Gov styles for Orbeon Forms

This repository holds CSS to add [BC Gov Design System styles](https://github.com/bcgov/design-system) to Orbeon Forms.

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

## Style Guide
See Adobe XD style guide: https://xd.adobe.com/view/76b59a97-3acc-44ef-bdb7-0c4660f85b3a-23e6/

A copy of the XD file and PNG art boards are included in the `./style-guide/` directory.

## Notes
- Orbeon publishes [CSS in Orbeon Forms documentation](https://doc.orbeon.com/form-runner/styling/css).
- These styles were written in the context of having to over-write both the compiled Orbeon styles and the gov.bc.ca front-end rendering application styles (hence the `!important` use).

## Contact
- Designer: [Kim Nguyen](mailto:Kimberly.Nguyen@gov.bc.ca)
- Developer: [Tyler Krys](mailto:Tyler.Krys@gov.bc.ca)
