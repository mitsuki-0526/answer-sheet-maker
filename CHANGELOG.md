# Changelog

## v0.8.0 - 2026-05-18

- Added initial automatic pagination that keeps questions together across multiple sheets.
- Updated dynamic page numbers and status bar page count.
- Applied selected paper size and orientation to rendered sheet dimensions.
- Added print page breaks for multi-page output.

## v0.7.0 - 2026-05-18

- Added working ribbon tab switching for File, Home, Insert, Paper, Question, View, and Help.
- Added File tab commands for new document, JSON open/save, and print/PDF output.
- Added Insert tab commands for answer-area insertion, textbox insertion, and page number toggling.
- Added Paper tab shortcuts for paper size, layout, margins, center line, page number, and score display settings.

## Documentation - 2026-05-18

- Set v0.12 as the initial achievement target.
- Moved vertical writing, mobile support, and Firebase sharing to future updates.

## v0.6.0 - 2026-05-18

- Added vertical alignment support for text inside floating textboxes.
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
