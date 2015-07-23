ORDER AND PURPOSE OF DEFAULT STYLESHEETS
----------------------------------------

The Shell Theme has been set up as a standardized theme. Styling is found for this theme within a few Cascading Style Sheets, listed below with their specific purposes.

- flexslider.css:
  This CSS file provides all the necessary styling for the standard Flexslider.
  If you need to set up a dual-Flexslider, please refer to IMRC documentation for
  help.

- footer-official.css
  This CSS file provides all standard styling for the official Lehigh footer.

- html-reset.css:
  This is the place where you should set the default styling for all HTML
  elements and standardize the styling across browsers. If you prefer a specific
  reset method, feel free to add it.

- print.css:
  The print styles for all markup.

- media-queries.css:
  This CSS file provides all necessary styling for responsiveness. It sets general
  styling for a number of page sizes, allowing the site to change styles slightly
  when at tablet or phone size.

- style.css:
  This CSS file provides all standard styling for the Shell Theme. It is organized
  according to hierarchy as well as position on the page - styling for the entire
  page located towards the top, followed by HTML tag-specific styling, followed by
  Header, Navigation, Content, etc. Please make sure to keep any additional styling
  in this organization, to make any future editing attempts easier.

- ie7.css:
- ie6.css:
  The Internet Explorer stylesheets are added via conditional comments. Many CSS
  authors find using IE "conditional stylesheets" much easier then writing
  rulesets with CSS hacks that are known to only apply to various versions of
  IE. The full conditional comment syntax can be found on Microsoft's website:
  http://msdn.microsoft.com/en-us/library/ms537512.aspx
  An alternative method presented by Paul Irish can be found at
  http://paulirish.com/2008/conditional-stylesheets-vs-css-hacks-answer-neither/

In these stylesheets, we have included all of the classes and IDs from this
theme's tpl.php files. We have also included many of the useful Drupal core
styles to make it easier for theme developers to see them.


DRUPAL CORE'S STYLESHEETS
-------------------------

Many of the Shell Theme's styles are overriding Drupal's core stylesheets, so if
you remove a declaration from them, the styles may still not be what you want
since Drupal's core stylesheets are still styling the element. See the
drupal7-reference.css file for a complete list of all Drupal 7.x core styles.
