# state0 - TODOs and Design

- state0 and state0_template will be either 2 repos or 2 branches in this repo TODECIDE
- packages will be in a separate text file with packages - ideally it whould be just a bash array
with bash array syntax also visible in the file itself, the file would just be sourced in the package_install.sh
script.
- packages needed by state0 itself will be in the packages_install.sh file
- I will try to separate files from state0 itself and stuff added by the user to the separate files, so that
rebasing is safer
- each user will fork dotfiles and state0 repo and stack his personal commits on top of the state0 repo & regularly rebase
- consider adding custom naming scheme for the state0 file itself, so that they are clearly distinguishable from the rest of
the files in the repo. Maybe even consider making the state0 files readonly if the repo is not the state0-base repo, so that
I will be forced to add my personal changes into separate files.
- consider mechanism that will warn if I modify state0 file in state0_fork repo
- consider making state0_template, state0, and state0_fork all just branches on the same repo in my default GitHub account

state0_template -> state0 -> state0_fork


TODO - consider moving this repo to my regular github?
