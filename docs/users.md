# jarplace user list

Use `jarplace user list --repo REPOSITORY_NAME` for displaying all users of specified repository. 

# jarplace user info

`jarplace user info USER_NAME --repo REPOSITORY_NAME` command will show you information about specified user.

# jarplace user create

To create new user execute `jarplace repo create USER_NAME`. Don't forget to add mandatory parameters to this command: `--repo REPOSITORY_NAME` and `--password PASSWORD`. Optionally you can add `--readonly` parameter that will tell JarPlace if this user should be readonly or not.

# jarplace user modify

For and existing user you can modify password and readonly status. Use `jarplace repo modify USER_NAME --repo REPOSITORY_NAME` with `--password PASSWORD` and/or `--readonly` to alter those options.

# jarplace user delete

Deletes the user after confirmation. Note, that this operation can not be reverted!
