# AIML Weekly Learning Tracks

This repo is the home of the AIML team's weekly learning program. Each week is broken into
**day-wise topics** split across **three tracks**. Every member picks **one track**, works through its
**checklist** day by day, and fills in the matching **day worksheet**. All three tracks are designed to
move members toward machine learning.

> **New here? Start with [Week 1](week-01/README.md).**

## Tracks at a glance

| Track | Name | Who it is for | Where it goes next |
|---|---|---|---|
| **A** | Python Basics | Members who know zero or minimal coding, or are brushing up foundations | Comfortable writing small Python programs, then move to Track B |
| **B** | Advanced Python | Members comfortable with basics (variables, functions, loops) who want to move toward Python libraries | OOP and advanced Python, then numpy / pandas / matplotlib, then move to Track C |
| **C** | ML Fundamentals | Members who already know some Python and want to start machine learning | numpy / pandas / matplotlib brush-up, then ML fundamentals, then supervised learning |

## Cadence

- **Week 1 is the exception: it runs Monday to Monday.** Day 1 is **Monday**, Day 7 is **Sunday**, and
  the final Monday is review.
- **From Week 2 onward, every week runs Wednesday to Monday.** Day 1 is **Wednesday**, and the week
  closes on the following **Monday**.
- In **every** week, the **final Monday is a review day**: catch up on anything missed and finish your
  worksheets. No new topics are introduced on that Monday.

## How a week is organised

```
.
├── README.md                       # this file: program overview, tracks, cadence
├── SUBMISSION.md                   # student walkthrough: fork -> checklist -> worksheet -> WhatsApp
└── week-01/                        # one folder per week
    ├── README.md                   # week goal, day-wise schedule, track selection, submission
    ├── track-a/                    # Python Basics
    │   ├── checklist.md            # day-wise topics + video timestamps + documentation links
    │   └── worksheet/
    │       ├── README.md           # how to use the day worksheets
    │       ├── day-1.md            # 2-3 questions for Day 1
    │       └── day-2.md ... day-7.md
    ├── track-b/                    # Advanced Python  (same layout)
    └── track-c/                    # ML Fundamentals (same layout)
```

Each day you do two things:

1. Work through that day's block in the track **`checklist.md`** (topics, video with timestamps).
2. Answer that day's questions in **`worksheet/day-N.md`**.

The **documentation links** you need for the whole week sit at the **end of the checklist**, after
Day 7.

## How to track your progress

> **Submitting your work?** The copy-paste walkthrough — fork → tick the checklist → fill the day's
> worksheet → post the link in the WhatsApp group — is in [`SUBMISSION.md`](SUBMISSION.md).

GitHub renders `- [ ]` checkboxes as **read-only** in file preview — you cannot click them in the web
UI. So each member tracks progress in **their own fork**:

1. **Fork this repo** to your own GitHub account using the *Fork* button, top right.
2. **Open your track's checklist** in **your fork**, for example `week-01/track-a/checklist.md`,
   not in the upstream repo.
3. **Click the pencil / Edit icon** (top-right of the file view) to open the editor.
4. **Flip each `- [ ]` to `- [x]`** for every item you complete, as you go.
5. **Commit the change** with the green *Commit changes* button, or use a branch and open a PR if your
   lead asks for one.
6. **Fill in that day's worksheet** (`worksheet/day-N.md`) the same way, then share a link to your
   filled-in worksheet in your team channel.

Because progress lives in your fork, you can never accidentally overwrite anyone else's work, and your
lead can review it by opening your fork.

## Ground rules

- **Work through one track.** Do not mix tracks in a single week.
- **Every day ends with a hands-on deliverable.** Reading and watching is not the work — running code is.
- **The final Monday introduces nothing new.** It is review, catch-up, and worksheet completion.
- **Record time honestly** in the worksheet. Confidence ratings of 1 to 5 are more useful to you in
  later weeks than perfect completion rates.

## Weeks

- [Week 1: 12 Oct to 19 Oct 2026](week-01/README.md) — Python Basics (A), Advanced Python (B), and ML
  Fundamentals (C). *(Week 1 runs Monday→Monday; **from Week 2 onward, weeks run Wednesday→Monday**.)*
