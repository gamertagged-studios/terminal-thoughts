# contributing to terminal_thoughts

## the idea

every shirt starts as a phrase. phrases come from developers — the things we say, think, or stare at for too long.

if you have a phrase that belongs on a terminal_thoughts shirt, submit it here. the PR is the vote. the community discusses in the comments. if it gets merged, it gets made.

---

## how to submit

1. fork this repo
2. create a new file: `phrases/community/your-phrase-name.yaml`
3. fill it out (see format below)
4. open a PR with the title: `phrase: your_phrase.md`
5. that's it — the conversation happens in the PR

---

## phrase format

```yaml
phrase: "the text that goes on the shirt"
filename: "your_phrase.md"        # what shows in the status bar
status: "* your status string"    # optional — right side of status bar
notes: "why this belongs"         # optional but appreciated
submitted_by: "@yourhandle"
```

---

## what makes a good phrase

- a developer says it or thinks it without prompting
- it works as a filename — underscores, `.md` extension
- there's a human truth inside the technical framing
- it hasn't been printed on a shirt before
- it stands alone with no explanation needed

**the test:** if the right person sees it on someone in a coffee shop and thinks "okay" — it works.

---

## what doesn't make it

- too general ("i love coffee and code")
- requires explanation ("it's funny because...")
- been done ("404 brain not found")
- not a genuine developer thought

---

## what happens after

open PRs are the backlog. when the submission window opens, the team reviews what's been submitted. approved phrases get designed and dropped in the next release. the wizard decides.

merged = it's getting made.
closed = not this time.

---

## status strings

the right side of the status bar is where the phrase lives mechanically. two formats:

- parenthetical: `(thinking...)` `(context limit reached)` `(awaiting feedback)`
- action: `* whirring....` `* probably just magic` `* summoning...`

if you're not sure, leave it blank. silence is a valid design choice.

---

*terminal_thoughts™ — Gamertagged Studios*
