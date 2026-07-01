# Gramazio Kohler — ETH Zürich Onboarding

A practical setup guide for **Gramazio Kohler Research**, ETH Zürich (D-ARCH), covering the gotchas the official docs miss.

> Community-maintained — please keep it current for the next person.

## Prerequisites

This guide assumes you have already received the following from ETH:

| Item | Details |
| --- | --- |
| **Global email** | `<username>@ethz.ch` |
| **Department email** | `<username>@arch.ethz.ch` (Department of Architecture) |
| **Global password** | Used for email, NAS, Google/Microsoft logins, etc. |
| **Network password** | Separate password used **only** for Wi-Fi / Eduroam |

> **Both email addresses point to the same inbox/account.** You do not manage two separate mailboxes.

You will use slightly different usernames depending on the service. This is the single most common source of confusion, so here’s a quick reference:

| Where | Username | Password |
| --- | --- | --- |
| Outlook / email | `<username>@ethz.ch` | Global password |
| NAS | `<username>@ethz.ch` | Global password |
| Google Workspace / Microsoft 365 | `<username>@ethz.ch` | Global password |
| **Wi-Fi (Eduroam)** | role-dependent login (see [Wi-Fi](#2-wi-fi-eduroam)) | **Network password** |

## 1. Email (Outlook)

**Outlook** is the recommended email client, it keeps you aligned with the rest of the team. You can use another client if you prefer, but Outlook is the smoothest path.

1. Go to <https://outlook.office.com/mail/>.
2. Enter your `@ethz.ch` email.
3. You'll be redirected to the ETH login page — sign in with your **global password**.

## 2. Wi-Fi (Eduroam)

Wi-Fi is available in all ETH buildings (provided by ITS) and always requires authentication. The catch: your Wi-Fi username follows a **different format** that depends on your relation to ETH — not your plain `@ethz.ch` address. Take your ETH user name and add the role-specific segment before `ethz.ch`:

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
3. Once approved, you can log in to **Teams** with your `@ethz.ch` email and **global password**.

## Quick checklist

- [ ] Connect to Eduroam (role login, e.g. `@student-net.ethz.ch` + network password)
- [ ] Log in to Outlook (`@ethz.ch` + global password)
- [ ] Access and map the NAS
- [ ] Accept the Slack invite (`@arch.ethz.ch`)
- [ ] Accept the GitHub invite (`@arch.ethz.ch`)
- [ ] Request Google Workspace license
- [ ] Request Microsoft 365 license
