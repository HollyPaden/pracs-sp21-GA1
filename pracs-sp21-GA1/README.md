# Repository for git assignment

Made additions to GITCOM.md by copying and paraphrasing commands and purposes listed in CSB

Contents of repo are this file and a file of basic git commands

`touch File{1..25}_Treatment{A..D}.txt`

Used to create 100 text files in Data directory

`for oldname in *.txt; do newname=$(basename $oldname txt)csv; echo "Old name: $oldname"; echo -e "New name: $newname \n"; git mv "$oldname" "$newname"; done`

Used to rename files from .txt to .csv