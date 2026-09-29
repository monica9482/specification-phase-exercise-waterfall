# Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. In this exercise, your team specifies a set of improvements and new features for [The Slide Machine](https://theslidemachine.com) — see the [instructions](instructions.md) for detail, and the [background](background.md) for an introduction to the software product you are tasked with extending.

## Team members
Monica Lee  https://github.com/monica9482  
Yusef Moustafa  https://github.com/YusefMoustafa  
Leslie Sampaney  https://github.com/Leslie-Sampaney  
Krishiv Seth  https://github.com/machinelearner49  
Veer Singh  https://github.com/sing1179  

## Review of the Current Application
Strengths:  
- Mostly accurate transcriptions of speech onto slides  
- Navigation cue words to go forward and back a slide  
- Verbally add a picture to a given slide  
- Filler words or stutters ignored for non-strong speakers  
- AI accurately predicts and completes sentences most of the time
- Acronyms like SDLC and CI/CD came out spelled correctly, and a long stretch about waterfall versus agile became a clean two column comparison slide
- Before a quiz is published, a review screen lets the instructor edit every question and set points for each one
- Quiz settings let the instructor choose the number of questions, the question types, and add extra instructions for the AI

Weaknesses:  
- Image resource pool/must be seeded pre-lecture  
- Design template importing is not the best  
- New slide predictor doesn't allow for gaps/pauses for non-strong speakers
- Saying "next slide" mid lecture added a blank slide (slide 10) with no title or text that stayed in the finished deck
- Maintenance was said out loud but appears on none of the 12 slides, and the summary slide says six phases while the phase list slides only show five
- AI freedom defaults to 2 out of 5, so slides can include content the instructor did not say, and quizzes are written from the slide text by default with the spoken transcript as an unchecked box
- Opening a quiz link with a personal Gmail account showed "You need access" with no explanation    

Gaps:  
- Real-time verbal correction  
- Editing/approving material during the lecture  
- Unable to verbally insert diagrams/charts/graphs  
- Unable to verbally link words   
- Unable to add videos
- Signed out, the lecture page shows only the slides, a play button, and language and share icons, with no place to ask about a slide, no definitions of terms, and no mention that a quiz exists
- Quiz settings never say which accounts can open the quiz, and nothing warns the instructor before publishing
- After publishing, the Quiz tab shows only a Google Forms link, a copy button, and Delete quiz, with no open or close time and no way for students to reach it

## Prior Art & Originality

See instructions. Delete this line and replace with a short statement of what your team checked (the project's Future Work and Open Questions, its roadmap, and its open issues and pull requests) and which parts of your proposal are original — new work not already specified, scheduled, or proposed by someone else.

## Stakeholders

Students:  
**Student A — Student participant**  
Background: Student; Senior and Business.  
Interview method: Interview about study habits and proposed features, followed by app-use tasks directly observed by a team member.  
Goals and needs:  
- Understand lecture material using slides and professor-provided notes.
- Find explanations of unfamiliar terminology.
- Revisit prerequisite concepts through textbook material.
- Obtain clarification from professors, friends, office hours, or an LLM.
- Know whether an answer has been reviewed by an instructor before relying on it.

Problems and concerns:  
- Described encountering confusing slides and seeking clarification through LLMs.
- Needs to consult additional sources when terminology or prerequisite concepts are unfamiliar.
- Would not trust a classmate’s answer before professor review.
- Checks suspected errors with the professor.
- Would be uncomfortable with instructors seeing that they sought help from outside sources.

Observed app use and participant comments:  
- Selected a lecture because it seemed interesting.
- Used Google to investigate unfamiliar terminology and found sufficient, useful information.
- Reported successfully returning to an earlier explanation using memory.
- Said that a clarification request should include surrounding context and relevant material.

Reactions to proposed features:  
- Responded positively to an embedded glossary, particularly explanations that break down complex topics.
- Identified professor review as a condition for trusting peer answers in a slide-specific Q&A feature.  

Limitations:  
- The concept-understanding task was skipped.
- No direct observation record was supplied; the experiences above are participant-reported.
- Successful Google use does not establish that external lookup is a problem.
- The participant did not test a glossary or Q&A prototype.
- Discomfort with disclosure of outside help does not establish their preference about aggregate in-app statistics.
  
**Student B — Student participant**  
Background: Student; Grad level and Industrial Engineering.  
Interview method: Interview about study habits and proposed features, followed by app-use tasks directly observed by a team member.  
Goals and needs:  
- Study using lecture slides and past exam papers.
- Obtain clarification through office hours or a teaching assistant.
- Understand unfamiliar terms and prerequisite concepts using Google or an LLM.
- Locate earlier explanations when revisiting lecture material.
- Distinguish instructor-reviewed answers from unchecked peer responses.  

Problems and concerns:  
- Described seeking help when lecture slides are confusing.
- Needs additional explanations for unfamiliar terminology and prerequisite concepts.
- Reported difficulty finding an earlier explanation in the deck.
- Would not trust a classmate’s answer before professor review.
- Would be uncomfortable with instructors seeing that they sought help from outside sources.  

Observed app use and participant comments:  
- Selected the first lecture they could find.
- Used an LLM to investigate unfamiliar terminology and found it useful.
- Reported not knowing where to find an earlier explanation.
- Said that a clarification request should include surrounding context, relevant material, and their current understanding.
- Described explaining a concept in simple words as a personal check of understanding; this ability was not demonstrated during the recorded tasks.  

Reactions to proposed features:  
- Responded enthusiastically to the embedded glossary idea.
- Initially suggested that an answer remaining online indicated trustworthiness, but clarified that professor review would be necessary before trusting a classmate’s answer.  

Limitations:  
- The concept-understanding task was skipped.
- No direct observation record was supplied; the experiences above are participant-reported.
- The specific navigation steps that led to difficulty were not recorded.
- Positive reactions to the glossary do not demonstrate its effectiveness; no prototype was tested.
- Their preference concerning aggregate in-app statistics remains unknown.

## Product Vision Statement

See instructions. Delete this line and place your Product Vision Statement here — one sentence describing the improvements and new features your team is proposing for The Slide Machine.

## User Requirements

See instructions. Delete this line and place a list of your User Stories here, grouped by type of user. These should describe functionality that is new or changed, not functionality the app already has.

## Activity Diagrams

See instructions. Delete this line and place images of your UML Activity diagrams here, each with the text of the user story it illustrates.

## Wireframes

See instructions. Delete this line and place your wireframe diagrams here, covering every new screen and every existing screen your proposal changes, for every type of user.

## Clickable Prototype

See instructions. Delete this line and place a publicly-accessible link to your clickable prototype here.

## Stakeholder Demo

See instructions. Delete this line and place a link to the deck The Slide Machine generated during your presentation here, after you have presented.

## Exit Ticket

See instructions. Delete this line and place a link to the exit-ticket quiz you generated from your demo deck and distributed to the class, along with a short note on what — if anything — you had to correct in the generated questions before publishing.
