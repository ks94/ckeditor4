@bender-tags: 4.16.0, feature, 3582
@bender-ui: collapsed
@bender-ckeditor-plugins: sourcearea, wysiwygarea, floatingspace, toolbar, autocomplete, textmatch
@bender-include: _helpers/utils.js

*Repeat steps below for all 3 editors and modes (Left, Right and Bottom).*

1. Select mode (horizontal or vertical).
1. Place cursor as close as possible to window border.
1. Type `@`.

## Expected

Mention panel should be appeared inside browser borders.

## Unexpected

Mention panel appears outside browser borders.