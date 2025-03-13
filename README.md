# template
My template repo including some basic bash scripts for git handling.

*Write the README of this git repo here, above this line.*

--- --- --- --- --- --- --- --- --- ---
## `git` stuff

For a foolproof introduction to handling `git submodule`s, watch this youtube video: <https://www.youtube.com/watch?v=eJrh5IjWSGM> ("Add git submodules to GitHub example").

To avoid unnecessary problems (like python imports from a python file in a git submodule), only use underscores `_` in the repository names and paths, not hyphens (minus, dash) `-`.

So, underscore `_` good:  
**```github.com/user/template_repo```**

...and hyphen (minus, dash) `-` bad:  
```github.com/user/template-repo```

### GitHub flavoured Markdown editing notes

Three hyphens `---` is enough to add a horizontal line separator in the GitHub Markdown reading view (as used above). With more hyphens, regardless of spaces between them, GitHub still displays just one horizontal line.

A few hints on adding links and embedding images on github (code chunk content is copied below the chunk, look at it on github.com to see how it should look like).

#### Citing files with hyperlinks:
```
[README] - where the link will be shown

[README]: https://github.com/radRoy/template/blob/master/README.md
hidden in reading mode, requires an empty line, or another link assignment, above
```
[README] - where the link will be shown

[README]: https://github.com/radRoy/template/blob/master/README.md
hidden in reading mode, requires an empty line, or another link assignment, above

#### Embedding an image:
```
![Fiji blobs](https://github.com/radRoy/template/blob/master/blobs.png)  
blobs image caption
```
![Fiji blobs](https://github.com/radRoy/template/blob/master/blobs.png)  
blobs image caption
