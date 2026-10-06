Design-11 - Image Backdrop

Uses capitol-backdrop-generated.png, an AI-generated photographic composition
based on the supplied Capitol and banner references. The dome and trees sit on
the right; continuous blue sky leaves space for the logo on the left. This is
an illustrative reconstruction, not an unaltered documentary photograph.

The white/orange logo, title and teal rule are separate HTML/CSS
layers. No workforce slogan is included. Original reference files are retained.

Open preview.html locally to review the sample form.

Nintex setup:
1. Replace form custom CSS with all of style.css.
2. Paste header.html into the full-width header control's HTML/source editor.
3. Host ga@work_logo_white.png and GA@WORK_LOGO_FullColor.png from the repository
   root, plus this folder's capitol-backdrop-generated.png, at accessible URLs.
4. Replace all three YOUR-...-URL placeholders in header.html.
5. Preview desktop/mobile sizes and verify image access and controls in Nintex.

The full form theme includes backgrounds, group panels, fields, primary and
secondary buttons, and focus/disabled states. Earlier designs are unchanged.
The local preview simulates controls; final appearance must be checked in Nintex.


Current control styling:
- Primary and secondary buttons: navy, white text, lighter blue hover.
- Duplicate/remove toolbar actions: 36px buttons with centered ~22px artwork.
- Disabled delete keeps its navy color; Nintex still controls disabled behavior.
- Dropdown focus surrounds the outer control instead of its search input.

Upload design-11-v3.css as a new file and attach it as the form's theme CSS.
It is an identical release copy of style.css with a new name to avoid stale cache.
Replace the previous theme attachment; remove the old row-icon-fix.css attachment
and any previously pasted icon patches. This release contains the whole theme.
Header HTML and hosted image URLs do not need changing.

Open preview.html for local review. It uses the supplied Nintex button markup
and SVG paths, with working row actions and local file selection. No data is
submitted or uploaded. Verify in Nintex's form preview before publishing.

Icon implementation: a fixed 24px SVG viewport is centered in the 36px button.
Only the paths are enlarged using explicit matrices around the SVG's (18,18)
center. This avoids enlarging/displacing the SVG element and its wrappers.

Theme selectors follow Nintex Custom CSS Guidelines:
https://help.nintex.com/en-US/nwc/Content/Designer/CustomCSSGuidelines.htm
Labels: .nx-theme-label-1; text inputs: .nx-theme-input-1;
buttons: .nx-theme-button-1 and .nx-theme-button-2.
Row actions are scoped to ntx-repeating-section and the existing
.ntx-repeating-section-duplicate-btn / .ntx-repeating-section-remove-button.
No per-control custom CSS classes are required. The banner keeps its own HTML
classes because it is custom header content. Dropdown/icon internals are narrow
exceptions based on the supplied markup, not documented theme class guarantees.
