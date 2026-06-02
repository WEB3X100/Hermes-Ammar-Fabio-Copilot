# 04 - Trade Journal Template

Copy this into `~/TradingCoachLogs/YYYY-MM-DD/trade-XX.md`.

## Trade Header

```text
Date:
Trade number:
Instrument: ES / NQ
Session time:
Setup type:
Direction: long / short
Regime at entry: balance / compression / expansion / trend / slow grind / unclear
Location grade: A / B / C / F
Model fit: correct / questionable / wrong
Entry price:
Stop price:
Target price:
Actual exit price:
Exit reason:
R result:
P&L:
Screenshot before: trade-XX-before.png
Screenshot after: trade-XX-after.png
```

## Pre-Entry Gate

```text
Valid location from premarket map: Y/N
5-minute footprint volume above 20K: Y/N
9:30 footprint above 10K if early-session: Y/N/N/A
15+ points to next zone: Y/N
Right model for current regime: Y/N
Who is trapped:
Who is being rewarded:
Expected speed:
Setup type named before entry: Y/N
Screenshot captured before entry: Y/N
Trading before 11:30 AM: Y/N
Daily loss rule still safe: Y/N
```

## Order-Flow Read

```text
Total volume:
Delta:
Delta %:
Delta NT:
Total Effort:
Delta Effort:
Profile shape:
Delta interpretation: loud but ineffective / efficient and accepting / unclear
Price behavior: accepted / rejected / stalled / chopped
Regime: balance / compression / expansion / trend / slow grind / unclear
Cage status: inside / edge / clean break / failed break / accepted outside
Speed of tape: rising / falling / dead / not tracked
Who was trapped:
Who was rewarded:
Was aggression getting paid:
```

## Rationale

```text
What did I see?

Why was this location valid?

Why was this entry not a chase?

What would invalidate the trade?

Was this easy to explain before entry?

Was I early, on time, or late?

Would Fabio take this? Why or why not?

Would Carmine take this? Why or why not?
```

## Emotional State

```text
Emotion at entry: neutral / anxious / confident / frustrated / FOMO / revenge / bored
Emotion at exit: neutral / anxious / confident / frustrated / FOMO / revenge / bored
Body signal noticed:
Impulse noticed:
Did I obey the impulse or the rulebook?
```

## Mistake Taxonomy

Select any that apply:

- early entry
- chased
- ignored chop
- traded after rule limit
- bias trade
- failed to wait for Beta B
- faded continuation
- misread location
- volume threshold ignored
- confused absorption for continuation without location context
- no mistake / valid process trade

## Coach Notes

```text
Did this meet all gate criteria?
Did I follow the exit plan?
Time to first favorable movement:
Did this setup need to work fast:
Did I manage it according to that speed requirement:
Same-thesis loss count at entry:
Which style did I actually trade: CLC Selective / NQ Squeeze / Balance Edge Fade / Reload Continuation / Zero Print Magnet / No Trade
Would I take this exact trade again after review:
What was the one best thing I did?
What was the one thing to improve?
```

## Prompt D - Trade Autopsy

```text
Analyze this trade. Setup type: [X]. Regime: [X]. Location grade: [X]. Model fit: [correct/questionable/wrong]. Entry: [X]. Stop: [X]. Target: [X]. Actual exit: [X]. R result: [X]. What I saw: [describe delta, volume, profile, rejection/acceptance]. Who was trapped: [X]. Who was rewarded: [X]. Expected speed: [X]. Actual time to first favorable movement: [X]. My entry rationale: [X]. Emotion at entry: [X]. Rule I may have violated: [X]. Questions: Did my entry meet all gate criteria? Did I follow my exit plan? What mistake type is this? Was this a process win, process loss, valid loss, or rule break? If you were my trading coach, what would you tell me in 2 sentences?
```
