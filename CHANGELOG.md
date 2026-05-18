# Changelog

## Documentation - 2026-05-18

- Set v0.12 as the initial achievement target.
- Moved vertical writing, mobile support, and Firebase sharing to future updates.

## v0.6.0 - 2026-05-18

- Added top and bottom margin controls with JSON persistence and Undo/Redo support.
- Extended the sheet body to fill the remaining page height so column dividers reach the bottom margin.
- Added phase A Undo/Redo history using in-memory snapshots.
- Enabled Undo/Redo buttons and Ctrl+Z / Ctrl+Y / Ctrl+Shift+Z shortcuts for non-text editing operations.
- Covered title changes, paper settings, question add/delete/settings, JSON import, and basic textbox operations.
- Added phase B history capture for cell text input, textbox text input, formatting commands, alignment, vertical alignment, and cell clearing.
- Fixed textbox edit focus showing a duplicate inner border and made textbox move/resize history capture independent from text editing history.
- Improved the textbox resize handle hit area and event handling so resizing starts reliably.
- Fixed textbox background color options so transparent, white, and gray render distinctly.

## v0.5.0 - 2026-05-18

- Added inline title editing on the answer sheet header.
- Synchronized edited titles with the hidden `#title` field and title bar document name.
- Kept JSON export/import title handling compatible with existing data.

## v0.4.0 - 2026-05-18

- Initial baseline imported from `answer_sheet_maker_v4.html`.
- Added GitHub Pages entry file as `index.html`.
- Added distributable copy as `answer_sheet_maker.html`.
- Added project documentation and repository metadata.
