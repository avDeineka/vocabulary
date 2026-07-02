# Project Notes

- Main app file: `dic.html`.
- Data model: `lessons[]`, where each lesson has `id`, `title`, and `words[]`.
- Each vocabulary item uses `{ id, word, translation }`.
- State lives in the `state` object near the top of the script.
- `localStorage` persists the full `lessons` structure under the `lessons` key.
- Keep changes in a single-file style unless the task explicitly requires more files.
- Preserve current UI behaviors unless the user asks to change them.
