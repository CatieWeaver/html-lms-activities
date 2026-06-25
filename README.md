# Interactive HTML for Your LMS

A practical resource for instructional designers, instructional technologists, and the faculty they support — covering a repeatable workflow for creating interactive HTML learning activities that embed directly in a learning management system.

Live site: *(add your GitHub Pages URL here once deployed)*

---

## What this is

This site documents a methodology for using AI tools to generate interactive, accessible HTML learning activities that live inside an LMS document editor — no authoring tools, no plugins, and no external hosting required. Activities are generated from course-specific content and learning outcomes, then embedded directly in Blackboard Ultra (or any LMS that supports HTML input in its document editor).

The resource includes a library of live, working examples across seven interaction types, a prompt guide covering both brainstorming and prescriptive approaches, and implementation models for individual practitioners, ID teams, and institutional-scale adoption.

---

## Repository structure

```
index.html                        # Main landing page
activities/
  index.html                      # Activity library
prompts/
  getting-started.html            # Prompt guide
examples/
  psychology-flashcards.html
  chemical-physical-changes-sorting.html
  course-redesign-decision-tree.html
  behavior-function-assessment.html
  leadership-decision-tree.html
  lab-safety-checklist.html
  clinical-hand-hygiene-guide.html
  civil-rights-timeline.html
  startup-launch-plan-builder.html
  spot-grammar-errors.html
```

---

## Activity types included

| Type | Example |
|---|---|
| Flashcards | Psychology Flashcards |
| Sorting | Chemical vs. Physical Changes |
| Guided Practice | Significant Figures Guided Practice |
| Diagnostic Tool | Classroom Behavior Function Assessment |
| Branching Scenario | Leadership Case Study |
| Checklist | Lab Safety Checklist |
| Procedure Guide | Clinical Hand Hygiene Guide |
| Timeline | Civil Rights Movement Timeline |
| Planning Tool | Startup Launch Plan Builder |
| Error Identification | Spot the Grammar & Style Errors |

Each activity is a self-contained HTML file with no external dependencies. All files are designed to be adapted for any discipline using an AI tool and the prompt templates in the guide.

---

## How to use this resource

1. Visit the live site and interact with any activity in the library
2. Copy the page source (right-click → View Page Source)
3. Use a prompt from the Prompt Guide to adapt the activity for your course content
4. Paste the customized HTML into your LMS document editor

Detailed instructions, prompt templates, and LMS-specific troubleshooting are covered in the [Prompt Guide](prompts/getting-started.html).

---

## Technical notes

All activities are built with standard HTML, CSS, and JavaScript. No external libraries, frameworks, or dependencies are used. Activities are designed to embed in LMS document editors that support HTML input, including Blackboard Ultra.

Accessibility requirements — WCAG 2.1 AA color contrast, keyboard navigation, ARIA labels, and screen reader support — are built into the prompt templates rather than added as a revision step. As with any HTML content embedded in an LMS, accessibility tool coverage may vary by platform; alternative formats or pathways should be provided alongside interactive content where needed.

---

## Adding new activities

To add an activity to the library:

1. Place the HTML file in the `examples/` folder
2. Add a card for it in `activities/index.html` following the existing card structure
3. Update the activity count and type tags on `index.html` if needed

---

*Developed by Catie Weaver, Instructional Designer and Adjunct Faculty at Western Kentucky University.*
