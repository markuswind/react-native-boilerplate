## About

A React Native boilerplate with TypeScript support. Including development setup to ensure clean and working code before pushing.

## Included

The following development dependencies are included:

- [typescript](https://github.com/Microsoft/TypeScript)
- [prettier](https://github.com/prettier/prettier)
- [commitlint](https://github.com/marionebl/commitlint)
- [tslint](https://github.com/palantir/tslint)
- [husky](https://github.com/typicode/husky)
- [editorconfig](https://editorconfig.org/)

## Getting started

First clone the repository and install dependencies.

```bash
$ git clone https://github.com/markuswind/react-native-boilerplate
$ yarn install
```

**Renaming**

To rename the React Native project, you first have to edit the name in `package.json`. Afterwards you have to run the following commands to re-generate the project files.

```bash
$ rm -r ./android && rm -r ./ios
$ react-native upgrade
# answer no to replace .gitignore
# answer yes to replace app.json
$ git add .
$ git commit -m "chore: renamed project"
# done!
```
