# Gramazio Kohler — ETH Zürich Onboarding

A practical, step-by-step guide for getting set up at **Gramazio Kohler Research**, ETH Zürich (Institute of Technology in Architecture, D-ARCH). It captures the small gotchas that aren't obvious from the official docs, so the next person has a smoother start than the last.

> This guide is community-maintained. If something is out of date or unclear, please update it for the next person.

## Prerequisites

This guide assumes you have already received the following from ETH / the team:

| Item | Details |
| --- | --- |
| **Global email** | `<username>@ethz.ch` |
| **Department email** | `<username>@arch.ethz.ch` (Department of Architecture) |
| **Global password** | Used for email, NAS, Google/Microsoft logins, etc. |
| **Network password** | Separate password used **only** for Wi-Fi / Eduroam |

> **Both email addresses point to the same inbox/account.** You do not manage two separate mailboxes.

## Your ETH identities at a glance

You will use slightly different usernames depending on the service. This is the single most common source of confusion, so keep this table handy:

| Where | Username | Password |
| --- | --- | --- |
| Outlook / email | `<username>@ethz.ch` | Global password |
| NAS | `<username>@ethz.ch` | Global password |
| Google Workspace / Microsoft 365 | `<username>@ethz.ch` | Global password |
| **Wi-Fi (Eduroam)** | role-dependent alias (see [Wi-Fi](#2-wi-fi-eduroam)) | **Network password** |

## 1. Email (Outlook)

To stay on the same page as the rest of the team, use **Outlook** (not another mail client).

1. Go to <https://outlook.office.com/mail/>.
2. Enter your `@ethz.ch` email.
3. You'll be redirected to the ETH login page — sign in with your **global password**.

## 2. Wi-Fi (Eduroam)

Wi-Fi is available in all ETH buildings (provided by ITS) and always requires authentication. The catch: your Wi-Fi username is a **third alias** that depends on your relation to ETH — not your plain `@ethz.ch` address. Take your ETH user name and add the role-specific segment before `ethz.ch`:

| Your role | Wi-Fi username |
| --- | --- |
| Staff (professors, assistants, **post-docs**, technical staff) | `<username>@staff-net.ethz.ch` |
| Student (incl. **PhD students**) | `<username>@student-net.ethz.ch` |
| Visitor | `<username>@eth-visitors.ethz.ch` |

- **Password:** your **network password** (a.k.a. Radius / WIFI / VPN password) — **not** your global password. You can set it at <https://password.ethz.ch>.

More details: <https://isg.inf.ethz.ch/Main/ServicesNetworkWireless>

## 3. NAS (storage + website CMS)

Once you're connected via Eduroam, you can reach the group NAS:

```
\\nas22.ethz.ch\arch_ita_gramazio_kohler
```

**On Windows:**

1. Open **File Explorer** and enter the address above.
2. When prompted, sign in with:
   - **Username:** `<username>@ethz.ch`
   - **Password:** your **global password**
3. (Recommended) Use **Map network drive** for quick access in the future.

![Map network drive dialog](./map-network-drive.jpg)

The NAS serves a dual purpose:

- **Storage** for the group's files.
- **Content Management System (CMS)** for the group website: <https://gramaziokohler.arch.ethz.ch/>

> ⚠️ _TODO: document how the CMS workflow works (how content on the NAS maps to the published website)._

## 4. Slack

The team will send an invite to your **`@arch.ethz.ch`** address. Accept it to join the group workspace.

## 5. GitHub

The team will send an invite to your **`@arch.ethz.ch`** address. Accept it to join the organization.

## 6. Google Workspace & Microsoft 365 licenses

Request your licenses through ETH's **Unlimited** self-service portal: <https://unlimited.ethz.ch/en/help>

### Google Workspace

1. Follow **"Google Workspace — Getting a License"**: <https://unlimited.ethz.ch/en/help/googlews/getting-started/first-steps>
2. Approval takes about **10 minutes**.
3. Once approved, log in to Google services with your `@ethz.ch` email and **global password**.

### Microsoft 365

1. Follow **"Requesting an M365 License"**: <https://unlimited.ethz.ch/en/help/m365/getting-started/m365-first-steps>
2. Approval takes about **5 minutes**.

## Quick checklist

- [ ] Log in to Outlook (`@ethz.ch` + global password)
- [ ] Connect to Eduroam (role alias, e.g. `@student-net.ethz.ch` + network password)
- [ ] Access and map the NAS
- [ ] Accept the Slack invite (`@arch.ethz.ch`)
- [ ] Accept the GitHub invite (`@arch.ethz.ch`)
- [ ] Request Google Workspace license
- [ ] Request Microsoft 365 license
