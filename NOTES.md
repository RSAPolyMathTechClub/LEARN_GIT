# NOTES

- Notes

## SETUP

```bash

git config --global user.email "you@example.com"
git config --global user.name "Your Name"

```

## CHECK SETUP

```bash

git config --list

```

- OR

```bash

git config user.name
git config user.email

```

## CREATE YOUR FIRST REPOSITORY

```txt

1. Using the graphic interface on the github website, create your first repository.
OR
2.1 (No readme)
2.2 (With readme)

```

- create a new repository on the command line

```bash

echo "# my_first_repository" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/RSAPolyMathTechClub/my_first_repository.git
git push -u origin main

```

- TO PUSH TO MAIN YOU MAY USE : git push
- TO PUSH TO BRANCH YOU MAY USE :  {TODO}

## CLONE

```bash

git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/my_first_repository.git

```

- e.g

```bash

git clone https://{YOUR_PERSONAL_TOKEN}@github.com/RSAPolyMathTechClub/my_first_repository.git

```

## PUSH AN EXISTING REPOSITORY FROM THE COMMAND LINE

```bash

git remote add origin https://github.com/RSAPolyMathTechClub/my_first_repository.git
git branch -M main
git push -u origin main

```

## BRANCHES

- create branch

```bash

git checkout branch1
git checkout -b subbranch_of_b1 branch1

```

## REFERENCES

- Notes
