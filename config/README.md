`mapping.json` maps file names to test suites. This file is used by [test-case-reminder-bot](https://github.com/wordpress-mobile/test-case-reminder-bot) to decide which test cases to suggest to PR owner. Once a file changed in the PR match with the `regex`, the bot will drop a comment to the PR suggesting the test suites stated in the `testFile` attribute.

If you want to test your updates to the mapping.json file you can use unit tests mentioned [here](https://github.com/wordpress-mobile/test-case-reminder-bot#unit-tests).
