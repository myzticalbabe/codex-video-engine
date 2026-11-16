# STEM learning guide — codex-video-engine

CODEX Studio turns HTML and still images into video: it renders frames and encodes them to MP4. It is the most directly creative project in the set — the output is something you can watch.

This guide is for teachers, mentors, club leaders, parents and students who want to
use this repository as a vehicle for real STEM learning — in particular for girls and
other groups still under-represented in computing, engineering and mathematics. It
says what the project actually teaches, how to run a session with it, and what to
remove so that nobody is excluded by accident.

## What this project teaches

**Subject areas**

- media encoding
- rendering pipelines
- colour and frame rate
- graphics programming

**Skills practised**

- turning a design into a sequence of frames
- measuring output quality
- reasoning about size against quality
- debugging a pipeline that produces no error but wrong pixels

## Prerequisites

Python 3.13 and ffmpeg on the PATH. A pair can share one machine.

Nothing else is assumed for the entry-level activity below: no prior programming
experience, no particular hardware, and no home internet connection.

## Six practices this repository is set up to support

These follow the published guidance on gender-equitable STEM education — connect the
work to learners' lives, let them investigate real problems, treat struggle as part of
the work, name and challenge stereotypes, make the work collaborative, and put
learners in front of diverse role models.

1. **Connect it to their lives.** the same encoding decisions decide why one phone video is 40 MB and another is 400 MB — a question learners have already asked
2. **Let them investigate.** give the same 10-second clip three encode settings and ask which one a phone on a slow connection should receive
3. **Make struggle normal.** Build the session so that the first attempt is *expected*
   to fail. Say out loud that debugging is the subject, not a penalty. Ask "what did
   that error tell you?" before offering the answer.
4. **Challenge the stereotype.** Name who does this work and why it is not a gendered
   skill. Praise the method ("you isolated the variable"), not the person ("you're a
   natural") — the second kind of praise teaches learners that ability is fixed.
5. **Make it social.** one learner directs (decides the look), one operates (changes settings); they swap halfway
6. **Show diverse role models.** women in animation and VFX pipelines, and the engineers behind the video codecs inside every phone

## A 90-minute session

1. *(15 min)* Decode a 2-second clip into frames and count them.
2. *(25 min)* Re-encode at three quality settings and record size and visible artefacts.
3. *(35 min)* Build a 10-second title sequence from HTML.
4. *(15 min)* Screen everyone's clip; the group votes on the best size-to-quality trade.

## Vocabulary to define before the session

Specialist vocabulary is a hidden entry test if nobody explains it. Define each of
these the first time it appears, in one sentence, in the learners' own words:

1. **frame** — one still image in the sequence.
2. **codec** — the rule for compressing frames.
3. **bitrate** — how much data is spent per second.
4. **CRF** — a quality dial where lower usually means larger files.

## Accessibility

Read [ACCESSIBILITY.md](ACCESSIBILITY.md) before running a session. Two rules matter
most in a mixed-ability room:

- Every activity must be completable with a keyboard alone, with a visible focus ring.
- Every instruction names the control or the heading ("the **Run** button in the
  toolbar"), never a colour or a position.

Pair learners rather than singling anyone out, and always offer a text-only route for
a visual step.

## Contributing as a learner

Small, well-scoped contributions are the point, not a consolation prize:

- Browse issues labelled
  [`good first issue`](https://github.com/myzticalbabe/codex-video-engine/labels/good%20first%20issue).
- Read [CONTRIBUTING.md](CONTRIBUTING.md) — it has a section written for first-time
  contributors.
- Ask in [SUPPORT.md](SUPPORT.md) if anything is unclear. Asking is expected here; it
  is not a failure.

## Licence and classroom reuse

Classroom, club and workshop use is welcome. See `LICENSE` for the exact terms, and
check whether your institution requires a separate agreement before redistributing
modified copies.
