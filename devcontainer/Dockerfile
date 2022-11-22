ARG NODE_VERSION="18"
# By default, we pull from the bullseye version. This is specifically to accomidate for the fact
# that our entire dev team runs on M1 macs. This also makes sure we get any VS-Specific commands or
# security fixes that the people much smarter than us over at Microsoft have
FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:${NODE_VERSION}-bullseye

# Our package manager of choice is pnpm, let's install that
RUN npm install pnpm@latest -g
