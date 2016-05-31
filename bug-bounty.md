---
layout: bug-bounty
title: Bug bounty
permalink: /bug-bounty/
---

#### Timeframe & Budget

This bug bounty program is not a contest or competition. It is an experimental and discretionary rewards program. Depending on the outcomes of this event we will see if there is a need to continue running this type of activity in the future.

Start - **2016.06.01**

Final submission - **2016.06.05 - 23:59**

Budget - **1500 EUR**

##### Scope & Bounty

In principle, any Adform-owned web service that handles reasonably sensitive user data is intended to be in scope.

_We will prioritize bugs submitted by a person who is not directly associated with the reported bug. In other words do not look for bugs in your own product/services._

Before you submit a bug, we suggest you pay attention to the tips and instructions bellow and include all relevant details in your report. This will help us to properly assess your submission and for you to be concise.

 * Report a qualifying vulnerability that is in the scope. Does it align to a CVE or OWASP issue?
 * Write a description that clearly and concisely identifies the affected component.
 * Present a well-developed attack scenario, and include clear reproduction. This will get triaged much faster and is more likely to be prioritized correctly. If it contains many steps, please create a video so we can attempt to perform the same steps. 
 * What is the impact of your issue?
 * What are some scenarios where an attacker would be able to leverage this vulnerability?
 * What would be your suggested fix?
 * If you found XSS vulnerability, don't use "alert(1)" as a proof-of-concept. Take it one step further and show how it can be exploited.
 * All submissions have to be made in JIRA - https://adform.atlassian.net/browse/BB

##### Who will evaluate submitted bugs?
A "Security Verification" group will be formed from different teams within Adform. They will assess all submissions and determine if it qualifies for a bounty. The group consists of:

 * Martynas Baltrūnas
 * Liudas Jankauskas
 * Andrius Januta
 * Paulius Leščinskas
 * Karolis Pocius

##### How is the bounty reward determined?

Security Verification group will take many factors into account when determining a reward. These factors include the complexity of successfully exploiting the vulnerability, the potential exposure, as well as the percentage of impacted users and systems. Sometimes an otherwise critical vulnerability has a very low impact simply because it is mitigated by some other component, e.g. requires user interaction, an obscure web browser, or would need to be combined with another vulnerability that does not currently exist.

##### How are bounty payments made?

Payments will be made as a bonus to your original salary that comes in the beginning of the month. In this case until July 5th.

##### What does not qualify for a bounty?

 * Insecure cookie settings for non-sensitive cookies
 * Cookies missing secure/httponly
 * Disclosure of public information and information that does not present a significant risk
 * Bugs requiring exceedingly unlikely user interaction
 * Bugs that have already been submitted by another user in **[HERE](https://adform.atlassian.net/browse/BB)**, that we are already aware of.
 * Bugs that have been submitted/registered previously in JIRA before this bug bounty.
 * Issues related to email coming from *@adform.com addresses (e.g. things related to DMARC and SPF)
 * Disclosure of tools, libraries, software and/or their versions used by Adform
 * Missing security headers that do not lead directly to a vulnerability
 * Theoretical attacks without actual proof of exploitability/concept
 * Reports from automated tools or scanners
 * Missing security-related HTTP headers which do not lead directly to a vulnerability
 * Allowing browsers to remember passwords via auto-complete
 * Issues related to software or protocols, not under our control
 * Disclosure of public information or information that in our opinion does not present a significant risk
 * Login/logout CSRF or forms missing CSRF tokens (unless you provide evidence of an actual CSRF vulnerability)
 * Vulnerabilities only affecting users of outdated or unpatched browsers and platforms
 * Descriptive/verbose/unique error pages (without proof of exploitability)
 * SSL/TLS best practices
 * XSS in Flash files not developed by Adform, e.g. third-party ads

##### What are the legal terms and/or restrictions of Bug Bounty challenge?

 * Act in good faith.
 * Do not degrade or harm the performance/reliability/integrity of our services or data (e.g. via automated scanning, brute forcing, or denial of service attacks).
 * DDoS/spam attacks are not allowed.
 * Only report issues that are in scope.
 * Don’t publicly disclose a bug.
 * Check the list of non-qualifying vulnerabilities to make sure that you aren't spending time chasing down a vulnerability that isn't going to qualify for a bounty.
 * Do not attempt to modify any production user data that is not your own.
 * We strongly recommend you to use **test credentials or accounts**.
