# gitignore
Standard *.gitignore* files used by VIA Studio.

## Usage
Combine the desired *.gitignore* files into a single *.gitignore* file using `cat`:

    cat Project.gitignore WordPress.gitignore >> .gitignore

Edit the *.gitignore* file to add any project specific rules.

If ignored files already exist in the repository you can remove them with `git rm --cached`. Otherwise, remove them with `rm` or a combination of `find` and `rm`.

## Contributing
As these are meant to be combined, add rules to their respective *.gitignore* file. Do not overlap projects into a single *.gitignore* file. Also, leave a new line at the end of file.

Comment and categorize rules. Especially those specific to [VIA Studio](http://viastudio.com) so contributors can easily identify them.

## Reference
Additional *.gitignore* files can be found in the [github/gitignore repo](https://github.com/github/gitignore). You are strongly encouraged to contribute to their project as well.

Rules should follow the strategy outlined by the [gitignore Documentation](http://git-scm.com/docs/gitignore).
