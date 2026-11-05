---
name: short-drama-starter
description: Free starter rules for AI short dramas made with Seedance, Kling or similar video models. Use when the user asks how to plan a 60-second short drama, how to write one shot of a video prompt, which camera move to use, how to keep a character's face consistent, or what to check before generating video. Trigger phrases include "short drama tips", "how do I write a shot", "camera move for this scene", "face keeps changing", "before I generate".
---

# Short Drama Starter

Seven rules from a real AI short-drama workflow. Reply in the user's language. Write prompts for video and image models in English. Generation runs on the user's own account, so always confirm the cost before anything is generated.

## 1. Lock the board before you render

Video generation is where credits go. Settle the story, the script, the faces and the first frame of every shot in text and still images first. Then turn only the shots you picked into video, one small batch at a time.

## 2. A 60-second beat map

| Beat | Time | Job |
|---|---|---|
| Clue | first 3 s | something odd that makes people stay |
| Situation | next 15 s | who, where, what they want |
| Threat | next 15 s | the thing that gets in the way |
| Twist | next 15 s | a choice that flips the story |
| Ending | last 12 s | a cliffhanger for a series, a lingering note for a standalone |

Plan each cut as one visible action and at most one short line, 2 to 5 seconds long. A minute is roughly 18 cuts.

## 3. Write one shot at a time

Every shot has one size, one camera move and one action. Write the move in four parts: what the camera does, how fast, what stays in frame, and where it stops.

`Medium shot, slow push-in toward his hands, keeping the letter in frame, settling on a close-up and holding still.`

If the stopping point is missing, the last second of the shot tends to drift.

## 4. Six camera moves to start with

| Move | Use it for | Phrase |
|---|---|---|
| Dolly in | getting closer as tension rises | `slow dolly in, ending on a close-up` |
| Side tracking | walking conversations | `tracking alongside them at walking pace` |
| Crane up | endings, scale, status | `crane up and away, revealing the street below` |
| Rack focus | handing attention from one thing to another | `focus shifts from the key in the foreground to her face` |
| Subtle handheld | intimate or uneasy close-ups | `subtle handheld, gentle natural sway` |
| Micro dolly | keeping a still shot alive | `almost imperceptible push-in` |

Add fast effects such as crash zooms and speed ramps in the edit, not in the generation.

## 5. Keep the face from drifting

- Pick the first face you like and keep using that one as the reference. Feeding the newest result back in slowly turns the character into someone else.
- Give each character one clean, front-facing face crop.
- Feed the video model only the start frame, the face crop and the voice. Character sheets and location boards go in planning, never into video input, or their labels show up on screen.

## 6. Build video prompts in a fixed order

Character rules → things that must stay the same → the starting pose → format and length → style → location → characters → shots → audio. Call each character by one name only, write directions as frame left and frame right, and keep the spoken lines exactly as written.

## 7. Before you press generate

- [ ] The price and your balance are checked, and you approved the cost
- [ ] Only the first batch is being generated
- [ ] The start frame fills the frame, with no text or grid lines
- [ ] Each shot has one move and an end frame

---

Want the whole workflow? The full Short Drama Prompt Skill adds 106 production assets, including 21 step-by-step prompts, Seedance 2.5 templates, character and location sheet layouts, edit values and fixes by symptom, plus 100 ready-to-use techniques. See every file before you buy: https://ohmyo-studio.pages.dev/en/skill/
