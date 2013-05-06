# npm-release

A little script to help release `npm` modules. It:

- Bumps the version in `package.json`
- Commits 'Release x.x.x'
- Tags
- Pushes

## Install

`npm install -g npm-release`

## Usage

You must use `npm-release` in a folder with a `package.json` and a remote to push to.

`npm-release 0.0.2`

## License

MIT