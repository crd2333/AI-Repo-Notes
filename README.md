# CS-Repo-Notes
Some notes of CS Repositories, mainly in the form of code annotations (some in 中文 and some in English, based on my mood), arranged by git submodules.

## Add Repos
- public repos: add by http url
  ```
  git submodule add <http_url> repo_name
  ```
- private repos: add by ssh
  ```
  git submodule add <ssh_url> repo_name
  ```

## Pull Notes
I should clone with my user name (and those private ssh repos will pass authentication):
```
git clone --recurse-submodules --shallow-submodules git@github.com:crd2333/CS-Repo-Notes.git
```
> Use shallow clone to only get the latest commit of each submodule, saving space and time.
