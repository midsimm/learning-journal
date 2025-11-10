# Create a new project and make it a repo.

---

## Create a new project

```bash
mkdir my-app
cd my-app
echo ".env" >> .gitignore
```

## Initialize a local repo

```bash
git init
git add .
git commit -m "Initial commit."
```

## Create a remote repo

```bash
gh repo create my-app --public --source=. --remote=origin
```

## Push local repo to github

```bash
git branch -M main
git push -u origin main
```

## Verify repo is created

```bash
gh repo view --web
```