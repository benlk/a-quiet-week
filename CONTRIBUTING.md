# Contributing

We welcome contributions and suggestions to help us improve any of these documents. Please start by [reading our code of conduct](CODE_OF_CONDUCT.md).

## Workflow

When you contribute to this repository, you agree to license your contributions under [A Quiet Year's license](LICENSE.md) in perpetuity.

1.  [Fork this repo](https://help.github.com/articles/fork-a-repo)
2.  Create a branch (`git checkout -b my-branch`)
3.  Stage and commit your changes (`git commit -am 'description of my changes'`)
4.  Push the changes to your fork (`git push origin my-branch`)
5.  [Submit a pull request to the parent repo](https://help.github.com/articles/creating-a-pull-request). Please read our [guide to submitting pull requests](/how-to-work-with-us/pull-requests.md) to see what we expect in a good pull request message.
6.  Pull request should be assigned to:
	- @benlk

Additionally, you can [create issues](https://github.com/benlk/a-quiet-year/issues) on this repo to suggest changes or improvements.

Particular pinch points:

- Use [markdown syntax](https://help.github.com/categories/writing-on-github/) for all documents
- Please make sure that edited CSVs are valid.
- If your pull request changes a file's name or the location of a file within the repository, please check all other files in the repository for links to the former filename. (`git grep "old-filename-here.md"`)

## File-specific notes:

- cards.csv
	- prompt values *should* be less than 140 characters long
	- prompt values *must* be enclosed in quotes.
