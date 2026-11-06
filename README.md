# Multiple-Choice Reading

Multiple-choice questions on passages, including choose TWO, where every wrong option is wrong for a reason.

Part of the [IELTS Study Suite](https://github.com/Apurba94/ielts-study-suite): 100 free study apps for IELTS. This one is for the IELTS Academic and General Training test. It works offline, as a Windows program or in the browser.

## Download and run

- **Windows:** download `Multiple-Choice Reading.exe` from the [latest release](https://github.com/Apurba94/ielts-reading-mcq/releases/latest) and open it. Nothing to install. It opens in its own window and saves your progress in your user folder.
- **Browser:** open it online in the suite's web edition at https://ielts-study-suite.vercel.app/apps/ielts-reading-mcq/ . Progress stays in that browser.
- **From source:** `python launcher.py` (Python 3.10 or later, no packages needed).

## What it does

Multiple-choice questions in IELTS Reading have three or four options, and the wrong ones are designed to tempt: they repeat words from the passage, overstate it, or are true but answer a different question. Practise with the multiple-choice questions on six passages, with True, False or Not Given statements to check close reading.

Sections: Passages, Traps, Progress, About.

## How to use it

1. Read the question stem first and find the part of the passage it refers to.
2. Read that part closely, then compare each option with it.
3. Learn the four common traps in **Traps**.

## Good to know

- All questions, passages, recordings and definitions were written for this suite. None are official IELTS questions. For official practice, use the materials on ielts.org and from the test partners.
- It follows IELTS as delivered on computer in 2026. Formats change, so check ielts.org before your test.
- Listening uses the voices installed on your computer, which sound less natural than real test recordings.
- Feedback on writing and speaking counts what a program can count honestly, such as length and linking words. It is not an IELTS band score. Band conversions for Listening and Reading are approximate.
- Not endorsed by or affiliated with the British Council, IDP or Cambridge University Press & Assessment. IELTS is a registered trademark of its owners.

## For developers

The app is plain HTML and JavaScript in `web/`, run by a small Python launcher that serves it on 127.0.0.1 only and needs a secret token for saving. Tests: `node --test "tests/*.test.js"` (29 tests) and `python -m unittest discover -s tests`. Build the .exe with `python build_exe.py`.

Built with AI assistance (Claude Code). MIT licence. By JANIN A APURBA.
