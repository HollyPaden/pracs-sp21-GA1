# Git commands

`git config`

Used for configuring git the *first time* it is used by a **specific** user on a **new** computer

### Subcommands

```

--global user.name "xxxxx xxxxx"

--global core.editor xxxxxx

--global color.u: true

--list

```

---

`git help`

Overview of *common* git commands

`man git`

Print git manual

`git init`

Initialize **empty** git repository

`git status`

Check repository status

`git add`

Track changes of a file

### Subcommands

- `.`

    Add to current directory

- `--all`

    Add all files in the repository directory

---


`git commit`

Commit changes

###Subcommand

`-m`

**Adding a message is very important**

*Note: using `-m` and not including a message will open a default text editor*

`git log`

View respository history

*Note: assigns checksum*

`git diff`

See **all* changes since last commit

`git rm`

**Remove** files from git repository

`git mv`

**Move** files in git repository

`git add filename.xyz` --> `git commit --amend``

**Amend** previous commit.

*Note: results in one commit instead of two*

## Git Workflow

1. New project `git init`

2. Change files

3. See changes `git status`

4. Select files for snapshot `git add`

5. Create snapshot `git commit -m "message"`

6. Repeat
