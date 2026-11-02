# Independent standard-row visual review

Reviewed the populated contact sheet and separately rendered native-resolution frame sequences for idle, running-right, waving, jumping, failed, waiting, running (active work), and review. Running-left is excluded because its repair is in progress. This is sequential-frame visual review, not a claim that the final encoded animation has been played in a video client.

## Findings

- Idle: pass. Six complete figures retain face, costume, braids and asymmetric sleeves. A blink is clear in frame 1; the remaining changes are small head/breathing/sway variations. Feet remain registered.
- Running-right: pass with a motion-polish warning. All eight poses face screen-right and retain complete trailing braids/boots. Stride phases vary, with planted, bent and lifted legs. Frames 1 and 2 are similar and the near-arm swing is more restrained than the leg cycle, so the cadence is stylized rather than smooth high-frame-rate animation. No wrong-direction frame or clipped figure is visible.
- Waving: pass. Rest, raised hand, wrist tilt, and rest form a readable four-frame greeting. Face and sleeve/tattoo sides remain consistent.
- Jumping: pass. Crouch, takeoff, apex, descent and landing are readable. Alpha>16 baselines are 200, 188, 154, 201, 202 px; idle baseline is 202 px. Apex rises 48 px and landing matches idle. Pose scale stays coherent through bent knees and changing arm spread; headroom and extremities remain inside cells.
- Failed: pass. Flinch, bowed posture, facepalm and recovery are distinct from idle and waiting; braids stay attached.
- Waiting: pass. Upturned palm, shrug and sideward expectant glance are readable. Boots remain on the same baseline.
- Active work: pass. Temple tap, chin/hand concentration and a small knowing expression communicate thought; no foot-running or added object.
- Review: pass. Forward lean, narrowed downward attention and head tilt communicate inspection. The lower body remains registered; the changing head height follows bending, not character resizing.

## Remaining checks

Thin magenta edge pixels remain visible on some hair/boot boundaries and must be handled by the required final despill pass. Final encoded-sheet motion, the repaired left run, all sixteen look directions, and final structural/quality validators remain outside this review. No blocker was identified in the eight reviewed source-row sequences.
