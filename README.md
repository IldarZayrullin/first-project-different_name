# Практическая работа №1. «Делимся проектом с миром»

## Part 1. Terminal

### 1. Main commands<br>
**cd** (**c**hange **d**irectory) - to get to the directory where you going to work <br>
	cd Downloads/PhD - you will get to subfolder PhD in folder Downloads <br>
**git init** - to initialize git repository in current folder<br>
**rm -rf .git** - to delete .git if you have some troubles<br>
**git status** - to check status<br>

### 2. Add files to repository<br>
**git add --all**, **git add .** - to start tracking files<br>
**git commit**<br>
**git commit -m "Text"** - to save changes<br>
**git log** - to see history logs<br>
	
### 3. SSH keys generating <br>
**ls -la .ssh** - to check existing keys<br>
**ssh-keygen -t ed25519 -C "электронная почта, к которой привязан ваш аккаунт на GitHub"** - to create new keys<br>
**pbcopy < ~/.ssh/id_rsa.pub** - to copy key to clipboard

## Part 2. GitHub.com

### 1. SSH key linking<br>
**Settings -> SSH and GPG keys -> New SSH key -> Add SSH key** - workflow to add key<br>
**ssh -T git@github.com** - to check status<br>
### 2. Connecting
**git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git** - to link local and remote repositories <br>
**git remote -v** - to check it<br>
### 3. Pull/Push
**git push -u origin main** - to pushing for the first time<br>
**git push** - to push data to repository<br>
**git pull** - to pull data from repository<br>



**Just for case:**
```mkdir my_project
cd my_project
git init
```

[Гит](https://www.github.com "GitHub")