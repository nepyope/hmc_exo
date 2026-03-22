# Homunculus Exoskeleton

Whole-body control 7DOF device

<table>
<tr valign="top">
<td width="50%"><img src="assets/demo.gif" alt="Demo clip" width="100%"/></td>
<td width="70%" align="center"><img src="assets/exo.png" alt="Homunculus exoskeleton hardware" width="200"/></td>
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
