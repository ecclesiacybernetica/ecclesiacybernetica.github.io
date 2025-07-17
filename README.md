# Readme

Jak to robimy na nowym komputerze.

1. przechodzę do folderu gdzie chcę mieć repository,
2. daje

```bash
git clone git@github.com:ecclesiacybernetica/ecclesiacybernetica.github.io.git
cd ecclesiacybernetica.github.io


```

wprowadzam zmiany, ale uwage, żeby nie usunąć np CNAME, bo nie będzie działać custom domain.

```bash
git add . 
git commit -m "update strony"
git push origin main
```

Przy następnym otwarciu rozpoczynam od pull.

```bash
git pull origin main  # Replace 'main' with your default branch if different

```


```bash
mkdir my-project
cd my-project
# Copy or create files here
git init
git add .
git commit -m "Initial commit"
git branch new-branch-name  # Optional, after the initial commit

```