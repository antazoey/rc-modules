# RC Modules

Use this tool to keep your root RC file (`.bashrc` etc.) cleaner.
For example, you may have a collection of aliases and bash functions related to only `git`, 
so you can create a `git_profile.sh` file and use this tool to source it.

## Installation

Add the `rcmod` file in this repository somewhere in your path or execute it
using its relative path.

## Get Started

Add files to the directory `.rc_modules/profiles` with the naming convention
`{name}_profile.sh`. Then, to source these files all at once, run the command:

```bash
rcmod source-all
```

Add the line above to your root RC file (`.bashrc` etc.).
