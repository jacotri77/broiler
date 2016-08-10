# Broiler - Boilerplate installer

## Purpose
With all the different starter kits out there to start a project (such as react-redux-starter, etc), it becomes a bit of a pain to not only remember where these repos are when you need to start a new project, but also the steps required to get it up and running. Broiler is an attempt to make this a bit easier. You can save several different repos for several different starters (or boilerplates) and install them and have them ready to go with just a couple of keystrokes.

## Install
`npm install -g broiler`

## Usage
You can point to any git directory you'd like and ask broiler to bring it down and install it for you. It makes some modifications to the package.json file (such as the name and description of your application) but preserves the original data in the package.json under the 'boilerplate' key.

Install from a git repository:
`broiler install [path to git repo]`

You can also save repos under a more friendly alias to use again later. Doing so will create a `.broilrc` file in your home directory to store this info.

`broiler save [alias] [path to git repo]`

will allow this type of install:

`broiler install [alias]`