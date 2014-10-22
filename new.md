# New

A commandline script to create new projects based on skeletons.

## Huh?

Say you want to create a new angular app. What do? You probably want to start
from some kind of skeleton.

## What does it look like?

`new angular <name>`: Start a new angular project based on [angular-seed][seed]. If
any options (grund or not), either expect them as arguments (`--grunt`) or
prompt for them during creation

## Implementation design

A script with stellar tab completion.

Curated files that define structure:

* What repo(s) to clone as a skeleton
* Any applicable options and commandline arguments


[seed]: https://github.com/angular/angular-seed
