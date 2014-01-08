# gitignore
Standard *.gitignore* files used by VIA Studio.

## Usage
Combine the desired *.gitignore* files into a single *.gitignore* file using `cat`:

    cat Project.gitignore WordPress.gitignore >> .gitignore

Edit the *.gitignore* file to add any project specific rules.

If ignored files already exist in the repository you can remove them with `git rm --cached`. Otherwise, remove them with `rm` of a combination of `find` and `rm`.

## Contributing
As these are meant to be combined, add specific rules to the specific *.gitignore* file. Do not overlap projects into a single *.gitignore* file.

Comment and categorize rules. Espcially those specific to [VIA Studio](http://viastudio.com).
