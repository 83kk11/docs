---
title: REST API endpoints for repository interactions
shortTitle: Repository
intro: >-
  Use the REST API to temporarily restrict which type of user can comment, open
  issues, or create pull requests in a public repository.
permissions: >-
  People with owner or admin access to temporarily restrict which type of user
  can comment, open issues, or create pull requests in a public repository.
versions: # DO NOT MANUALLY EDIT. CHANGES WILL BE OVERWRITTEN BY A 🤖
  fpt: '*'
  ghec: '*'
topics:
  - API
allowTitleToDifferFromFilename: true
autogenerated: rest
---

## About repository interactions

People with owner or admin access can use the REST API to temporarily restrict which type of user can comment, open issues, or create pull requests in a public repository. {% data reusables.interactions.interactions-detail %} Here's more about the types of {% data variables.product.github %} users:

* {% data reusables.interactions.existing-user-limit-definition %} in the repository.
* {% data reusables.interactions.contributor-user-limit-definition %} in the repository.
* {% data reusables.interactions.collaborator-user-limit-definition %} in the repository.

If an interaction limit is enabled for the user or organization that owns the repository, the limit cannot be changed for the individual repository. Instead, use the [User](/rest/interactions/user) or [Organization](/rest/interactions/orgs) interactions endpoints to change the interaction limit.

<!-- Content after this section is automatically generated -->
