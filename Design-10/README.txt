Design-10 - Capitol backdrop + Design-09 waves

Open preview.html for a local sample. This version combines a white GA@WORK logo with an orange power symbol,
a continuous dark-to-light blue photo backdrop and Design-09's blue/light-blue/orange waves. No workforce
slogan is included. Design-07 and Design-09 remain separate designs.

Nintex setup:
1. Replace existing form custom CSS with all of style.css.
2. Paste header.html into the header control's HTML/source editor.
3. Host the repository's ga@work_logo_white.png, GA@WORK_LOGO_FullColor.png and this folder's
   georgia-state-capitol.jpg at direct URLs accessible to form users.
4. Replace YOUR-WHITE-LOGO-URL, YOUR-FULL-COLOR-LOGO-URL and YOUR-CAPITOL-PHOTO-URL in header.html.
5. Keep the photo credit below the banner, or move it to the form footer.
6. Verify desktop/mobile layouts, image access, and controls in Nintex.

The stylesheet includes the full form theme: page and form backgrounds, group
panels, fields, primary and secondary buttons, and keyboard/disabled states.
Wave artwork is embedded in CSS. header-waves.svg is its editable source.
If data-image backgrounds are blocked, host header-waves.svg and replace the
wave data URI in style.css with its hosted URL.

Photo: Georgia-state-capitol-dome.jpg, Connor.carey, 24 April 2009.
Source: https://commons.wikimedia.org/wiki/File:Georgia-state-capitol-dome.jpg
License: https://creativecommons.org/licenses/by-sa/3.0/
Downloaded original is unchanged. CSS crops/shades its display. Retain attribution
and the license link when using this photo. The reference screenshot's original
photo was not supplied; this version uses a different photo of the same Capitol.

Local preview is a static approximation; Nintex runtime verification is required.

