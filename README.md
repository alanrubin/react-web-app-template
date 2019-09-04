This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Recommended Tools & Practices

- [x] Package Manager: yarn
- [x] Code Formatter: prettier
- [x] ES6 JS syntax: async/await instead of promises + es6 destructuring
- [x] Static Types: typescript (with babel 7, so no TS compile trouble)
- [ ] Static Analysis: Eslint (with Typescript rules support) vs. tslint
- [ ] CSS-in-JS: emotion vs. styled components: CSS-in-JS vs. SASS/LESS
- [ ] Dev tools integration: jest + eslint + typescript + vscode integration: https://www.youtube.com/watch?v=Pl2heYVwQ-Q + https://www.youtube.com/watch?v=CdAhR70XD3g + https://github.com/jest-community/jest-runner-eslint + https://github.com/mightyiam/eslint-config-standard-with-typescript
- [ ] End-to-End Testing: Cypress
- [ ] Component Explorer and Documentation: docz vs. storybook
- [ ] React Unit Testing: react-dom-testing (https://github.com/kentcdodds/react-testing-library) vs. enzyme
- [ ] Internationalization: i18next
- [ ] Commit Workflow: lint-staged + husky: prettier + lint + typescript
- [ ] Visual Testing: https://applitools.com/ + https://happo.io/
- [ ] Import Paths: absolute path instead of relative: https://github.com/facebook/create-react-app/issues/5118 & https://github.com/unzico/cra-2-typescript-sass-antd
- [x] Node versions management: nvm
- [ ] Folder Structure
- [ ] File name standards: consistency
- [x] source-map-explorer to analyze build size
- [x] environment variables for secrets/keys : https://facebook.github.io/create-react-app/docs/adding-custom-environment-variables#adding-development-environment-variables-in-env & https://facebook.github.io/create-react-app/docs/deployment#customizing-environment-variables-for-arbitrary-build-environments
- [x] progressive web-apps support: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app
- [ ] debugging in development: https://github.com/infinitered/reactotron
- [ ] debugging jest tests : https://facebook.github.io/create-react-app/docs/debugging-tests#debugging-tests-in-chrome
- [ ] proxy backend in development: https://facebook.github.io/create-react-app/docs/proxying-api-requests-in-development
- [ ] deployment: netlify vs. now vs. aws (https://github.com/fastlane/fastlane for mobile)
- [ ] error reporting: sentry
- [ ] ux reporting: mouseflow
- [ ] log in production: https://logz.io/ + https://www.loggly.com/
- [x] hot module reloading
- [ ] analytics: Google Analytics
- [ ] yarn workspaces vs. lerna: package division + code and components sharing
- [ ] typescript format: https://github.com/palmerhq/typescript ?
- [ ] versioning: auto semantic versioning (https://semver.org/) using https://github.com/semantic-release/semantic-release
- [ ] Static code review/coverage tools: https://www.codacy.com/ + https://codecov.io/
- [ ] Continuous Integration
- [ ] Lazy Loading: https://blog.bitsrc.io/improve-react-performance-using-lazy-loading-and-suspense-933903171954
- [ ] State management: plain state vs. context vs. Redux vs. Mobx State Tree

## Bad Practices
- Frontend code in same repo of Backend code (specially if using Maven)

## Recommended Libraries

- [ ] emotion vs. styled-components
- [ ] polished
- [ ] i18next: i18next-scanner + react-i18next
- [ ] date-fns instead of momentjs
- [ ] fontawesome
- [ ] react-select
- [ ] axios instead of fetch (https://medium.com/wix-engineering/why-i-wont-be-using-fetch-api-in-my-apps-6900e6c6fe78)
- [ ] history vs. https://reach.tech/router
- [ ] iframe-resizer
- [ ] query-string
- [ ] react-day-picker
- [ ] react-ga
- [ ] formik + yup
- [ ] mobx-state-tree vs. immer vs. React State vs. React Context
- [ ] pace for enhance initial loading experience : https://github.hubspot.com/pace/docs/welcome/
- [ ] yup or validator for validation
- [ ] big lists rendering - https://github.com/bvaughn/react-window

### IDE
- VSCODE: don't think twice
- VSCODE Plugins: https://github.com/kentcdodds/ama/issues/406
- VSCODE Font/Color: https://twitter.com/kentcdodds/status/1011999102492504064

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
