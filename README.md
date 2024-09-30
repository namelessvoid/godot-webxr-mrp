# Godot XR MRP

Minimal Godot project to reproduce an AR issue. It contains a single scene with four colored boxes.

It is intended to be run on a tablet or smartphone.

## Run from editor

1. To make the project accessible from the editor, you have to expose Godot's built in web server to your local network. In the menu bar, select "Editor" > "Editor Settings". Find the "Export" > "Web" section. Change "HTTP Host" to "0.0.0.0" and enable HTTPS by enabling "Use TLS".
2. Now start the project via "Remote Debug" > "Web" > "Start HTTP Server".
3. Open Chrome on your Smartphone or Tabled. Navigate to "https://<your-dev-machine-ip>:8060/tmp_js_export.html"

## Frun from GH pages

The project is also availabe as a pre-built version on [https://www.simonkerler.de/godot-webxr-mrp/dist/](https://www.simonkerler.de/godot-webxr-mrp/dist/).
