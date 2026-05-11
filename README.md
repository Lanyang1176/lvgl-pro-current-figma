# LVGL Pro current Figma binding

This is an LVGL Pro handoff scaffold for the current Figma file.

- Figma document: `VJOm3ZfzAjGQgG9LXL914P`
- Figma root frame: `2:56` / `MusicPlayerScreen`
- Target display: `960 x 412`

The original Figma frame is the source geometry. The LVGL Pro target matches the current frame at `960 x 412`.

`project_local.xml` must stay local because it contains the Figma personal access token. Use `project_local.example.xml` as the shape.

LVGL Pro Figma Sync updates XML styles that include `figma_node_id`. Per the official Figma Integration docs, this is not a magical auto-importer: the screen structure is maintained as LVGL XML, and the copied/synced Figma styles attach to real XML objects. `screens/music_player.xml` is therefore an XML-composed screen, while `music_player_screen.png` is kept only as a visual reference asset.

Open in LVGL Pro Viewer:

```text
https://viewer.lvgl.io/?repo=https%3A%2F%2Fgithub.com%2FLanyang1176%2Flvgl-pro-current-figma%2Ftree%2Fmain%2Fui
```
