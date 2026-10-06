# Images

Every picture on the site is a **slot**. If the file exists, it shows. If it
doesn't, the page shows a dashed "PHOTO SLOT" box with the filename it wants.
So adding a photo is just: save it here with the right name, commit, push.
No HTML edits needed.

Landscape photos (roughly 4:3 or 16:9, about 1200-1600 px wide, JPEG) look best.

## Empty slots waiting for photos

| File | What goes there |
|---|---|
| `cnn_accelerator.jpg` | FPGA board or simulation waveform for the CNN accelerator |
| `rrc_fpga_board.jpg` | Cyclone IV board running the RRC filter |
| `itch_waveform.jpg` | ITCH decoder waveform screenshot or block diagram |
| `slam_car.jpg` | The CEV car / LiDAR sensor rig |
| `tils.jpg` | Screenshot of the Tils compare screen |
| `lowlight_bms.jpg` | Low Light Innovations BMS board render or photo |
| `quantum_setup.jpg` | Optical bench or alignment GUI screenshot |
| `cev_can_dashboard.jpg` | CEV CAN dashboard PCB |

## Already filled

`headshot.jpg`, `rrc_constellation.jpg`, `rrc_eye.jpg` (from the rrc-matched-filter
repo), `slam_vis.jpg`, `slam_desk.jpg`, `igvc_dashboard.jpg` (from cornellev/igvc-dashboard),
`polymer.jpg`, `xray.jpg`, `quantum_focus_curve.png`, `weld.jpg`, `matter.jpg`.

To swap one, overwrite the file with the same name.

## Adding a new project

In `index.html`, search for `TEMPLATE: copy this block`. Copy the commented
block, paste it above that comment, and fill it in.
