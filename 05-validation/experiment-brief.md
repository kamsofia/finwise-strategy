[experiment-brief.md](https://github.com/user-attachments/files/34104543/experiment-brief.md)[Upl
# The Validation · FinWise

> Module 5 · Experimentation Methods. The experiment brief that tests the bet.

## Method

**Method:** Multi-Armed Bandit

**Why:** Multi-armed bandit fits because I am comparing three versions of the share step (control, share with accountant, invite co-owner), and each trial user is scarce: only about 2% convert, so sending half of them to a losing variant for weeks is an avoidable cost. A bandit shifts traffic toward the better arm as invite data comes in and keeps testing the weaker ones at a reduced rate. The trade-off is precision: allocation is uneven, so the conversion estimate is less clean than an A/B test. I keep a control arm and confirm the winner on conversion afterwards.

_____

## Hypothesis + primary metric

If we add an optional share step after the Aha screen for FinWise trial users and let MAB shift traffic to the best-performing version, we expect more users to invite an accountant or co-owner, as measured by 7-day invite rate.

**Primary metric:** % of trial users who send an invite within 7 days of reaching Aha, target: A winning arm beats control by at least 5 percentage points on 7-day invite rate with 95% probability, and its trial-to-paid is not below control

_Experiment: Post-Aha Share Step Optimization Test, Get more trial users to bring in a second person (accountant or co-owner) right after their first cash picture, so more of them reach the North Star's import-to-output step and convert to paid (baseline about 2%)._

_Testing Two versions of one optional share step shown after the Aha screen, tested against a control that sees no step: "Send this cash picture to your accountant" and "Invite a co-owner or teammate". Both are skippable. on New reverse-trial users who connect a bank account and reach the Aha screen in their first session.. Current experience: Four-screen onboarding: Goal, Connect, Aha (own cash position and runway, fix one transaction), Habit (weekly summary). No prompt to bring in an accountant or co-owner, so every user sees the same flow after Aha.._

_Predicted outcome: Traffic shifts to one share-step version within the first two weeks, and that version beats control by at least 5 percentage points on 7-day invite rate (95% probability), with Aha rate flat and its trial-to-paid not below control.. If successful: Lock in the winning version, then confirm it against control in a standard A/B test on trial-to-paid (target +0.5 pp from about 2%). After shipping, keep a 5% holdout to check 12-month retention (baseline about 40%). Then test new variables such as timing and who gets invited.. If unsuccessful: If invites stay low in every arm, the prompt is the problem: rework placement and copy, then rerun. If invites are high but conversion is flat, collaboration isn't the lever, which fits M1's flat 2% conversion. Drop it and test the trial-to-paid step itself, where 98% of trials are lost.._

_____

## Guardrail + read date

- **Guardrail:** Aha rate (bank connected and cash position seen in session one) must not fall by more than 5% relative to control
- **Read date:** 14 days after launch, no earlier (e.g. launch Mon Nov 2, read Mon Nov 16). Two full weekly cycles, and every user in the window has had their 7 days.

_____
oading experiment-brief.md…]()
