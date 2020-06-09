# WHATWG Participant Data

This repository hosts the data submitted through the [WHATWG Participant Agreement](https://participate.whatwg.org/agreement).  When someone submits a pull request to a WHATWG repository, automated processes check the data here to determine whether the person submitting has made the required commitments under the [IPR Policy](https://whatwg.org/ipr-policy). 

## Maintenance

Whenever an individual or entity signs the agreement, an entry is added to the respective JSON file with the `verified` field set to false. When they then make a contribution, the respective editor will [check everything is in order](https://github.com/whatwg/participate.whatwg.org#process-for-editors "Process for Editors") and set the `verified` field to true or escalate as appropriate. If they do not end up contributing their `verified` field likely is not changed.

The automated processes use the GitHub organization identified in the `"gitHubOrganization"` field in the entity's entry in the `entities.json` file in this repository to determine whether to accept a pull request. People affiliated with entities that have signed the entity agreement should _not_ sign the Participation Agreement themselves. Instead, they should work with one of the contacts identified in that entry to get themselves added to the appropriate GitHub organization, then [make sure their membership is public](https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/publicizing-or-hiding-organization-membership) so the automated processes can see it. Similarly, when a person is no longer affiliated with an entity, it is the responsibility of the identified contacts to ensure their entry is removed from the identified GitHub organization.
