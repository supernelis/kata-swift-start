# kata-swift-start

This repository is there to allow you starting a new code kata fast.

Requirements:

* swift

## Clone and work on branch

One posibility is to clone the repo and work on a branch. Creating a branch can be done with the following command.

```bash
git checkout -b <name of branch>
```

I would suggest to name the branch something like ```2019_10_11_numberToWordKata```

## Download as zip

Another possibility is to download this project as a zipfile, extract it in a directory with the name of the kata.

Don't forget to init the git repository:

```bash
git init
```

## Generate your own project instead of a download

In a new directory, run the following commands:

```bash
swift package init
swift package generate-xcodeproj
```
