Design-07 - Nintex form theme

1. Replace the form's existing custom CSS with the entire style.css file.
   Do not append main.css or another design's CSS after it.
2. Paste header.html into the header Text/HTML control's source editor.
3. Host these two files from the repository root at URLs form users can access:
   - ga@work_logo_white.png -> YOUR-WHITE-LOGO-URL
   - GA@WORK_LOGO_FullColor.png -> YOUR-FULL-COLOR-LOGO-URL
   Replace both placeholders in the HTML. Use direct image URLs, not sharing pages.
   Both images are needed: the color image overlays only the orange power symbol.
4. Keep the header control full width. Remove any old inline header sizing and
   old custom-form-header / ga-header CSS overrides.
5. Preview the form at desktop and phone widths before publishing. Verify logo
   access as a normal form user and check primary/secondary buttons and fields.

The theme includes a pale page background, white form shell, subtle group panels,
navy buttons, secondary buttons, keyboard focus outlines and disabled states.
The banner uses CSS gradient stripes, so no separate stripe asset or empty HTML
spans are required. The small circled 7 in the reference is a design identifier
and is deliberately excluded from the production header.

Open preview.html locally for a sample with the supplied logo files. This is a
static layout preview, not a Nintex runtime test. The theme uses the nx-theme
classes from the existing stylesheet; confirm them in your deployed form if a
particular control does not pick up its styling. Existing validation colors and
Nintex control behavior are retained.
