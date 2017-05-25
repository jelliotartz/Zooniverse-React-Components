Zooniverse-React-Components
===========================

What the repo name says

`npm i` to install dependencies

Components should be added to the `src/components` folder and an export to `src/index.js`

Any default styles can be added as a stylus file in `src/css`. The require for the stylus file should be added to `zooniverse-react-components.styl`

`npm version [semver new version]` will run helper preversion and postversion scripts. `preversion` will run the tests. `postversion` will push the updated repo and the updated git tag to github.

For now, we will git tag and install via github. 

`npm test` to run mocha tests
