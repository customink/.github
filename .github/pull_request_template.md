### Stakeholder Overview _[(learn more)](https://app.getguru.com/card/TGyLkrnc/Pull-Review-Stakeholder-Overview)_

<!--
Provide a concise summary of the motivation and the driving force behind this change, in a way that anyone without context can understand.
-->

### Risk Estimate _[(learn more)](https://app.getguru.com/card/iMnRRRjT/Pull-Request-Risk-Estimate)_
<!-- WIP: Some teams are experimenting with this section. Fee free to remove. -->
_[Replace this with a description of the risk, if any, and how the change will be deployed.]_

<!-- add a ✅ or 🚫 as appropriate -->
- Big/complex change?
- Big splash zone?
- High stakes if errors occur?
- Low confidence?
- Not hidden by feature flag?
- Negligible risk!

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
