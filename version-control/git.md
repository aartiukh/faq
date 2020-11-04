# Git

## Submodules

### How to change the remote repo?

- Edit `.gitmodules` file and change the `url`
- Run `git submodule sync`

### How to check the actual remotes urls?

- Run `git submodule foreach -q git config remote.origin.url`

## Git flow

### Release

- `git flow init`
- `git flow release start 1.1.1`
- Bump version in CMake and README, and commit
- `git flow release finish 1.1.1`
- `git push origin master`
- `git push origin develop`
- `git push origin 1.1.1`
