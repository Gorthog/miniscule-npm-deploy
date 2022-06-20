instructions what to do before publishing a package to NPM:

1. Make sure the package has a unique name
1. Specify which files should be sent to NPM - add "files" to package.json
1. Split out 'dependencies' and 'devDependencies'
1. Set out package to be publicly accessible - add "publishConfig" to package.json
1. If building a CLI, configure the file to run
   - add "bin" to package.json and point to the file
   - add shebang to the file
1. Add a 'prePublish' script to your package.json
1. Commit to git
1. Run `npm publish`
