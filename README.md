# Homunculus Exoskeleton

Wearable upper-body exoskeleton for teleoperation and sensing: printed structure, hall-effect joints, joystick input, and Arduino-side muxing for analog reads. This repo holds CAD (STEP), left/right URDF exports, PCB artifacts, firmware for the sensor mux, and a [bill of materials](docs/BOM.md).

## Media

<video src="assets/video.mp4" controls playsinline preload="metadata" width="100%"></video>

If the player does not show in the browser you are using, open the file directly: [`assets/video.mp4`](assets/video.mp4).

<p align="center">
  <img src="assets/exo.png" alt="Homunculus exoskeleton hardware" width="55%">
</p>

## Repository layout

| Path | Contents |
|------|----------|
| [`assets/`](assets/) | Demo video and reference photos |
| [`cad/`](cad/) | STEP assembly export |
| [`docs/`](docs/) | BOM and build notes |
| [`firmware/`](firmware/) | Arduino-style firmware (mux + analog reads) |
| [`PCB/`](PCB/) | Board BOMs/gerbers and the [Martino joystick adapter](PCB/elec_martino_joystick_adapter) submodule |
| [`urdf/`](urdf/) | Left/right robot descriptions (Onshape → URDF) |
