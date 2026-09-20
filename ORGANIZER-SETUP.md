# Organizer setup

The game controller uses GitHub Actions repository secrets so participants cannot read the answer keys from the workflow.

Open:
Settings → Secrets and variables → Actions → New repository secret

Create these secrets:

- GAME1_ANSWER = 3
- GAME2_ANSWER = Set up Issues Game controller and documentation
- GAME3_ANSWER = the answer you decide for the final clue

## Important

Do not put the answer keys into public files or the README.

Game 3 is intentionally incomplete until the organizer releases final_clue.txt.

When Game 3 starts, create final_clue.txt with the clue, then later verify that participants create final-answer.txt in their contribution commit.

The workflow checks:
- /answer submissions
- sequential progression per GitHub username
- Game 3 commit URL
- presence of final-answer.txt in the linked Game 3 commit
