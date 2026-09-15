# Blue Striker look mechanics

Standard rows pass independent visual QA after left-row regeneration and shared-scale jump extraction.

Keep boots, legs, lower torso, tail root and football planted in the approved idle pose. Football stays against the same boot on screen-right; never changes side or floats. Hands rest beside body. Preserve black/white feline face, blue eyes, muzzle, pointed ears, spiky hair, blue outfit and proportions.

The neck turns the separate head naturally. Eyes lead with whole eyeball/eyelid redraw inside original apertures, then muzzle and ears follow. Slight upper chest follow-through is allowed but feet, ball and torso width remain stable. No whole-sprite rotation, skew, face warping, new eye layer or pupil-only substitute.

Cardinal families in viewer coordinates:
- 000 UP: raise chin and nose; eye gaze and lids clearly aim above, show underside of muzzle. Keep broad frontal face, both ears visible.
- 090 SCREEN-RIGHT: head yaws right; nose-tip and pupils visibly right of head center, nearer left cheek more visible, far right eye partly occluded. Keep level vertical gaze.
- 180 DOWN: lower chin and nose; eyes/lids look below toward football, show more hair crown and less underside muzzle. Keep broad frontal face.
- 270 SCREEN-LEFT: head yaws left; nose-tip and pupils visibly left of head center, nearer right cheek more visible, far left eye partly occluded. Keep level vertical gaze.

Interpolate 16 evenly spaced clock directions, modest but readable head yaw and pitch. At each 22.5-degree step, move head orientation and eyes by comparable amounts; no posture/scale jumps. Diagonals carry both horizontal and vertical axes. Row 9 follows up through right toward down; row 10 starts down exactly one step later, turns through left toward up. Final 337.5 is one step before 000. All poses differ visibly from neutral. Preserve skull size, muzzle, eye construction, clothing and ball placement throughout.
