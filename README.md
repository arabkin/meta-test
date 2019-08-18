# Meta Git Addon demo

This repo represens mixed, "mono-repo" and "multi-repo" approaches.
It actually allows to manage multiple separate repos in one place.
Let's assume this repo is just for a grouping purposes and it will contain the following **services**:
- **userService** managed in `git@github.com:arabkin/userService.git`
- **graphqlService** managed in `git@github.com:arabkin/graphqlService.git`
- **appService** managed in `git@github.com:arabkin/appService.git`

All these are buin managed in `.meta` file.

To do the changes for all the repos at once, prefix all git commands with __meta__ command.
