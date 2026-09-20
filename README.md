# Issues Game 🎮

A GitHub-based three-stage event game.

## How it works

1. **Game 1 — The Broken README**: start with Issue #4.
2. **Game 2 — GitHub Detective**: after Game 1 is verified, continue to Issue #5 and investigate the repository history.
3. **Game 3 — Race Against the Commit**: after Game 2 is verified, continue to Issue #6. The organizer releases the final clue when the final round begins; solve it, create `final-answer.txt`, and submit the commit link.

## Participant format

Use the same GitHub account throughout the event.

When submitting an answer, comment:

```
/answer YOUR_ANSWER
```

For Game 3, also include:

```
Commit: YOUR_COMMIT_LINK
```

The event bot checks the answer and records your progress through issue comments. Direct access to a later issue does not bypass the progression check.

> Organizers should configure the three answer secrets in the repository before the event:
> `GAME1_ANSWER`, `GAME2_ANSWER`, and `GAME3_ANSWER`.
