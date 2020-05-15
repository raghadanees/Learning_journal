# Remote Repositories
- ## viewing all the remote URLs
By using git remote -v, you can view all the remote URLs next to their corresponding short names.
$ git remote -v

*Example*

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)

remote2 https://github.com/remote2/example (fetch)

remote2 https://github.com/remote2/example (push)

- ## Pushing
To push your changes “upstream” for sharing, you would use the following git push command format:

git push [remote-name][branch-name]
$ git push origin master

- ## Renaming Remotes

To rename a remote’s short name, use the git remote rename command.

*Example*

$ git remote rename js jane

$ git remote

origin

jane
