# Organizer setup

The live event now uses **Issues #4, #5 and #6**. Issues #1, #2 and #3 are archived test issues and should not be used for the event.

The game controller uses GitHub Actions repository secrets so participants cannot read the answer keys from the workflow.

Open:
Settings → Secrets and variables → Actions → New repository secret

Create these secrets:

- GAME1_ANSWER = 3
- GAME2_ANSWER = Set up Issues Game controller and documentation
- GAME3_ANSWER = Git

## Live issues

- Game 1 → Issue #4
- Game 2 → Issue #5
- Game 3 → Issue #6

Participants should start at **Issue #4**. Even if someone opens #5 or #6 directly, the workflow rejects submissions until the previous game has been completed successfully.

## Game 3 release

Game 3 is intentionally incomplete until the organizer releases `final_clue.txt`.

When Game 3 starts, create `final_clue.txt` on the default branch with the final clue. Do not add the answer to the file.

The current test `final_clue.txt` has been removed, so the live repository is clean.

## Important

Do not put the answer keys into public files or the README.

The workflow checks:
- `/answer` submissions
- sequential progression per GitHub username
- Game 3 commit URL
- presence of `final-answer.txt` in the linked Game 3 commit

For the actual event, do not reuse the old test comments/issues.