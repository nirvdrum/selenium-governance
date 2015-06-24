# Governance

The Selenium project is a large that it can not, and must not, be run by a single person making decisions.

## Project Committee

The Selenium project has 5 people who, with the help of the Software Freedom Conservancy, will control the day to day running of the project.

The Project Committee will meet at least 6 times a year. Minutes from those
meetings will be publicly available. This is to make sure that the project
committee are regularly meeting and Module Owners and Module Peers can be aware
of changes that are regularly happening.

The Project Committee are voted in if they meet the following criteria:
* Only have a maximum of 2 people from the same company.
  * This is to make sure the direction of the project is not influence by a single company.
* The person has been contributing to the project for more than 6 months.
  * Contributions can take the following form:
    * Are a peer or module owner within the Selenium Project.
      * Have made a change to a Selenium repository or documentation.
    * Regularly make contributions to the W3C WebDriver Working Group
      * Are a member of the W3C Working Group as either a W3C Member or Invited Expert.
      * Supplying change sets for the WebDriver specification
      * Supplying changesets for tests for the WebDriver Specifications
    * Helping out on mailing lists when people have questions
    * Helping out on forums not directly associated with the Selenium Project. For example on https://stackoverflow.com

The Project Committee tenure is to last for 24 months. At the end of this time the Project Committee members will need to re-elected to the post.

If a Project Committee member, during their tenure, does not meet any of the criteria above there will be a vote to replace that person.

### Voting

Voting for new Project Committee members is done by Module Owners and Module peers.

## Modules

A module is, in the case of code, a piece of functionality, or in the case of non-code, an activity, with reasonably well-defined boundaries. (Some of the below explanation is code-focussed, but analogous points can be made for non-code.).

### Module Owners

The Selenium Project has a number of subject matter experts who, through expertise or historical reasons, have come to “own” particular pieces of the project. These Module Owners own the direction of the project and, with the help of the Module Peers, make sure that improvement to code and documentation is done.

Module owners are not tyrants. They are chartered to make decisions with input from the community and in the best interests of the community. Module owners are not required to make code changes or additions solely because the community wants them to do so. (Like anyone else, the module owners may write code because they want to, because their employers want them to, because the community wants them to, or for some other reason.) Module owners do need to pay attention to patches submitted to that module. However “pay attention” does not mean agreeing to every patch.

In terms of voting for a project committee, a Module Owner’s vote counts the same as a Module Peer.


### Module Peers

A Module Peer is a person that has the ability to push changesets to a Selenium Project repository. Module Peers and Module owners can nominate people to become Module Peers if they have shown they will regularly make contributions to the Project. The nominees are then voted in by a simple majority vote (more +1s than -1/~1 votes)

### Removal of Module Peer Status

A Module Peer will hold the position of Module peer indefinitely unless one of the following occurs:
* Breaches the Code of Coduct of the project
* The Module Peer asks to have their Module Peer status revoked.

## Escalation and Review

The owner and peers of the Module Ownership module will get involved if controversy develops and cannot be resolved otherwise. A module owner may ask for a public statement of agreement with a particular action. Sometimes other contributors suggest ways in which a module owner might improve. Sometimes there is ongoing controversy. We prefer that the community resolve these issues when possible, but acknowledge that this can’t happen all the time. We try to avoid making absolute decisions like “this must happen” but will do so if required.

## Poorly Maintained Modules

Periodically a module is not well maintained and no longer interacts well with the rest of the codebase. This can happen where there is no module owner, or when a designated module owner is too busy with other things to tend to the module. Conceivably it could happen when a module owner is active, but has an approach to a module that the community in general believes is inappropriate. We prefer that the development community identify such modules, propose a solution, and implement improvement. If this can’t happen for some reason then the Module Ownership Peers will get involved to find the best possible resolution.
