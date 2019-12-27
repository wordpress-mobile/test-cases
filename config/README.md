`mapping.json` maps file names to test suites. This file is used by [test-case-reminder-bot](https://github.com/wordpress-mobile/test-case-reminder-bot) to decide which test cases to suggest to PR owner. If one of the files changed in the PR matches with the `regex`, the bot will drop a comment in the PR suggesting the test suites stated in the `testFile` attribute.

If the same `<test-suite>.md` is matched more than once for a PR, [test-case-reminder-bot](https://github.com/wordpress-mobile/test-case-reminder-bot) will eliminate duplicates so you don't have to worry about putting the same `<test-suite>.md` file multiple places in the `mapping.json`.

If you want to test your updates to the mapping.json file you can use unit tests mentioned [here](https://github.com/wordpress-mobile/test-case-reminder-bot#unit-tests).
