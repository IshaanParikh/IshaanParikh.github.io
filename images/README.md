# Images

Every picture on the site is a `<figure class="shot">` with an `<img src="images/...">`.
If a file is missing, the figure collapses to its caption, so a typo never shows
a broken-image icon. To swap a picture, overwrite the file with the same name.

Landscape photos (roughly 4:3 or 16:9, about 1200-1600 px wide, JPEG) look best.
Below-the-fold images use `loading="lazy"` and carry `width`/`height` so the page
doesn't jump while they load; keep those attributes in sync if you replace a file
with different dimensions.

## Photos that would help

| File | What goes there |
|---|---|
| `cnn_accelerator.jpg` | FPGA board photo for the CNN accelerator (once it runs on hardware) |
| `rrc_fpga_board.jpg` | Cyclone IV board running the RRC filter (once demonstrated) |
| `lowlight_bms.jpg` | Low Light Innovations BMS board render or photo |
| `cev_can_dashboard.jpg` | Fabricated CEV CAN dashboard PCB |

## In use

`headshot.jpg`, `rrc_constellation.jpg`, `rrc_eye.jpg` (from the rrc-matched-filter
repo), `slam_sim_result.svg`, `slam_vis.jpg`, `slam_desk.jpg`, `polymer.jpg`,
`xray.jpg`, `quantum_focus_curve.png`, `waveguide_alignment_v2.mp4` (+ poster),
`weld.jpg`, `matter.jpg`, `cev_layout.png`, `cev_sch_*.svg`,
`cev_dashboard_schematic.pdf`, `cev_dashboard.glb` (3D viewer, loaded on click).

Simulation waveforms (rendered from the testbenches' VCD dumps):
`cnn_winograd_waveform.png`, `rrc_waveform.png`, `itch_waveform.png`.

`og-card.jpg` (1200 × 630) is the link-preview image for LinkedIn, Slack, etc.
It is a screenshot of the hero; regenerate it if the hero text changes.

## Adding a new project

In `index.html`, search for `TEMPLATE: copy this block`. Copy the commented
block, paste it above that comment, and fill it in. Give it a short stable `id`
(used for the shareable `#link`) and only mark a status pill `ok` when a test,
report, or doc in the linked repo backs it.
