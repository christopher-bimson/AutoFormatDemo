# AutoFormatDemo

A very simple demo of using a git pre-commit hook to automatically format source files, so there is no need to waste time with formatting debates in code reviews.

This is a an example for the purposes of a blog post.

Note that this repo _assumes_ that you have the correct tools installed. If you were doing this for real you would include a setup script or similar so people can pull the repo and get up and running straight away.

## Testing Locally

The hook script is located at `.\hooks\pre-commit`.

You can run `.\hooks\install-hooks.sh` if you don't want to install the script manually.

You'll need both `dotnet format` and `npm install --save-dev prettier`.
