# See changes at different points in the story.
- git show hash-value
# Color only the modifications
- git show hash-value --color-words
# See only specific modifications with show.
- git show hash-value -- src/views/*
# ignoring unwanted files or directories.
- Using vim, create .gitignore and type the name of the file to be ignored.
- git rm -r --cached 
- git add .
- git commit -m "ignoring files"
