# CivicActions Security Requirements

CivicActions has defined a set of security requirements to ensure the security of the code produced by the our developers. Most of these requirements are defined in the [CivicActions Security Policy](https://github.com/CivicActions/security-policy) but they are repeated here for clarity:
- Maintain up-to-date versions of software on all systems (sandbox, development, staging and production). This includes:
 - Drupal
 - Operating System (GNU/Linux; some developers may use Mac OSX) - Editors, debuggers, and other tools
- Always apply relevant CVE patches within 30 days of their release, usually within two weeks
- Limit live data on development machines. In particular:
 - no client user PII (other than test PII created by developers)
 - no copyrighted content
 - no access restricted files
- Minimize custom code: use contrib modules and contribute patches when needed
 - Create generic modules for new functionality and contribute them to the Drupal project
 - Custom code must conform to Drupal coding and undergo internal security review
- Before being integrated into the development branch, all code updates must:
 - have an associated ticket in JIRA
 - undergo static code analysis with [Drupal Code Quality](https://www.drupal.org/project/dcq) (exceptions for CSS, features, perhaps others)
 - peer review
 - full automated testing 

_**If you have questions about any of the above or the linked documents, ask your Project Manager or Tech Lead.**_
