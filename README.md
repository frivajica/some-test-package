# NPM Package Example
### This is an example repository for developing/testing npm packages locally.

To install it on other projects locally:
1. Within this package's folder.
    1. Run `npm install`.
    2. Run `npm run build`.
    3. Run `npm link` (so it is recognized as a package by **npm** as _some-test-package_).

2. In the project folder where you want to install and use this package.
    1. Run `npm link some-test-package` (local equivalent for `npm install some-test-package`).
    2. Import it where you need it.
       - `import { test } from 'some-test-package'`
