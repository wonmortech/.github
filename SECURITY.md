# Security policy

This policy mirrors the [security and disclosure page](https://wonmor.io/security/) on wonmor.io, which is the source of truth. If the two ever differ, the page on wonmor.io applies.

It covers every repository in the `wonmortech` organization, bitg and the other dtwin products, and wonmor.io.

## How to report

Please do not report vulnerabilities in public issues, pull requests, discussions or group chats. Use one of these private channels:

| Where the problem is | How to report |
|---|---|
| bitg | GitHub private vulnerability reporting: [github.com/dtwinuz/bitg/security/advisories/new](https://github.com/dtwinuz/bitg/security/advisories/new) |
| Any other public repository in [github.com/dtwinuz](https://github.com/dtwinuz) or in this organization | The repository's Security tab, then "Report a vulnerability" |
| A product without a public repository, a live site, or wonmor.io | A private message on Telegram to [t.me/xnosir](https://t.me/xnosir) |

On Telegram, a short first message is enough, for example "Security report for dtwin.uz". We will reply and agree on how to share the details safely. Never send live credentials or other people's personal data, even as proof.

A machine-readable version of these contacts is published at [wonmor.io/.well-known/security.txt](https://wonmor.io/.well-known/security.txt).

## What to include

- the affected product, URL or repository, and the version or release, if you know it;
- the platform: operating system, browser or app;
- the steps to reproduce, or a minimal proof of concept;
- what an attacker could gain: which data or which permission is at risk;
- whether you have shared the issue with anyone else, and any date by which you plan to publish.

You do not need to have a fix. A clear description is more useful than a long one.

## What happens next

We use the timeline from the bitg security policy for every product. Where a repository's own SECURITY.md promises a shorter time, the shorter time applies.

| Step | What we do | Within |
|---|---|---|
| Acknowledge | Confirm we received your report | 7 days |
| Assess | Reproduce it and rate its severity (CVSS) | 14 days |
| Fix | Fix and release high and critical issues, sooner where possible | 60 days |
| Disclose | Publish a security advisory, and a CVE where needed, with the fixed release | With the fix |

While we work on a fix, you are welcome to take part in the private advisory on GitHub, or in the Telegram conversation for products without a public repository. We will tell you if we need more time and why. Medium and low severity issues are fixed in a normal release; we will tell you which one.

For products installed on your own machine, fixes go to the latest release. For live sites, the fix is deployed to the site and no update is needed on your side.

## Safe harbour for good-faith research

We will not pursue or support legal action against you for security research that follows these rules:

- you act in good faith to find and report a vulnerability, not to cause harm or gain an advantage;
- you access only the data you need to show the problem, stop as soon as you reach other people's data, and do not keep, copy or share it;
- you do not degrade our services or anyone else's use of them;
- you give us reasonable time to fix the issue before you publish, following the timeline above;
- you test only against accounts you own or have permission to use.

If you are unsure whether something is allowed, ask us first through the channels above. If someone else takes legal action against you for research that followed this policy, we will say publicly that your work was authorised by us.

## Out of scope

- denial-of-service attacks, load or stress testing, and anything that floods a service with traffic;
- social engineering or phishing of the founder, contributors or users;
- spam, including through contact forms, bots or support desks;
- physical attacks on equipment;
- reports from automated scanners with no demonstrated impact;
- problems in services we do not run, such as GitHub or Telegram. Please report those to their owners.

## Credit

Once a fix is released, we credit you by name or handle in the security advisory, if you would like that. If you prefer to stay anonymous, we respect that. We do not run a paid bug bounty: Wonmor is self-funded and we would rather make no promise than one we cannot keep.

## What we do not publish

To keep users safe, we do not publish details of unfixed vulnerabilities, our server addresses or other infrastructure details. Fixed vulnerabilities are described in advisories with enough detail for users to understand their risk.
