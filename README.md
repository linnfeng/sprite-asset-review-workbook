# Sprite asset review workbook

This is a manual review resource for small game projects, not an executable validator, animation package, or tested engine integration. Its purpose is to help a designer explain why a character image is ready for the next step, or why it needs another revision. Copy the questions into your own project notes and answer them with observations from the actual image. An empty field is an open question, not evidence that an asset passed a check.

The workbook is associated with promoting Sprite Maker and was prepared with AI assistance. It is not an independent review or a claim of measured product performance. Sprite Maker provides AI character generation, direction views, NPC sets, pixel refinement and transparent PNG export. The tool reference is https://spritemaker.app/ . Current credit allowances, prices and terms should be checked there. The workflow below can also be applied to images made with other tools or drawn manually.

![Sprite Maker public product illustration](https://spritemaker.app/og.png)

The image above is the project's public product illustration. It is not a screenshot of a test run, proof of quality, or an example of an asset approved by this workbook.

## 1. Describe the intended use

Begin with the role of the asset rather than the details of the prompt. A hypothetical village courier may need to remain recognizable beside a guard, carry a bag, and face toward the next area of a scene. Those requirements are more useful than an unranked list of adjectives. Write down the intended display size and whether the image is a static portrait, a directional view, or a candidate frame for later animation work.

Separate a requirement from a preference. A clear silhouette might be necessary for gameplay, while a particular scarf color might be negotiable. If both are labeled critical, a reviewer cannot make a useful tradeoff when a simpler image reads better. Record the small number of features that must survive reduction. This gives later revisions a stable reference instead of allowing the newest attractive image to silently redefine the project.

Review fields: asset identifier; intended role; intended display size; view direction; required visual cues; optional details; known exclusions.

## 2. Record provenance without exposing private material

Keep enough information to explain where the candidate came from. That might include a local filename, the date of generation or drawing, and a short description of any reference material. Do not put credentials, private upload addresses, personal photographs, or confidential customer artwork into a public review record. A team can keep private provenance details in its own authorized storage while using an innocuous asset identifier in a shared checklist.

Provenance is not a substitute for permission. A generated result and the reference used to create it may raise separate questions under the relevant terms. Record unresolved rights questions explicitly and ask the appropriate owner before distributing the asset. Do not assume that a successful export grants every commercial use, or that a visual resemblance is harmless simply because it appeared during generation. This workbook does not make legal determinations.

Review fields: candidate filename; reference permission checked; private material excluded from shared notes; terms reviewed; unresolved permission questions.

## 3. Inspect the silhouette before the details

View the character at its intended size before zooming in. Identify the body, limbs, carried objects and facing direction without relying on tiny decorative marks. For the courier example, the bag should be distinguishable from the torso if it is an essential cue. If the pose only becomes understandable after zooming, note the specific ambiguity rather than writing a vague comment that the art lacks polish.

Compare the candidate on representative light and dark backgrounds. This is a bounded check, not proof that it works in every environment. Vegetation, particles and moving scenery can create different difficulties from a flat background. Write down the backgrounds actually used and whether the outline remains legible. A later in-scene review can extend the evidence without pretending that it was part of the earlier inspection.

Review fields: native-size inspection completed; silhouette concerns; light-background result; dark-background result; scene testing still required.

## 4. Compare direction views as a set

Place the available views beside one another and compare proportions, costume features, carried objects and visual emphasis. The same character should remain recognizable even when details are not identical. A bag that moves to the other shoulder without a design reason may be an inconsistency. An intentionally asymmetric outfit, however, should not be forced into symmetry merely to make the comparison easier. State the intended design before judging the result.

Direction views are not automatically animation frames. Movement introduces separate questions about timing, contact with the ground, transitions and whether the pose supports the action. If only static views have been inspected, call them static views. Do not hand them to a collaborator as a tested walk cycle. A precise label helps the next person estimate the remaining work and avoids turning a useful concept into a misleading promise.

Review fields: views available; proportion differences; equipment consistency; intentional asymmetry; missing views; animation checks not yet performed.

## 5. Make a revision that addresses one observation

Choose a concrete problem and describe the smallest useful edit. Removing a stray pixel, simplifying a confusing color cluster, or separating an arm from the body gives the reviewer an observable before-and-after comparison. Changing many unrelated details at once can make it harder to understand which edit improved readability. Small revisions are not always sufficient, but they are a useful first option when the underlying design already meets the brief.

Keep the earlier candidate available while reviewing the new version. A pair of clearly named files and a short note may be enough for a small prototype. Record any tradeoff introduced by the change: a cleaner silhouette may remove costume detail, for example. That can be acceptable if it serves the intended display size. The important point is that the decision is explicit rather than discovered accidentally during a later handoff.

Review fields: observed problem; chosen change; earlier filename; revised filename; improvement observed; new tradeoff; next decision.

## 6. Examine the exported file

Open the actual transparent PNG after export. Confirm the dimensions, inspect the edges and transparency, and look for clipping or unexpected margins. A correct-looking editor preview does not prove that the exported file has the layout expected by the receiving project. If an engine or another editing application is available, import the file through its normal workflow and record what was actually checked rather than assuming compatibility from the file extension.

Naming and arrangement are part of the handoff. A static character image, a group of separate directions and a combined sheet can require different handling. State what the file contains and what it does not contain. Do not infer a complete animation set, collision data or engine configuration from a transparent image alone. Those may be future tasks, but they should not be described as delivered capabilities unless the corresponding artifacts exist and have been checked.

Review fields: exported filename; pixel dimensions; transparency inspected; clipping or padding concerns; receiving application tested; missing companion files.

## 7. Write a limited approval note

An approval note should describe the evidence and its boundaries. For a hypothetical courier, it might say that a static front view was checked at native size on two flat backgrounds, while animation and in-scene testing remain outstanding. This is more useful than a broad statement that the asset is game ready. The next collaborator can see what has already been done and can focus on the unresolved questions instead of repeating every check.

If the candidate is rejected, preserve the reason in neutral language. The goal is not to judge the creator or the tool but to explain a mismatch with the current brief. A version that does not suit one display size may still be useful elsewhere. Keep that possibility separate from the present decision. Clear records support iteration without turning every revision into a claim that the previous work was worthless.

Review fields: accepted for which next step; evidence reviewed; limitations; unresolved tasks; reviewer; review date.

## Minimal reusable decision record

Use the following plain-text structure as a starting point. It is a documentation template, not a script, and no automated tests or validation results are implied.

```text
Asset identifier:
Intended use and display size:
Candidate file:
Reference permissions and privacy notes:
Observed problem:
Revision made:
Export checks actually performed:
Approved next step:
Unresolved checks:
Reviewer and date:
```

A prompt is a request and an image is a candidate response. Approval is a separate decision supported by inspection. The benefit of a review workbook is not that it eliminates judgment; it makes judgment visible enough for another person to understand, repeat where appropriate, and revise when new evidence appears.
