# jarplace repo list

Use `jarplace repo list` for displaying all your Maven repositories. 

# jarplace repo info

`jarplace repo info REPOSITORY_NAME` command will show you information about specified repository.

# jarplace repo create

To create new repository execute `jarplace repo create REPOSITORY_NAME`. Optionally add specify `--private` to this command if you are about to create private repository. Private repo means that basic auth will be required not only for pushing artifacts, but also for pulling (read protection).

# jarplace repo modify

Currently it's possible to modify only one parameter of the repository: whether it's public or private. Use `jarplace repo modify REPOSITORY_NAME` and `jarplace repo modify REPOSITORY_NAME --private` correspondingly. 

# jarplace repo delete

Deletes the repository after confirmation. Note, that this operation can not be reverted!
