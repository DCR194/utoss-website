---
title: 'Software Onboarding'
description: 'Here is a sample of some basic Markdown syntax that can be used when writing Markdown content in Astro.'
pubDate: 'Oct 9 2025'
heroImage: '../../assets/blog-placeholder-about.jpg'
---


## Quick Links
- [Contributing To Firefox Quick Guide](https://firefox-source-docs.mozilla.org/setup/index.html)
- [Bugzilla](https://bugzilla.mozilla.org/home)
- [GitHub Forking Guide](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)
- [Developing Firefox with ClangD](https://botondballo.wordpress.com/2019/12/02/developing-mozilla-c-code-with-clangd-and-vscode/)

>**NOTE:** This onboarding guide is subject to change as the current content may be incomplete.
Reach out on discord if you find any issue or if something is unclear.


## Clone the Firefox Repo
### Windows Commands
```Bash
cd c:/
mkdir mozilla-source
cd mozilla-source
wget https://raw.githubusercontent.com/mozilla-firefox/firefox/refs/heads/main/python/mozboot/bin/bootstrap.py

python3 bootstrap.py
```

### Linux/MacOS Commands
```Bash
curl -L https://raw.githubusercontent.com/mozilla-firefox/firefox/refs/heads/main/python/mozboot/bin/bootstrap.py -O

# Select 2 to develop firefox for desktop
python3 bootstrap.py
```

### Other Useful Commands
```Bash
# Setup your vscode ide (also supports (Neo)Vim, Emacs, Eclipse)
./mach ide vscode
# Build your firefox
./mach build
```

## Getting started with Git
### Setup Your Workspace
```Bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

