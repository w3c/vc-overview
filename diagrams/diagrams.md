# Generation of the diagrams

Some of the diagrams are, originally, in the [draw.io](https://www.drawio.com/) format. _Any change on those diagrams must be made by modifying the files in this directory._  The editing application can be downloaded and used directly, or added to Google Docs. Note that, due to some bug(s) in the software, and to improve the exported SVG file, it must be run through a [post-processing script](https://github.com/iherman/drawio-svg/), which must be downloaded and run separately.

When editing the diagram in draw.io
- Under "Diagram" no background color

When creating/updating a diagram in SVG from draw.io:
- Export to SVG with 
  - zoom 100%
  - border width: 20
  - size: diagram
  - transparent background
  - appearance: light
  - no shadow
  - no copy of my diagram
  - no embed images
  - no embed fonts
  - link automatic

then run draw-svg (this cleans up the header to make the image scalable).

The dark/light mode of draw.io only creates difficulties; the W3C stye automatically sets a background to white (there is an entry in CSS to make it "less" white).
