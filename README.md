# RC Modules

Use this tool to keep your root RC file (`.bashrc` etc.) cleaner.
For example, you may have a collection of aliases and bash functions related to only `git`, 
so you can create a `git_profile.sh` file and use this tool to source it.

## Get Started

Add files to the directory `.rc_modules/profiles` with the naming convention
`{name}_profile.sh`. Then, to source these files all at once via sourcing the `rcmod` file:

```bash
source path/to/rcmod
```

Add the line above to your root RC file (`.bashrc` etc.).

Once you have profiles, the output will look something like this:

```
Sourcing environment profiles
-----------------------------
docker         ✅
git            ✅
python         ✅
-----------------------------
```
