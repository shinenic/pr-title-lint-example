# Pull Request Title Lint Action
A linter for verify the pull request title format based on the [document](https://www.notion.so/shypyard/Pull-request-code-review-convention-2c1f49d2382f4fa6a030c7db2da6e7ec)

## Test cases
```
Test case (type of PR)
feat: description
fix: description
perf: description
refactor: description
chore: description
test: description
wrong: description
feat: 
feat:

Test cases (partially optional):
feat: description [sc-1234]
feat(Design System): demo project
feat: [1/3] description

Test cases (description):
feat: test
feat: demo color system `test` - Some Symbol & * !@#$%^&* (test)
feat: demo color system `test` - Some Symbol & * !@#$%^&* (test) [sc-1234]
feat:test

Test cases (n/n)
feat: [1/3] description
feat:[1/3] description
feat: [1/3]description
feat: [1/n] description
feat: [1/N] description
feat: [1/x]description

Test cases (Story)
feat: description [sc-1234]
feat: description[sc-1234]
feat: description [sc-12345]
feat: description [1234]
```