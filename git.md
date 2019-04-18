# Git

## Submodules

### How to change the remote repo?
* Edit `.gitmodules` file and change `url`
* Run `git submodule sync`

To check atual remotes urls run `git submodule foreach -q git config remote.origin.url`.
