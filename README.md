# SimpleResume
Simple and clean resume/CV template. Fully customizable.
Made with open-source third-part components as 
- Poppins Google Font
- LineAwesome Icons

All these components are places in the `/vendor` folder. Each component is licences by itself.

## Document Colors

This templates comes with three base colors: <var>orange</var>, <var>blue</var> and <var>green</var>. Other colors can be easily added. For example, the CSS code with a new <var>red</var> color added will appear as following:

```css
:root
{
    /* other colors and variables */
    --color-red: #f00;
    --color-red-dark: #d00;
}

/* other classes */

.resume.resume-red
{
    --theme-color: var(--color-red);
    --theme-color-dark: var(--color-red-dark);
}
```

The theme color will be applied automatically once the class `.resume-red` is added in the HTML document.


## Document sizes

There are two CSS classes to represent two different document sizes
- `.resume_iso-a4` for "A4" paper size (210 &times; 297 mm), as described in ISO standard.
- `.resume_us-letter` for "US Letter" paper size (216 &times; 297 mm), as described in american standard. Can be used for "US Legal" size too.

Ask your company/school (or whoever is supposed to receive your resume) for the correct size to be used.

In the print dialog, you can also choose to print with different paper size from the one you used ad CSS class. But, in this case, good results are not guaranteed.

## Printing or generating PDF

Once opened the `resume.html` file, hit <kbd>Ctrl</kbd> + <kbd>P</kbd> (or <kbd>Command</kbd> + <kbd>P</kbd> if on MacOS), to open the print dialog. From there, you can set the paper format (A4, US Letter).

In the left box, you can see a preview of your print. If you see some gray lines around, set the <var>Margin</var> option to `0` or `none` (you can find this options in the right box of the print dialog).

Also, set the <var>Background Graphics</var> option to `true` or `yes`, else you won't be able to see graphical/colored backgrounds.

When all options are set, you can print your document with your choosen printer. If you want to generate a PDF document instead, then choose <var>Save as PDF</var> as printer.
