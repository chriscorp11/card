This is a single page, single screen responsive site template. It makes heavy use of CSS animation and works well as a landing page that directs visitors to your content elsewhere on the web. Sass sources are also included for those interested in using Sass (sass-lang.com). If not, you can safely delete the "sass/" folder.

The scrolling mountainous background was derived from "Icefields" by a talented photographer from Vancouver who released it on Unsplash under the CC0 license. Check out other CC0-licensed images at Unsplash (unsplash.com).

The Scrolling Background:

This relies entirely on CSS. You can use almost any image, but for best results ensure it is:

- Horizontally tileable
- Wide and short
- About 1500px wide
- Fades to a solid color at the top or bottom to fill the empty space

There are two ways to use it: with CSS, or with Sass:

CSS:

Look for this line in css/style.css:

background: #348cb2 url("images/bg.jpg") bottom left;

Use it to set the page background color, URL, and placement of your image. It should be as close to 1500px wide as possible.

Sass:

Set the value of $bg to the page background color, URL, and placement of your image. Change $bg-width if your image is something other than 1500px wide.

Credits:

Background Image:
AlphaCoders

Icons:
Font Awesome (fontawesome.io)

Other:
Responsive Tools (github.com/ajlkn/responsive-tools)
""")