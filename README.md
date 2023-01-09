# Typescript template with jest configs for VS Code

## Getting started

Fork it!

Github does not allow forking repos you already own. See forking workarounds below.

## installation

`npm install`

## Fork with gh cli

This repo is a "template". It can be conveniently forked into a new repository using the github cli.

`gh repo create <NewForkName> --template OlleMattsson/ts-template`

Convenient flags

`gh repo create <NewForkName> --template OlleMattsson/ts-template --clone --private --include-all-branches`

## Fork manualluy
If the above method is unavailable, a fork can be manaually created.

1. Create a new repository (fork). Using web / gh cli is very convenient: `gh repo create`
2. Clone the newly created fork `git clone git@github.com:OlleMattsson/<ForkName>.git`
3. Add the original repo as a remote `git remote add upstream git clone git@github.com:OlleMattsson/ts-template-test.git`
4. Pull the original repo to your fork `git pull upstream master`
5. Push the new fork `git push origin master`

[Instruction source](https://deanmalone.net/post/how-to-fork-your-own-repo-on-github)
