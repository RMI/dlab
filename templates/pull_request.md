When opening a new PR, first copy this markdown template into the description. Then fill in the relevant details in the first section above the [Review Checklist](#review-checklist), and delete this section.

Once created, copy the link to the PR into the DLab slack channel, and make any specific requests for reviewers if appropriate.

----------

# Description

# Connected Tasks & Issues
### Monday
### Github

# Additional Notes

----------
# Review Checklist

For larger PRs, please checkout the branch locally. If it's a package, build and install it, otherwise there are a number of ways to perform more free from testing:
- use the python REPL
- run scripts in the repo or create some
- run the included test suite


## General
- [ ] code is reasonably well organized
- [ ] changes match the above description
- [ ] things are reasonably understandable and readable
- [ ] changes generally look like they implement the desired functionality
- [ ] if the changes relate to a package, can it be built and installed?
- [ ] if the changes relate to an application, 

## Style & Formatting
> [!NOTE]
> Refer to [PEP8](https://peps.python.org/pep-0008/) for details.
- [ ] functions, methods, properties, and variables are snake case
- [ ] classes are camel case
- [ ] PR is free of commented code

## Documentation
- [ ] all non-trivial functions and methods have [docstrings](https://peps.python.org/pep-0257/) with at minimum:
  - [ ] description
  - [ ] arguments
  - [ ] return value(s)
- [ ] all classes have docstrings with sufficient explanation
- [ ] additional comment lines are explanatory or prefixed with `TODO` (for the latter, ensure an accompanying task exists in Monday)

## Testing
> [!NOTE]
> Optional until testing is more widely implemented
- [ ] all non-trivial functions/methods have accompanying unit tests
- [ ] tests reflect appropriate breadth of success/failure scenarios or inputs
- [ ] all tests passed unless accompanied by sufficient documentation and explanation

