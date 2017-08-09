# ts-gulp-mocha

A rabidly opinionated style & build guide consisting of the following:

* [`ts-style`](https://github.com/google/ts-style): Google's (currently unofficial) recommendation for code style
* A set of `gulp` tasks that favor `mocha` for unit tests, VS Code as an IDE

This makes the assumption that all source code satisfies the glob `src/**/*.ts` and all tests are mocha files that satisfy the glob `test/**/*.ts`.
