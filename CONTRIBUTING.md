# contributing.md

so you think you have something.

maybe you do. maybe you don't. the wizard will decide.
here's how to find out.

---

## what you're submitting

it's a terminal window. three fields.

```
┌─────────────────────────────────────────┐
│  ● ● ●                                  │
│                                         │
│         [the thing]                     │
│                                         │
├─────────────────────────────────────────┤
│ filepath.ext             * agent action │
└─────────────────────────────────────────┘
```

the thing can be anything that lives in a terminal. a phrase. a filepath. a command. a symbol. an error you've seen a hundred times and still haven't fixed. the wizard is not prescriptive about format. the wizard is prescriptive about whether it's good.

the filepath goes bottom left. the agent action goes bottom right. both are optional. silence is a valid design choice. not every terminal has a status string. not every thought needs one.

the wizard will know if you're forcing it.

---

## how to submit

1. fork this repo
2. add a file: `phrases/community/your-idea-name.yaml`
3. fill it out (format below)
4. open a PR titled `phrase: your_idea`
5. wait. the wizard is not on your schedule.

---

## the format

```yaml
content: "the thing that goes on the shirt"   # phrase / filepath / command / symbol / whatever
filepath: "your_file.md"                       # bottom left of the status bar
status: "* something..."                       # optional. bottom right. leave blank for silence.
notes: "why this belongs"                      # optional. won't hurt your odds.
submitted_by: "@yourhandle"
charity: "your chosen charity"                 # if merged, this is where the proceeds go
```

---

## the charity thing

if your design gets merged and made into a shirt, you pick a charity.
a portion of every sale of that shirt goes there. permanently. it's in the product description.
your name. your charity. every time someone buys it.

pick something real. the wizard will verify.

---

## what gets approved

a developer sees it and immediately feels something. no explanation needed. no setup. just recognition.

it works inside the terminal window frame. it belongs in a status bar.

it hasn't been printed on a shirt before. check before you submit.

**the test:** someone sees it on a stranger in a coffee shop and thinks "okay." that's it. that's the whole bar.

---

## what gets closed

```
* rejected: requires explanation.
* rejected: already been printed.
* rejected: not a genuine developer thought.
* rejected: "i love coffee and code" energy.
* rejected: the wizard said no.
```

the wizard does not elaborate. closed is closed.

---

## status strings

the right side of the status bar. two flavors:

- parenthetical: `(thinking...)` `(context limit reached)` `(awaiting feedback)` `(deprecated)`
- action: `* whirring....` `* probably just magic` `* summoning...`

not sure? leave it blank. silence is a valid design choice.

---

## when does the wizard review

when the window opens. watch [WIZARD.md](WIZARD.md).
your PR sits in the queue until then. that's fine. the wizard is patient.

---

*the wizard is watching.*
