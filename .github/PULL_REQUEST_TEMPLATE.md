# Default template

This is the default template loaded by GitHub

We could link to different template options, however this requires you to modify the hyperlinks below.
GitHub also generates different PR URLs depending on how you navigate to the PR.

1. Opened using the `Compare & pull request` button when GitHub prompts you to create a PR.
   Gives the URL format: https://github.com/MarcusPenn-CAL/template-test/compare/test?expand=1
   Modified to: https://github.com/MarcusPenn-CAL/template-test/compare/test?expand=1&template=API.md

1. Opened after comparing branches.
   Gives the URL format: https://github.com/MarcusPenn-CAL/template-test/compare/main...test
   Modified to: https://github.com/MarcusPenn-CAL/template-test/compare/main...test?template=API.md

Overall not user friendly, although there do seem to be a number of [extensions](https://chrome.google.com/webstore/detail/github-pr-template-picker/foaaibihjfcacpiehnjaghlhopofmmnb) to try and resolve this until [GitHub supports it natively](https://github.com/refined-github/refined-github/issues/1621).

Alternatively, we could use this as a catch all, much like the current template, e.g:

# Description

_What is the aim of your changes_

## API Checklist

- [ ] Unit tests
- [ ] QA tests

## UI Checklist

- [ ] ESLint
- [ ] Unit tests
- [ ] QA tests
