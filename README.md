# Knowledge Base

A shared notebook that connects Aaron's Claude projects. Anything worth
remembering across projects (research, word meanings, ideas) goes here as a
plain text note, so every project can read the same notes and GitHub keeps a
full history of every change.

## How it is organized

```
knowledge-base/
├── README.md              ← you are here
├── templates/
│   └── note-template.md   ← copy this to start a new note
├── bible-research/        ← notes from the "Bible Thoughts" project
│   ├── names/             ← one note per name (people, cities, kings)
│   └── topics/            ← one note per theme or study
└── my-daily-conquest/     ← notes from the "My Daily Conquest" project
```

- **One folder per project or topic.** Add a new folder whenever a new project starts.
- **One note per subject.** For example `bible-research/names/jerusalem.md`.
- **File names:** lowercase, words joined with hyphens (`king-david.md`, not `King David.md`).
- **Notes are Markdown** (`.md`), which is plain text with a few symbols for headings and lists.

## Images and other files

Pictures, PDFs, maps and other non-text files live in a companion Google
Drive folder instead of here:

**Google Drive folder:** _(link to be added)_

Inside a note, link to a Drive file like this:

```
[Map of ancient Jerusalem](https://drive.google.com/...)
```

## Word meanings and Strong's numbers

For Hebrew and Greek word meanings, use
[Blue Letter Bible](https://www.blueletterbible.org) as the source and record
the Strong's number (for example H3389 for Jerusalem) with a link to its page.

## Adding a note

1. Copy `templates/note-template.md` into the right folder and rename it.
2. Fill in the sections. Leave out any that don't apply.
3. Save it. On GitHub that means "Commit changes". Or just ask Claude:
   "Add a note about Hebron to the knowledge base."

## Using this knowledge base in another Claude project

1. Open the project in Claude and go to **Project settings → Repositories**.
2. Add `every-place/knowledge-base`.
3. In that project, tell Claude something like: "Check the knowledge base for
   notes on this before researching, and save anything new you find there."

Claude can then read and add notes from any project, and everything stays in
one place.

## Privacy

This repository is **public**, so anyone can read these notes. If you'd like
to keep them private, change it on GitHub under
**Settings → General → Danger Zone → Change visibility**.
