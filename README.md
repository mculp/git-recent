# git-recent

Interactively switch to recently updated Git branches.

## Features
- Sorts branches by last commit time
- Interactive selection via `fzf`
- Commit preview pane
- Supports limits and search queries

## Installation

### Homebrew
```sh
brew install mculp/tap/git-recent
```

### Manual
```sh
cp bin/git-recent /usr/local/bin
```

### Usage
```sh
git recent
git recent 10
git recent 20 feature
```

## Requirements
- `fzf`
