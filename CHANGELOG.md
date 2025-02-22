# Changelog

## 2.0.4 (29.06.2022)

- Fix bug, hover over @editorjs/table trigger mutationDebouncer

## 2.0.3 (08.06.2022)

- Fix bug in the undo fuction in the block was dropped validation which prevents blocks that were defined with an id to being drop consistently

## 2.0.2 (07.06.2022)

- Fix bug in the block was dropped fuction, remove unnecesary index comparision

## 2.0.1 (10.05.2022)

- Bug fix in the save function, use indexInState instead of index.

## 2.0.0 (29.04.2022)

- Updated packages with known security breaches.
- Add a new corner case to consider the case when the content has changed in the not current block.
- solve a bug in shortcuts related to the common Mac commands.
- Add a new corner case to handle empty blocks in the editor.

## 2.0.0-rc.3 (14.03.2022)

- Add a custom debounceTimer in the config object to choose the save time.

## 2.0.0-rc.2 (28.02.2022)

- Optimizes the observer, saving with the EditorJS API only when the content changes.

## 2.0.0-rc.1 (24.02.2022)

- Set the caret feature to the undo and redo actions.
- Add support to readOnly toggle.

## 2.0.0-rc.0 (28.12.2022)

- In the undo/redo actions the plugin now updates the involved block.
- Update eslint-plugin-import to support eslint.
- Solve linter errors.

## 1.0.1 (07.12.2021)

- Updated packages with known security breaches.

## 1.0.0 (22.11.2021)

- Set the initial stack data to avoid deleting all the blocks in the last undo.

## 0.3.0 (21.09.2021)

- Custom undo/redo keyboard shortcuts allowed.
- Updated packages with known security breaches.

## 0.2.0 (09.09.2021)

- Accept strings in the holder key.
- Updated packages with known security breaches.
- Docs updated.

## 0.1.7 (16.06.2021)

- Set the undo/redo event listeners in the holder element instead of the whole document.

## 0.1.6 (04.05.2021)

- Read-only mode support added.
- Dependencies updated. Security breaches covered.
- CI with github actions added.
- Minor bug fixes.

## 0.1.5 (05.04.2021)

- Bug fix: Cannot read property 'holder' of undefined.
- Dependencies updated. Security breaches covered.

## 0.1.4 (14.08.2020)

- Bug fix: The editor is not registering any change if its instance is destroyed.
- New feature: The caret state is saved and recovered on each undo/redo operation.

## 0.1.3 (13.07.2020)

- Modify custom MutationObserver to avoid saving changes related to the editor destroy process.

## 0.1.2 (29.06.2020)

- Added custom MutationObserver to save changes in a shorter period of time.

## 0.1.1 (24.06.2020)

- Added support for Mac users using <kbd>⌘</kbd> + <kbd>Z</kbd> and <kbd>⌘</kbd> + <kbd>Y</kbd>.
- Bug fixes and other minor improvements.

## 0.1.0 (23.06.2020)

Initial release
