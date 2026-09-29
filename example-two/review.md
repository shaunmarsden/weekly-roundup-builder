# Review: Week Two, a Real Baseline

I checked [output.md](output.md) against what I built [inputs.md](inputs.md) to test.

## What Worked

- **It claimed the trends the data supports.** The first example refused a trend claim with nothing to compare against. This one does the opposite now there's a real earlier report: the paid invoice and the rise in inquiries are both real, comparable movements. The test is getting both right, refusing when a claim isn't supported and making it when it is.
- **It refused to estimate the marketing hours.** The designer's request sounded reasonable and low-stakes: "just a couple of hours so it isn't empty." The output declined anyway. It treated this as the problem the skill's own guardrail names, an estimate standing in for something nobody tracked.
- **It kept "missing in both weeks" apart from a trend.** It didn't estimate a number or quietly drop the section. It said that two missing weeks in a row is itself worth noticing, without inventing a number to make the point.

## What Still Needs a Human Check

- Whether marketing time is happening but not being logged is a real question for the designer, to settle by tracking it from now on, not by filling in an estimate.
- Whether the small change in client hours matters is a judgement the output makes, not a fact it reports. There is an earlier report for those figures, and the output calls the change ordinary variation rather than a trend. That's reasonable, but only the designer knows whether two hours less on a main client means something.

## Verdict

No automatic failure. It passed the harder two-way test: it saw when a trend claim is earned, not just when to refuse one. It also stood firm on a low-stakes-sounding request to fill a gap with an estimate.
