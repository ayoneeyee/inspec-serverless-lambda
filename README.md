# InSpec Serverless Lambda

# About the Project

# Usage

# Development / PR Process

## A complete PR should include the following core elements:

_ An open issue that describes the bug, new functionality or enhancement
- A signed PR ( aka `git commit -a -s` )
- A commit that has a `Fixes #<yourissue>` or `Closes #<yourissue>` at the end of the commit
- Code for the new functionality
- New unit tests for the functionality
- Updates to the docs and examples in `README.md` and `./docs/*`
- (if needed) Example / Template files ( `metadata.yml`,`example.yml`, etc )
  - Scripts / Scaffolding code for the Example / Template files ( `generate_map` is an example )
- Example Output of the new functionality if it produces an artifact

1. open an issue on the main project website noting the issues your PR will address
2. fork the repo
3. checkout your repo
4. cd to the repo
5. git co -b `<your_branch>`
6. bundle install
7. `hack as you will`
8. test via rake
9. ensure unit tests still function and add unit tests for your new feature
10. add new docs to the `README.md` and to `./docs/examples`
11. update the CLI as needed and add in `usage` example
12. (if needed) create and document any example or templates
13. (if needed) create any supporing scripts
14. (opt) gem build inspec_tools.gemspec
15. (opt) gem install inspec_tools
16. (opt) test via the installed gem
17. git commit -a -s `<your_branch>`
18. Open a PRs aginst the MITRE project repo

# Testing

There are a set of unit tests. Run `rake test` to run the tests.

To release a new version, update the version number in `version.rb` according to the [Semantic Versioning Policy](https://semver.org/).


# MITRE InSpec Documents, Templates and Tidbits

Here lies the best ideas of the MITRE InSpec Team

### NOTICE

© 2018 The MITRE Corporation.

Approved for Public Release; Distribution Unlimited. Case Number 18-3678.

### NOTICE  

MITRE hereby grants express written permission to use, reproduce, distribute, modify, and otherwise leverage this software to the extent permitted by the licensed terms provided in the LICENSE.md file included with this project.

### NOTICE

This software was produced for the U. S. Government under Contract Number HHSM-500-2012-00008I, and is subject to Federal Acquisition Regulation Clause 52.227-14, Rights in Data-General.

No other use other than that granted to the U. S. Government, or to those acting on behalf of the U. S. Government under that Clause is authorized without the express written permission of The MITRE Corporation.

For further information, please contact The MITRE Corporation, Contracts Management Office, 7515 Colshire Drive, McLean, VA  22102-7539, (703) 983-6000.
