# template
My template repo including some basic bash scripts for git handling.

For a foolproof introduction to handling `git submodule`s, watch this youtube video: <https://www.youtube.com/watch?v=eJrh5IjWSGM> ("Add git submodules to GitHub example").

To avoid unnecessary problems (like python imports from a python file in a git submodule), only use underscores `_` in the repository names and paths, not hyphens (minus, dash) `-`.

So, underscore `_` good:  
**```github.com/user/template_repo```**

...and hyphen (minus, dash) `-` bad:  
<s>**```github.com/user/template-repo```**</s>

## GitHub flavoured Markdown editing notes

To cite / link to a file within a GitHub repo (e.g., the one belonging to this README.md), add a few text fragments to the repository's url:
```
[README] - Where the link will be shown  
[README]: https://github.com/radRoy/template/blob/master/README.md - assigning an url to the link named 'README' (hidden below in reading mode)
```
[README] - Where the link will be shown  
[README]: https://github.com/radRoy/template/blob/master/README.md - assigning an url to the link named 'README' (hidden in reading mode)

To embed an image:
```
![Fiji blobs](https://github.com/radRoy/template/blob/master/blobs.png)
```
![Fiji blobs](https://github.com/radRoy/template/blob/master/blobs.png)
