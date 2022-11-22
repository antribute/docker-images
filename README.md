# Docker Images

A selection of docker images that make our lives at Antribute easier

## List of Images

| Name         | Description                                       |
| ------------ | ------------------------------------------------- |
| Devcontainer | A VS Code Devcontainer running Node 18 and PNPM 7 |

## Creating a Release

We use Git tags to facilitate releases. Releases can be ran by pushing a tag with the following
format: `<imageName>/<version>`. For instance, if you wanted to release version `0.2.0` of
`devcontainer` you would run

1. `git tag devcontainer/0.2.0`
1. `git push --tags`
