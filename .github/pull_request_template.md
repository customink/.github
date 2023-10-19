### Stakeholder Overview

<!--
Provide a concise summary of the motivation and the driving force behind them. These explanations are designed to be understandable to individuals without technical knowledge, and to people who may not be familiar with the context or specialize in the particular system or update being discussed. Think about the logical rationale for the modification and its practical impact, especially from the viewpoint of any end-users.

Good example:
IHP is in the process of updating the way carts get built. This is the core cart creation 
logic that sorts and groups orders into carts. With the upcoming change for the UI, users will 
be able to skip the Press Staging Queue and create a cart based on the flash count for the 
printer they are selecting for.

Good example:
We are currently sending all pageViewTags as custom events to fullstory which results in Fullstory 
throttling Custom Events for our accounts. This prevents us from using custom events for more legitimate 
users (e.g. custom event to track when a user is in test group).
This change is going to help Swag Management to identify sessions of users in the Swag Management test group.

Bad example:
change ingress
-->

### Risk Assessment _[(learn more)](https://app.getguru.com/card/iMnRRRjT/PR-Risk-Assessment)_
<!-- Describe the risk of this change and how it will be tested, deployed, and verified. -->

- [ ] Large/complex change?
- [ ] Big splash zone?
- [ ] Low margin for error?
- [ ] Low confidence?
- [ ] No/flipping feature flag?

### Changes

<!--
Please describe your code changes in detail for reviewers. Explain the technical solution you have provided and how it addresses the issue at hand.
-->

##### Updated Dependencies
 - None
<!--
Please include any notes that might be helpful for a reviewer to check the dependency changes you might have introduced.
  - gem version update
  - new gem introduced
  - data model update
-->

### Ticket

<!-- Fill in the ticket information with the details of your feature -->
[Monday issue](https://customink.monday.com/boards/12345/pulses/12345)

### Screenshots

<!-- Communicate the visual story of the change that is being made. -->

### Notes

_Recommended reading: [Code Review guide](https://github.com/customink/guides/blob/master/operations/code-review/README.md)_

<!--
Please include any notes that might be helpful for a reviewer to keep in mind while reading the changes.
-->

### Optional Tasks

<!--
Common, optional tasks are included here in case you forgot something important.
-->

- [ ] Include 🎩 Instructions
- [ ] Update the readme (README.md)
- [ ] Update the API or architecture docs (e.g. docs/api.md)

##### Library-Specific

- [ ] Increment the changelog (CHANGELOG.md)
- [ ] Increment the version number (lib/version.rb)
- [ ] [Release & Tag][release] the version above in Github

[release]: https://docs.github.com/en/github/administering-a-repository/managing-releases-in-a-repository

##### Performance
- Are there any new queries in your change set that might require new indexes?
- Do any new queries require time-boxing to avoid table-scans when the data grows?

### What GIF Best Describes This Pull Request?

<!--
![](https://i.giphy.com/media/WNuF3KK9NaQ8w/source.gif)
-->
