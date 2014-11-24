<img src="https://dl.dropboxusercontent.com/s/1d8v65acdof1q1h/logo-westfield.svg" width="249">

# Overview

The Westfield Scally CSS Framework (WS) sits on top of our open source CSS framework [Scally](https://github.com/westfieldlabs/scally) and is specific to Westfield, mostly based off this: <http://styleguide.westfieldlabs.com/>.

It follows the exact same architecture as [Scally](https://github.com/westfieldlabs/scally).

Think of WS as the lick of paint and Scally as the scaffolding.

*More documentation coming soon*, in the meantime ask any questions in the **Westfield Scally Framework** HipChat room or email any of the Westfield Labs front end engineers:

- [Chris Pearce](mailto:cpearce@westfield.com)
- [Alec Raeside](mailto:araeside@westfield.com)
- [Kate Levin](mailto:klevin@westfield.com)
- [Sean Gee](mailto:sgee@westfield.com)

Use the repo's [GitHub Issues](https://github.com/westfieldlabs/westfield_scally/issues) to log any issues, additions, enhancements, or ideas.




# Browser Support

- IE9+.
- Chrome.
- Firefox.
- Opera.
- Safari (incl. iOS).
- Android 3+.




# Linting

To ensure a consistent authored code base and to keep things clean and readable WS uses the [`scss-lint` tool](https://github.com/causes/scss-lint).

## Installation and usage

To install run the following command:

    gem install scss-lint

Which will install the Ruby Gem.

To use `cd` into your project's root and run the command:

    scss-lint ./

Which will lint *everything*, to lint at a more granular level [see](https://github.com/causes/scss-lint#usage).

## Linting rules

WS' linting rules can be [found here](.scss-lint.yml). And WS has a Rake test setup that'll run the `scss-lint` tool automatically to ensure no badly formatted CSS goes into the framework.

# Licence

Copyright 2014 Westfield Labs Corporation

Licensed under the [Apache v2.0](http://www.apache.org/licenses/LICENSE-2.0.html) licence.
