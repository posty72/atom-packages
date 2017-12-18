# Atom packages
Atom packages

## Requirements
- Atom
- APM (Atom Package Manager)

## Installation
Run the command below to download and install all the packages: 

```sh
curl https://raw.githubusercontent.com/posty72/atom-packages/master/packages.txt | xargs apm install
```

Note: this won't work on Windows unless you're one of those fancy people running Windows subsystem for linux

## Updating 

Update the package file with:
```sh
apm list --installed --bare < packages.txt
```


## Next step

Set this to run whenever Atom launches, closes, or a certain amount of time has passed.
