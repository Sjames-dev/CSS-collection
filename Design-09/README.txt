Design-09 - Nintex form theme

1. Replace the form's existing custom CSS with the entire style.css file.
   Do not append main.css or a different design's CSS afterward.
2. Replace the header control's HTML with header.html using its source editor.
3. Host GA@WORK_LOGO_FullColor.png (from the repository root) at a direct image
   URL accessible to form users. Replace YOUR-FULL-COLOR-LOGO-URL in the HTML.
4. Use a full-width header control and remove old inline logo/header sizing.
5. Preview at desktop and phone widths before publishing. Check image access
   as a normal form user, field validation, and primary/secondary buttons.

Included: pale page background, white form shell, subtle group panels, navy
primary buttons, outlined secondary buttons, and focus/disabled states.
The header has a black/orange logo, black subtitle, and layered blue, light-blue,
and orange waves with white separators. The circled 9 is a reference design
identifier and is excluded from the production header.

The waves are SVG artwork embedded as a CSS background data URI; no empty wave
HTML elements or extra hosted wave file are required. header-waves.svg is the
editable source. If your Nintex environment blocks data-image backgrounds, host
header-waves.svg at an allowed image URL and replace the data URI in the header's
background-image declaration with that URL.

Open preview.html locally to view a sample form with the supplied logo. This is
a static preview, not a Nintex runtime test. Theme selectors use the nx-theme
classes from the existing form CSS. Existing validation colors and control
behavior are retained; verify the deployed form before publishing.
