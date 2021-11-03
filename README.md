## Create a folder

=> artistic-movement/

## Initialize project:

```bash
cd artistic-movement/

git init
```

## Clone project

```bash
git clone https://github.com/Ratsimandresy/Artistic.Movement.git
```

## enable push and pull to remote branch using personal access tokens

```bash
git remote set-url origin https://Ratsimandresy:personal_acces_tokens@github.com/Ratsimandresy/Artistic.Movement.git
```

## Install all dependencies

```bash
npm install
```

### To compile scss to css

```bash
npm run scss
```

#### To watch for changes

```bash
npm run scss-watch
```

### Running index.html on the browser via lite-server

```bash
npm start
```

---

---

Create a _.gitignore_ and _.env_ file at the root of the project under artistic-movement/

```zsh
touch .gitignore .env
```

Inside .gitignore file add:

```md
.env

node_modules
```

These gonna ignore node_modules and sensible environment variables when pushing

---

---

# git steps and commands

## Create your working branch

```bash
git branch name_of_your_branch
```

## Switching to your new working branch:

```bash
git checkout name_your_fo_branch
```

Enjoy and work in your new branch ;)

## After some doing modifications

- Adding the untracked filed (modified files) run :

```bash
git add -u

git status
```

NB: ****Don't use " _git add ._ ". Add only the modified files instead of everything****

- commit changes, run:

```bash
git commit -m "your commit message"

git status
```

- Go to your main branch and merge it with your branch to add the modifications on the master branch :

```bash
git checkout main

git merge name_of_your_branch
```

then check the status of the main branch :

```bash
git status
```

NB: ****before pushing changes, always PULL first****

- pull and push the changes and tadaaaaaa

- get back to your branch :

```bash
git checkout name_of_your_branch
```

And work on it again :)

#######