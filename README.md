# Практическая работа №1. «Делимся проектом с миром»

## Part 1. Terminal

### 1. Main commands<b>
**cd** (**c**hange **d**irectory) - to get to the directory where you going to work <b>
	cd Downloads/PhD - you will get to subfolder PhD in folder Downloads <b>
**git init** - to initialize git repository in current folder<b>
**rm -rf .git** - to delete .git if you have some troubles<b>
**git status** - to check status<b>

### 2. Add files to repository<b>
**git add --all**, **git add .** - to start tracking files<b>
**git commit**<b>
**git commit -m "Text"** - to save changes<b>
**git log** - to see history logs<b>
	
### 3. SSH keys generating <b>
**ls -la .ssh** - to check existing keys<b>
**ssh-keygen -t ed25519 -C "электронная почта, к которой привязан ваш аккаунт на GitHub"** - to create new keys<b>
**pbcopy < ~/.ssh/id_rsa.pub** - to copy key to clipboard

## Part 2. GitHub.com

### 1. SSH key linking<b>
**Settings -> SSH and GPG keys -> New SSH key -> Add SSH key** - workflow to add key<b>
**ssh -T git@github.com ** - to check status<b>
### 2. Connecting
**git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git ** - to linking local and remote repositories <b>
**git remote -v** - to check it<b>
### 3. Pull/Push
**git push -u origin main** - to pushing for the first time
**git push** - to push data to repository
**git pull** - to pull data from repository



**Just for case:**
```mkdir my_project
cd my_project
git init
```

[Гит](https://www.github.com "GitHub")