# Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. In this exercise, your team specifies a set of improvements and new features for [The Slide Machine](https://theslidemachine.com) — see the [instructions](instructions.md) for detail, and the [background](background.md) for an introduction to the software product you are tasked with extending.

## Team members

### Team
#### Sanay Daptardar [sanay-d-nyu](https://github.com/sanay-d-nyu)
#### James Li [DyingRavioli](https://github.com/DyingRavioli)
#### Member 3
#### Member 4
## Review of the Current Application

See instructions. Delete this line and replace with your team's findings from using the live app at https://theslidemachine.com — at least 10 specific observations, each labeled as a strength, a weakness, or a gap, and drawn from more than one team member's use of the app.
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

See instructions. Delete this line and replace with a short statement of what your team checked (the project's Future Work and Open Questions, its roadmap, and its open issues and pull requests) and which parts of your proposal are original — new work not already specified, scheduled, or proposed by someone else.
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

See instructions. Delete this line and place your Product Vision Statement here — one sentence describing the improvements and new features your team is proposing for The Slide Machine.

We propose to add an editing toolbal for use after a lecture has already been generated, with an AI editing feature.

## User Requirements

See instructions. Delete this line and place a list of your User Stories here, grouped by type of user. These should describe functionality that is new or changed, not functionality the app already has.  
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
<img width="2749" height="3456" alt="Student2UML" src="https://github.com/user-attachments/assets/d6a5e7fb-e7f3-42bb-9e28-eee5597d506c" />

Instructor: As an instructor, I want to drag, resize, and delete images and text boxes on a slide so that I can fix the layout myself.
<img width="3647" height="4192" alt="Instructor1UML" src="https://github.com/user-attachments/assets/9a725d13-2571-401e-8395-b85b2e9a1292" />

Instructor: As an instructor, I want to duplicate, reorder, and delete slides so that the deck follows the order I want to teach in.
<img width="2556" height="4272" alt="Instructor2UML" src="https://github.com/user-attachments/assets/84bd4905-1a5b-43e7-8d13-2e1394c56b19" />

Presenter: As a presenter, I want to save my favorite AI instructions as one-click presets so that I don't retype them.
<img width="2660" height="3722" alt="Presenter1UML" src="https://github.com/user-attachments/assets/82594cd7-f664-443a-a983-5ca75fbf9d7a" />

Presenter: As a presenter, I want to set an AI tone once and have it apply to everything so that the deck stays consistent.
<img width="2564" height="4016" alt="Presenter2UML" src="https://github.com/user-attachments/assets/49c188b6-787d-4619-aa2c-d70317f1bffc" />


## Wireframes

See instructions. Delete this line and place your wireframe diagrams here, covering every new screen and every existing screen your proposal changes, for every type of user.

## Clickable Prototype

See instructions. Delete this line and place a publicly-accessible link to your clickable prototype here.

## Stakeholder Demo

See instructions. Delete this line and place a link to the deck The Slide Machine generated during your presentation here, after you have presented.

## Exit Ticket

See instructions. Delete this line and place a link to the exit-ticket quiz you generated from your demo deck and distributed to the class, along with a short note on what — if anything — you had to correct in the generated questions before publishing.
