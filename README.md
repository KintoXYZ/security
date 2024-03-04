# Kinto Security Repository

This document describes the Security Process for Kinto, including vulnerability disclosures and the ongoing [Bug Bounty program](#bug-bounty-program). 

We are committed to conduct our Security Process in a professional and civil manner. Public shaming, under-reporting, or misrepresentation of vulnerabilities will not be tolerated.

For any vulnerability not in the scope of the bug bounty program, please follow the [section](#receiving-disclosures) as the team might also be interested on it.

## Responsible Disclosure Standard

Kinto follows a community [standard](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#the-standard) for responsible disclosure in cryptocurrency and related software. This document is a public commitment to following the standard.

This standard provides detailed information for:

- [Initial Contact](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#initial-contact): how to establish initial contact with Kinto's security team.
- [Giving Details](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#giving-details): what details to include with your vulnerability disclosure after having received a response to your initial contact.
- [Setting Dates](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#setting-dates): how to agree on timelines for releasing updates and making details of the issue public.

Any expected deviations and necessary clarifications around the standard are explained in the following sections.

## Receiving Disclosures

Kinto is committed to working with researchers who submit security vulnerability notifications to us, to resolve those issues on an appropriate timeline, and to perform a coordinated release, giving credit to the reporter if they would so like.

### Bug Bounty Program

<<Coming soon>>

Kinto will launch a Bug Bounty program to encourage security researchers to spend time studying the protocol in order to uncover vulnerabilities. We believe these researchers should get fairly compensated for their time and effort, and acknowledged for their valuable contributions.

### Directly to Kinto

In case of a vulnerability not in the scope of the bug bounty please reach out the team directly.

In these cases, Please submit issues to **all** of the following main points of contact for
security related issues according to the
[initial contact](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#initial-contact)
and [giving details](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#giving-details)
guidelines.

For all security related issues, Kinto has the following main points of contact:

| Contact                | Public key                                                                                                   | Email                             | Key ID                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------ | --------------------------------- | ----------------------------------------------- |
| Security               | [PGP](https://github.com/KintoXYZ/security/blob/master/keys/security.asc)                             | security at kinto.xyz       | 4C0552D8                                      |                              |

Include ALL contacts in your communication, PGP encrypted to ALL parties in the same email.

## Sending Disclosures

In the case where we become aware of security issues affecting other projects that has never affected Kinto, our intention is to inform those projects of security issues on a best effort basis.

In the case where we fix a security issue in Kinto that also affects the following neighboring projects, our intention is to engage in responsible disclosures with them as described in the adopted [standard](https://github.com/RD-Crypto-Spec/Responsible-Disclosure), subject to the deviations described in the deviations [section](#deviations-from-the-standard) of this document.

## Bilateral Responsible Disclosure Agreements

Kinto does not currently have any established bilateral disclosure agreements.

#### Repositories

For exact smart contracts, please check the list at:

- [kinto/smart-contracts](https://github.com/KintoXYZ/kinto-core)

#### Production Contracts

Kinto list of deployed smartcontracts can be found below:

- [Deployments](https://docs.kinto.xyz/kinto-the-safe-l2/building-on-kinto/network-information)

Note: Other contracts, outside of the ones mentioned above, might be considered on a case by case basis, please, reach out to the Kinto development team for clarification.

## Deviations from the Standard

The standard describes reporters of vulnerabilities including full details of an issue, in order to reproduce it. This is necessary for instance in the case of an external researcher both demonstrating and proving that there really is a security issue, and that security issue really has the impact that they say it has - allowing the development team to accurately prioritize and resolve the issue.

In the case of a counterfeiting or fund-stealing bug affecting Kinto, however, we might decide not to include those details with our reports to partners ahead of coordinated release, as long as we are sure that they are not vulnerable.

## More Information

Additional security-related information about Kinto including disclosures, signatures and PGP public keys can be found in the [kinto/security](https://github.com/KintoXYZ/security) repository.

## Credits

Parts of this document were inspired by [Yearn Finance security policy](https://github.com/yearn/yearn-security/master/SECURITY.md), [Babylon Finance](https://github.com/babylon-finance/security), as well as it is inspired by [Grin's security policy](https://github.com/mimblewimble/grin/blob/master/SECURITY.md).
