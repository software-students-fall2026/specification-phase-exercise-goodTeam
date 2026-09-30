
# Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. In this exercise, your team specifies a set of improvements and new features for [The Slide Machine](https://theslidemachine.com) — see the [instructions](instructions.md) for detail, and the [background](background.md) for an introduction to the software product you are tasked with extending.

## Team members

### Team
#### Sanay Daptardar [sanay-d-nyu](https://github.com/sanay-d-nyu)
#### James Li [DyingRavioli](https://github.com/DyingRavioli)
#### Ryan Jiang [UIYrj](https://github.com/UIYrj)

## Review of the Current Application

### Findings
- Strength: The slides made are quite accurate to what was spoken.
- Strength: Images generated are relevant.
- Weakness: Some slides break when switching between designs.
- Weakness: 'Refine with AI' feature makes the spoken part sound very robotic
- Gap: No way to add images to a slide after it's been generated from speech.
- Gap: No way to add a regular title/text slide after the fact.
- Strength: Exit ticket generated had relevant questions and was nicely customizable.
- Strength: Connection to google drive for exit ticket and sharing 
- Strength: Export options are nice and easy to use
- Gap: Great as a text-to-slides tool, could be brushed up as a slide-editing tool.

## Prior Art & Originality

In the project's repo [here](https://github.com/bloombar/slide-machine), we checked the following sections:
- Sections 18 and 19 - Future work and Open Questions - of [the spec document](https://github.com/bloombar/slide-machine/blob/better-faster/docs/SPEC.md)
- Open PRs
- Open issues

Our AI tool creation concept we propose doesn't seem to appear in any of these sections.

## Stakeholders

### LC (Student):
LC is a junior studying Computer Science at NYU.

Goals:
- Easily create formal and detailed slides for software presentations
- Access and annotate lecture slides for studying
- Have easy and quick tools to design and populate slides without much work
- Use AI integration to enrich slides and provide more indepth control of slide application

Frustrations: 
- Voice recognition sometimes doesn't catch on my words
- Don't want to always dictate/want to have some partially planned slides
- Wants more customizability with slides; add and move text, images, etc
- Generated slides don't go indepth enough into the topics; seems very superficial

### JH (Student):
JH is a junior studying Game Design and Media, Culture, and Communication at NYU.

Goals:
- Create understandable and easily readable slides
- Create interactable elements like polls and surveys to conduct media-related research
- Have widely customizable and creative tools to create popping and artistic slide visuals
- Cool slideshow interactions that allow it to function for non-presentation purposes (animation/game)

Frustrations:
- Lack of artistic and creative tools to expand styling capabilities
- Voice recognition and generation was laggy, especially on mobile device
- Slides created seemed to generic and boring
- Wants privacy features; slides shouldn't automatically be posted into the discover panel

### EH (Presenter):
EH is a Technical Operations Manager at NYU.

Goals:
- Create formal but inviting slides that conform to NYU branding
- Explain production space/equipment offerings by NYU to faculty/students in quick and concise way
- Accurately describe workflows and tutorials on how certain AV equipment work
- Formulate well designed and easy to follow slideshows for future documentation and reference

Frustrations:
- Text generation feels like a transcription rather than an aid
- Wants AI to catch up and add things that presenter may have forgotten during the talk
- Image generation is risky and may generate wrong or inaccurate visuals
- Felt too chronological; newly generated slides rarely reference old topics


## Product Vision Statement

We propose to add an editing toolbar for use after a lecture has already been generated, with an AI tool editing feature.

## User Requirements

### User 1: student
1. As a student, I want to see which slides were edited after the lecture so that I know how the deck differs from what I heard.
2. As a student, I want to see the corrected version of a slide with a note that it was changed so that I trust the study material.
3. As a student, I want to choose between the "as lectured" deck and the "final edited" deck so that I can study either.
4. As a student, I want to add private notes to a slide so that I can study from one place.
5. As a student, I want to flag a slide as unclear or possibly wrong so that the instructor can fix it.
6. As a student, I want to ask the AI to explain a slide in simpler words, using only that slide's content, so that I can understand it on my own.
7. As a student, I want to be told when an explanation is AI-generated so that I know to double-check it.
8. As a student, I want to be notified when a deck I'm following is updated so that I don't study outdated material.
9. As a student, I want to download the final edited deck so that I can study offline.
10. As a student, I want to mark slides as "review later" so that I can prepare for the quiz.
11. As a student, I want the shared deck to load with clear messages if the link has expired or the instructor made it private so that I know what happened.
  

### User 2: instructor
1. As an instructor, I want to add a blank title or text slide anywhere in a generated deck so that I can add an intro, agenda, or transition I never said
 aloud.
2. As an instructor, I want to upload my own image onto a slide so that I'm not limited to the images the app picked.
3. As an instructor, I want to search for a replacement image from inside the editor so that I can swap out one that doesn't fit.
4. As an instructor, I want to drag, resize, and delete images and text boxes on a slide so that I can fix the layout myself.
5. As an instructor, I want to duplicate, reorder, and delete slides so that the deck follows the order I want to teach in.
6. As an instructor, I want to undo and redo my edits so that I can experiment without fear of breaking the deck.
  
7. As an instructor, I want to select text on a slide and ask the AI to rewrite it with an instruction like "shorter" or "more formal" so that I control the
change.
8. As an instructor, I want to see the AI's suggestion next to the original and accept or reject it so that the AI never overwrites my work without my say-so.
9. As an instructor, I want to choose a tone for AI rewrites, such as conversational, academic, or plain, so that the spoken narration doesn't sound robotic.
10. As an instructor, I want the AI to rewrite only the slide text and not the narration, or the other way around, so that I don't lose one when I fix the
other.
11. As an instructor, I want to ask the AI to generate a new slide from a short prompt so that I can fill a gap in the lecture.
12. As an instructor, I want to apply one AI instruction to the whole deck, such as "simplify the wording", and review every change before saving so that I
can edit in bulk.
13. As an instructor, I want an AI-generated summary or key-takeaways slide at the end of the deck so that I can close the lecture quickly.

### User 3: non-academic presentor
1. As a presenter, I want to start from a blank deck with no learning objectives or quiz so that the app fits a talk that isn't a class.
2. As a presenter, I want to add a title, agenda, or section-divider slide after speaking so that the deck looks finished.
3. As a presenter, I want to upload my logo and brand images and place them on any slide so that the deck matches my company.
4. As a presenter, I want to ask the AI to rewrite a slide for a specific audience, such as executives, customers, or a general crowd, so that I can reuse one
 talk.
5. As a presenter, I want to ask the AI to make a slide punchier or shorter so that it works on screen.
6. As a presenter, I want to lock a slide so that AI edits and bulk changes never touch it.
7. As a presenter, I want to save my favorite AI instructions as one-click presets so that I don't retype them.
8. As a presenter, I want to combine slides from several talks into one deck so that I can build a new presentation.
9. As a presenter, I want to set an AI tone once and have it apply to everything so that the deck stays consistent.
10. As a presenter, I want to export the edited deck to PowerPoint or Google Slides with my changes intact so that I can present anywhere.
11. As a presenter, I want to be warned before I export or share if the AI added text I haven't reviewed so that I don't share a mistake.
  


## Activity Diagrams

Student: As a student, I want to add private notes to a slide so that I can study from one place.
<img width="2514" height="5656" alt="Student1UML" src="https://github.com/user-attachments/assets/71fafa02-e40d-4266-a3d2-14a8ade02387" />

Student: As a student, I want to see which slides were edited after the lecture so that I know how the deck differs from what I heard.
<img width="2749" height="3456" alt="Student2UMLNEW" src="https://github.com/user-attachments/assets/19aa2380-c13c-4430-953e-d255397120c1" />


Instructor: As an instructor, I want to drag, resize, and delete images and text boxes on a slide so that I can fix the layout myself.
<img width="3647" height="4192" alt="Instructor1UML" src="https://github.com/user-attachments/assets/9a725d13-2571-401e-8395-b85b2e9a1292" />

Instructor: As an instructor, I want to duplicate, reorder, and delete slides so that the deck follows the order I want to teach in.
<img width="2556" height="4272" alt="Instructor2UML" src="https://github.com/user-attachments/assets/84bd4905-1a5b-43e7-8d13-2e1394c56b19" />

Presenter: As a presenter, I want to save my favorite AI instructions as one-click presets so that I don't retype them.
<img width="2660" height="3722" alt="Presenter1UML" src="https://github.com/user-attachments/assets/82594cd7-f664-443a-a983-5ca75fbf9d7a" />

Presenter: As a presenter, I want to set an AI tone once and have it apply to everything so that the deck stays consistent.
<img width="2564" height="4016" alt="Presenter2UML" src="https://github.com/user-attachments/assets/49c188b6-787d-4619-aa2c-d70317f1bffc" />


## Wireframes

All screens are black-and-white wireframes. Elements marked **ADDED** are new; **MOVED** marks something relocated from where it lives in the current app. Everything unmarked matches the existing app.

### 00 Home — existing screen, unchanged (Instructor, Presenter)
![Home](wireframes/00%20Home.png)
Included as the prototype's entry point: open a lecture card to reach the Slide Editor. Nothing on this screen is added, moved, or renamed.

### 01 Slide Editor — changed screen (Instructor, Presenter)
![Slide Editor](wireframes/01%20Slider%20Editor.png)
ADDED: the existing floating tool strip (Pen, Highlight, Eraser, New whiteboard slide) gains Select, Text, Image, Shape, and AI tools. Selecting an element shows resize handles and a Replace / Crop / Delete bar. Undo / Redo in the top bar. A "[N] comments" button on the slide opens the Comments panel (01b). Nothing existing was moved or renamed.

### 01b Slide Editor – Comments — changed screen (Instructor, Presenter)
![Slide Editor – Comments](wireframes/01b%20Slider%20Editor%20%28comments%29.png)
ADDED: numbered markers show what each viewer comment refers to. Comments panel: reply, resolve / reopen, filter by this slide or all slides, and "Fix with Refine", which opens Refine with AI with the comment as the instruction. Toggle to turn viewer comments off. Comments are visible only to the deck's author.

### 02 Refine with AI — changed screen (Instructor, Presenter)
![Refine with AI](wireframes/02%20Refine%20with%20AI%20Panel.png)
Opens from the new AI tool or the existing ⋮ → "Refine this slide with AI". MOVED: from a pop-up to a side panel, so the slide stays visible and you can refine in several rounds. CHANGED: today Refine applies instantly; now it shows an Original vs. Suggestion preview, and nothing changes until you Accept. ADDED: typed instructions, tone, quick prompts and saved presets, an "AI-generated" label, and a count of AI edits left (AI use is metered and capped). The existing options and "How much" slider are kept as-is.

### 03 Deck Viewer — changed screen (Student, any viewer)
![Deck Viewer](wireframes/03%20Slide%20Viewer.png)
The deck as any non-author sees it. ADDED: "updated after the lecture" banner, EDITED tags and change notes on edited slides, As lectured / Final edited toggle, Previous / Next edited buttons, and a Slide tools panel: private notes, review later, AI "explain simply" (labeled AI-generated), comments to the author (optional "might be an error" tick, author replies, resolved status), and download. Comments are visible only to the deck's author. Existing: Play deck aloud, votes, view toggle, Translate, Share — unchanged.

### 04 Image Panel — new screen (Instructor, Presenter)
![Image Panel](wireframes/04%20Insert%20Image%20Panel%20Wireframe.png)
Opens from the new Image tool, or from "Replace" on a selected image. ADDED: upload by drag-and-drop or Browse, search for a replacement image, or pick from saved brand images. Option to place an image (e.g. a logo) on every slide.

## Clickable Prototype

**[Open the clickable prototype](https://www.figma.com/proto/wN8f3Z96Bm90tcNwvKGsOt/Slide-Machine-%E2%80%93-Wireframes?page-id=0%3A1&node-id=26-882&p=f&viewport=3891%2C3568%2C1&t=HhLdKv9NLTeLmIsc-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=26%3A882)** — no login required.

**Start:** the Home screen. **Tip:** click any empty spot to see what's clickable.

**1-minute walkthrough of the core idea:**
1. **Home** → click any lecture in **Discover** → the **Deck Viewer** (what a student or any viewer sees: edited-slide markers, notes, AI "explain simply", comments).
2. Write a comment → **Post** → switch to the **author's view**: the Comments panel.
3. **Fix with Refine** → **Refine with AI**: the AI suggests a change next to the original, and nothing changes until you **Accept**.
4. **Accept** → back to the **Slide Editor** with its expanded tool strip.
5. **Image** tool → **Image Panel** → **Replace image** → back to the editor.
6. Click the **logo** (top left) on any screen to return **Home**.
   
## Stakeholder Demo

See instructions. Delete this line and place a link to the deck The Slide Machine generated during your presentation here, after you have presented.

## Exit Ticket

See instructions. Delete this line and place a link to the exit-ticket quiz you generated from your demo deck and distributed to the class, along with a short note on what — if anything — you had to correct in the generated questions before publishing.
