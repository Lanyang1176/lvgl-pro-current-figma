# LVGL Pro current Figma binding

This is a conservative LVGL Pro handoff scaffold for the current Figma file.

- Figma document: `VJOm3ZfzAjGQgG9LXL914P`
- Figma root frame: `2:56` / `MusicPlayerScreen`
- Target display: `480 x 206`

The original Figma frame is kept as the source geometry. The LVGL Pro target is a conservative 0.5 scale so the test screen does not treat the oversized Figma canvas as the device resolution.

`project_local.xml` must stay local because it contains the Figma personal access token. Use `project_local.example.xml` as the shape.

LVGL Pro Figma Sync updates XML styles that include `figma_node_id`. It does not auto-import the entire Figma frame; the screen structure still needs to be maintained as LVGL XML.

Open in LVGL Pro Viewer:

```text
https://viewer.lvgl.io/?repo=https%3A%2F%2Fgithub.com%2FLanyang1176%2Flvgl-pro-current-figma%2Ftree%2Fmain%2Fui
```
