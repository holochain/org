# Contributing

[![Project](https://img.shields.io/badge/project-holochain-blue.svg?style=flat-square)](http://holochain.org/)
[![Chat](https://img.shields.io/badge/chat-chat%2eholochain%2enet-blue.svg?style=flat-square)](https://chat.holochain.net)

As an Open Source project Holochain welcomes many sorts of contributions, bug-report & fixes, code contributes, documentation, tests, feedback and more.

## Social
We are committed to foster a vibrant thriving community, including growing a culture that breaks cycles of marginalization and dominance behavior. In support of this, some open source communities adopt [Codes of Conduct](http://contributor-covenant.org/version/1/3/0/).  We are still working on our social protocols, and empower each team to describe its own *Protocols for Inclusion*.  Until our teams have published their guidelines, please use the link above as a general guideline.

## Coordination

* For task management we use [Waffle](https://waffle.io/holochain/org) or for the non-kan-ban view [github's issues](https://github.com/holochain/org/issuees)
* Chat with us on our [chat server](https://chat.holochain.net) or [Gitter](https://gitter.im/metacurrency/holochain)

## Test Driven Development
We use **test driven development**. When you add a new function or feature, be sure to add the tests shows that it works.  Pull requests without tests will most-likely not be accepted!

## Git Hygiene
This section describes our practices and guidelines for using git and making changes to the repo.

* We use Github's pull requests as our code review tool
* We encourage any dev to comment on pull requests and we think of the pull request not as a "please approve my code" but as a space for co-developing, i.e. asynchronous "pair-coding" of a sort.
* We develop features on separate branches identified by the Github issue number, i.e. `124-my-new-feature`
* We use merge (not rebase) so that commits related to a ticket can be retroactively explored.
* In most repos development happens on a `develop` branch which gets merged to master when there's a release.
