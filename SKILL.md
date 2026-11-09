---
name: swipespread
description: Plan, design, and export seamless 4:5 Instagram carousels from user-provided photos and video. Use for swipe-through photo spreads, framed photo journals, and mixed photo/video carousel posts when the user wants to preserve the original framing.
---

# SwipeSpread

Turn an ordered set of photos and short clips into a carousel with a shared visual rhythm and intentional cross-page joins.

## Plan the spread

- Inspect the supplied media locally. Read photo orientation and dimensions, and preview representative video frames with timestamps. Base captions, times, and names on the supplied material.
- **Main subject.** Use the user's stated lead. If several people could be the lead and the brief leaves the choice unclear, ask who to feature before finalizing the selection. Give the lead the cover and key moments. Use group photos where the lead is still easy to recognize.
- Choose an opening image, a sequence, and a closing image. Sketch which two adjacent pages will share a photo. Place each join away from faces, important text, and other focal details. Give each page a readable composition on its own.
- Establish a palette, frame treatment, and copy size. For a photo-led spread, favor small labels, restrained typography, and a consistent margin. Use the user's preferred language or leave captions off. One option is mist blue-gray `#E1E9ED`, cool white `#FCFDFE`, and dark slate `#18262C`.

## Compose and export

1. Build a shared canvas of `1080 × page_count` by `1350` pixels. Draw shared photos and rules on this canvas before splitting at multiples of 1080 pixels.
2. Apply source orientation and fit photos proportionally inside their frames. Use padding where needed. Preserve source edges across the complete spread, and ensure neighboring prints do not cover each other. Use sRGB for still exports when supported.
3. For a video page, use the requested time range or choose and trim to the relevant beats. Fit the excerpt within the same 1080 × 1350 page. A 648 × 1152 inner frame preserves a 9:16 source. Choose whether to retain ambient sound with the user or from the brief. Export H.264 MP4 with AAC when audio is included, using a widely supported pixel format such as yuv420p.
4. Export numbered posts in swipe order, such as `01.jpg`, `02.jpg`, and `03.mp4`. Keep the stitched preview outside the upload folder. Use a representative frame for a video page in the still preview.

## Iterate and verify

- When a user asks to see a single sample, export that page separately and wait for approval before applying the change across the set. Back up the previous version when requested, including its numbered files and stitched preview.
- Inspect both individual pages and the stitched preview at a phone-sized scale. Check photo edges, visual hierarchy, joins, and whether the number of labels matches the brief. Fix visible gaps and inspect the affected pages again.
- Confirm all exports are 1080 × 1350, ordered correctly, and decode successfully. Inspect the encoded video at the start, around cuts, and at the end. If real-time playback is available, watch the full clip with audio. Report which checks were performed.
- Deliver links to the numbered files and the stitched preview. Keep original media, personal information, and project-specific output out of shared skill repositories. Upload the post itself only when explicitly requested.
