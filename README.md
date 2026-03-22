# Homunculus Exoskeleton

Whole-body control exoskeleton: printed structure, hall-effect joints, joystick input, and Arduino-side muxing for analog reads. This repo holds CAD (STEP), left/right URDF exports, PCB artifacts, firmware for the sensor mux, and a [bill of materials](docs/BOM.md).

<table>
<tr valign="top">
<td width="72%"><img src="assets/demo.gif" alt="Demo clip" width="100%"/></td>
<td width="70%" align="center"><img src="assets/exo.png" alt="Homunculus exoskeleton hardware" width="500"/></td>
</tr>
</table>

## Repository layout

| Path | Contents |
|------|----------|
| [`assets/`](assets/) | Demo GIF/MP4 and reference photos |
| [`cad/`](cad/) | STEP assembly export |
| [`docs/`](docs/) | BOM and build notes |
| [`firmware/`](firmware/) | Arduino-style firmware (mux + analog reads) |
| [`PCB/`](PCB/) | Board BOMs/gerbers and the [joystick adapter](PCB/elec_martino_joystick_adapter) submodule |
| [`urdf/`](urdf/) | Left/right robot descriptions (Onshape → URDF) |
