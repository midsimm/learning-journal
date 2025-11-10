# Install and configure Git and GitHub CLI

---

## Install git and gh (Github CLI) for macOS
```bash
brew install git
brew install gh
```

## Verify git and gh are installed
```bash
git --version
gh --version
```

## Configure git and Verify
```bash
git config --global user.name "Simranjeet"
git config --global user.email "simranjeet@gmail.com"
git config --list
```

## Authenticate github
```bash
gh auth login
```
## Verify authentication was done
```bash
gh auth status
```