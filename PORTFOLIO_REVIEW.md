# Portfolio review and evidence checklist

This branch is a reviewable draft. Original image files are retained. Existing pictures were identified by their filenames and original page captions; confirm they are accurate, yours to share, and not stock or unrelated images. Replace inaccurate images rather than retaining them for visual polish. Do not publish internal CAD, research plots, team reports or client information without permission.

## Fast editing

1. Upload a real image to assets/ using the exact suggested filename below.
2. In the corresponding HTML page, find the figure with data-asset matching the filename.
3. Replace the placeholder's inner div with the markup below, keeping the caption and updating it with actual context.

    <div class="image-frame"><img src="assets/your-image.png" alt="Specific description of the image" loading="lazy" decoding="async"></div>

Add actual test conditions, units, material, dimensions or plot labels to captions where relevant. Screenshots of CAD and simulations are strongest when the reader can tell what they prove. Keep plots readable on mobile. Compress large photos and remove sensitive metadata.

## Suggested images in priority order

| Page | Filename | What to include |
|---|---|---|
| Trinity | trinity-prototype.jpg | Scaled printed frame and joint close-up |
| Trinity | trinity-python-model.png | CAD-derived node/member model and displacement scale |
| Trinity | trinity-monte-carlo.png | Matched optical spot clouds, field angles, units and sample count |
| Trinity | trinity-operations.jpg | Approved telescope operations or optical-protection concept |
| Off-Road | offroad-loadcase.png | Sanitized FBD and governing load calculations |
| Off-Road | offroad-reducer-cad.png | Actual CAD, material and key tolerances |
| Off-Road | offroad-reducer-machined.jpg | Actual manufactured reducer or installed joint |
| Off-Road | offroad-fea.png | Stress/deformation plot with load, restraints, units |
| ME 2110 | me2110-hoq.png | HOQ or weighted decision matrix excerpt |
| ME 2110 | me2110-assembly.png | Final CAD with mechanism labels |
| ME 2110 | me2110-fabrication.jpg | As-built robot, chassis and mechanism details |
| ME 2110 | me2110-test.jpg | Autonomous testing or competition run |
| ME 2110 | me2110-iteration.png | Failed component beside revised geometry |
| Wind turbine | turbine-rotor-detail.jpg | Rotor/motor connection |
| Wind turbine | turbine-blade-cad.png | Blade geometry and CFD domain |
| Wind turbine | turbine-cfd.png | Velocity or pressure contour with legend |
| Wind turbine | turbine-paper.png | Approved excerpt from the technical paper |

For the ME 2110 project card on index.html and projects.html, replace the concept schematic with an image tag for the real assembly when available. The existing original photo and CAD images on other cards can be replaced in place.

## Facts to verify before publishing

- Trinity: final optics coordinate conventions, benchmark validation, loading and restraint assumptions, Monte Carlo distributions, quantitative alignment requirements; do not publish unresolved numerical spot sizes as final.
- Off-Road: final bolt diameter and grade, reducer material/dimensions, preload, bearing/tear-out results and factors of safety; do not use illustrative dimensions as as-built specifications. Verify team permission for release.
- ME 2110: actual final score and cost, reliability by sprint and competition placement, final mechanism revisions and individual contributions. The $120 and 60-point figures in the case study are early sprint targets only.
- Wind turbine: test wind speed and electrical load, current/voltage measurement method, curve axes, CFD mesh/boundaries and paper sharing permission. The 15–20 W output is from the résumé, not an inferred rated power.
- GSU: verify plot and apparatus labels, data-sharing permissions; no accuracy or calibration metric asserted without results.
- FIRST Robotics: original site reports $10k+ sponsorship and team awards; confirm these are correct and approved to mention.
- Maker Spaces: keep prospective status until formal appointment. Solar Racing and CubeSat were on the original site but not in the latest résumé; their original images are preserved. Restore substantive descriptions only after confirming role and actual contributions.
- Contact: current email and LinkedIn are retained; personal phone is omitted from the public contact page.
- Résumé: HTML version follows the supplied résumé and can print to PDF; upload the original PDF only if you want it available publicly.

## Preview and publish

Check the homepage and every case study on desktop and mobile. Test navigation, anchor links, image captions, print layout and email link. Search for DOCUMENTATION SLOT to see remaining visible placeholder figures. Remove a slot if you cannot provide a useful public artifact; the text remains readable without it. Merge the review branch only when satisfied. The live site remains untouched until your normal deployment process runs.
