# Homunculus Exoskeleton

Whole-body control exoskeleton: printed structure, hall-effect joints, joystick input, and Arduino-side muxing for analog reads. This repo holds CAD (STEP), left/right URDF exports, PCB artifacts, firmware for the sensor mux, and a [bill of materials](docs/BOM.md).

## Media

![Demo clip](assets/demo.gif)

Full-quality video: [assets/video.mp4](assets/video.mp4)

![Homunculus exoskeleton hardware](assets/exo.png)

## Repository layout

| Path | Contents |
|------|----------|
| [`assets/`](assets/) | Demo GIF/MP4 and reference photos |
| [`cad/`](cad/) | STEP assembly export |
| [`docs/`](docs/) | BOM and build notes |
| [`firmware/`](firmware/) | Arduino-style firmware (mux + analog reads) |
| [`PCB/`](PCB/) | Board BOMs/gerbers and the [joystick adapter](PCB/elec_martino_joystick_adapter) submodule |
| [`urdf/`](urdf/) | Left/right robot descriptions (Onshape → URDF) |
