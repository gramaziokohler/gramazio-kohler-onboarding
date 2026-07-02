# Gramazio Kohler — ETH Zürich Onboarding

A practical onboarding guide for **Gramazio Kohler Research**, ETH Zürich (D-ARCH) — accounts, tools, people, and the gotchas the official docs miss.

> Community-maintained — please keep it current for the next person.
> Parts of this guide were merged from the group's [Notion onboarding notes](https://marble-forest-5bf.notion.site/On-boarding-new-employees-8609a941976143468566c7198cac579e).

## Prerequisites

This guide assumes you have already received the following from ETH:

| Item | Details |
| --- | --- |
| **Global email** | `<username>@ethz.ch` |
| **Department email** | `<username>@arch.ethz.ch` (Department of Architecture) |
| **Global password** | Used for email, NAS, Google/Microsoft logins, etc. |
| **Network password** | Separate password used **only** for Wi-Fi / VPN / Eduroam |

> **Both email addresses point to the same inbox/account.** You do not manage two separate mailboxes.

You will use slightly different usernames depending on the service. A reference specific to this onboarding:

| Where | Username | Password |
| --- | --- | --- |
| Outlook / email | `<username>@ethz.ch` | Global password |
| NAS | `<username>@ethz.ch` | Global password |
| Google Workspace / Microsoft 365 | `<username>@ethz.ch` | Global password |
| **Wi-Fi (Eduroam) / VPN** | role-dependent login (see [Wi-Fi](#2-wi-fi-eduroam)) | **Network password** |

## 1. Hardware

The group provides your workstation. When yours is being arranged, confirm you get:

- Laptop
- Screen
- Keyboard — check which layout you want (**US / DE / CH**)
- Mouse

## 2. Wi-Fi (Eduroam)

Two things trip people up here: your username isn't any of your email addresses, and your password isn't your global password.

**Network** &nbsp;·&nbsp; `eduroam`

**Username** &nbsp;·&nbsp; your ETH username with a **role-specific domain** — *not* `@ethz.ch`:

| Your role | Wi-Fi username |
| --- | --- |
| Staff — professors, assistants, **post-docs**, technical staff | `<username>@staff-net.ethz.ch` |
| Student — incl. **PhD students** | `<username>@student-net.ethz.ch` |
| Visitor | `<username>@eth-visitors.ethz.ch` |

**Password** &nbsp;·&nbsp; your **network password** (Radius / Wi-Fi / VPN password). Set or reset it at <https://password.ethz.ch>.

On Android, Eduroam needs extra configuration: [Eduroam Wi-Fi on Android](https://readme.phys.ethz.ch/network/eduroam_wifi_on_android/).

ETH also runs an `eth-iot` network for devices that can't join Eduroam.

More details: <https://isg.inf.ethz.ch/Main/ServicesNetworkWireless>

## 3. Email & Calendar

**Outlook** is the recommended email client, it keeps you aligned with the rest of the team. You can use another client if you prefer, but Outlook is the smoothest path.

1. Go to <https://outlook.office.com/mail/>.
2. Enter your `@ethz.ch` email.
3. Sign in with your **global password**.

## 4. NAS (storage + website CMS)

The NAS serves a dual purpose:

- **Storage** for the group's files.
- **Content Management System (CMS)** for the group website: <https://gramaziokohler.arch.ethz.ch/>

> _TODO: document how the CMS workflow works (how content on the NAS maps to the published website)._

Once you're connected via Eduroam, you can reach the group NAS:

```
\\nas22.ethz.ch\arch_ita_gramazio_kohler
```

**On Windows:**

> ⚠️ **The first connection is slow and silent** — No feedback for ~2 minutes.

1. Open **File Explorer** and enter the address above and _wait_.
2. Click  **More choices**. Don't accept the default account. 
<figure>
  <img src="./nas-credentials-1.jpg" alt="Enter network credentials dialog defaulting to the network account" width="400" />
  <figcaption><em>2a. The dialog opens pre-filled with your <strong>network account</strong>, which the NAS rejects. Click <strong>More choices</strong> at the bottom.</em></figcaption>
</figure>

<br />

<figure>
  <img src="./nas-credentials-2.jpg" alt="Credentials dialog expanded with Use a different account option" width="400" />
  <figcaption><em>2b. Select <strong>Use a different account</strong>.</em></figcaption>
</figure>

<br />

<figure>
  <img src="./nas-credentials-3.jpg" alt="Credentials dialog filled with global email and password" width="400" />
  <figcaption><em>2c. Enter your <strong>global</strong> email and password, then tick <strong>Remember my credentials</strong> so you're not asked again.</em></figcaption>
</figure>

3. **(Recommended)** Map it as a network drive so it stays available and reconnects at sign-in.

<figure>
  <img src="./map-network-drive-1.jpg" alt="This PC context menu with Map network drive highlighted" width="550" />
  <figcaption><em>3a. At <strong>This PC</strong>, click the three dots (…) and select <strong>Map network drive</strong>.</em></figcaption>
</figure>

<br />

<figure>
  <img src="./map-network-drive-2.jpg" alt="Map Network Drive dialog with drive letter and folder path" width="550" />
  <figcaption><em>3b. Fill in the dialog:</em>
    <ul>
      <li>In <strong>Drive</strong>, select the letter <code>M:</code> (or any other available letter).</li>
      <li>In <strong>Folder</strong>, enter <code>\\nas22.ethz.ch\arch_ita_gramazio_kohler</code>.</li>
      <li>Check <strong>Reconnect at sign-in</strong>.</li>
      <li>Check <strong>Connect using different credentials</strong>.</li>
    </ul>
  </figcaption>
</figure>

<br />

<figure>
  <img src="./map-network-drive-3.jpg" alt="Windows Security dialog to enter network credentials" width="400" />
  <figcaption><em>3c. Enter your global email and password.</em></figcaption>
</figure>

> _TODO: add macOS and Linux instructions._

## 5. Slack

The team will send an invite to your **`@arch.ethz.ch`** address. Accept it to join the group workspace.

## 6. GitHub

The team will send an invite to your **`@arch.ethz.ch`** address. Accept it to join the organization, and ask to be added to the project repositories you'll work on.

## 7. Software & licenses

Request the Google Workspace and Microsoft 365 licenses through ETH's **Unlimited** self-service portal: <https://unlimited.ethz.ch/en/help>

### Google Workspace

1. Follow **"Google Workspace — Getting a License"**: <https://unlimited.ethz.ch/en/help/googlews/getting-started/first-steps>
2. Approval takes about **10 minutes**.
3. Once approved, log in to Google services with your `@ethz.ch` email and **global password**.
4. Ask the team to add you to the **shared project drives**.

### Microsoft 365

1. Follow **"Requesting an M365 License"**: <https://unlimited.ethz.ch/en/help/m365/getting-started/m365-first-steps>
2. Approval takes about **5 minutes**.
3. Once approved, you can log in to **Teams** with your `@ethz.ch` email and **global password**.

### Zoom

Log in with your `@ethz.ch` email and password; it doesn't require a license.

### Rhino

The group's main CAD environment. It needs a license.

> _TODO: document where the license is requested._

### Other tools

- **Zotero** — reference manager.
- **ORCiD** — persistent researcher identifier; worth registering if you'll publish.

## 8. VPN

Needed to reach some internal services from outside the campus network.

- **Setup** &nbsp;·&nbsp; ETH VPN service page: <https://ethz.ch/staffnet/en/it-services/catalogue/network/vpn.html>
- **Username** &nbsp;·&nbsp; the same role-based login as [Wi-Fi](#2-wi-fi-eduroam) (e.g. `<username>@student-net.ethz.ch`)
- **Password** &nbsp;·&nbsp; your **network password**

## 9. Development environment

The group's computational stack is Python-centric and built around [COMPAS](https://compas.dev/index.html).

1. Install [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
2. Install a code editor or IDE — [VS Code](https://code.visualstudio.com/) is the common choice.
3. Install Python via **Anaconda**, and get comfortable with virtual environments — one environment per project is the norm.
4. Bookmark the COMPAS resources:
   - [COMPAS documentation](https://compas.dev/index.html)
   - [COMPAS in Rhino](https://compas.dev/compas/latest/gettingstarted/rhino.html)
   - [Tutorials — COMPAS II](https://github.com/compas-teaching/COMPAS-II-FS2022) (FS2022 edition — check whether a newer one exists)
5. Set up a **coding guidelines** intro meeting with Gonzalo Casas or Chen Kasirer.

## 10. Building access & trainings

- **RFL** (Robotic Fabrication Lab) — request access; the **security training** is required.
- **IDL** (Immersive Design Lab) — request access and training.

> _TODO: document who grants access and how the trainings are scheduled._

## 11. Admin & perks

- **ETHIS** (ETH's administration portal) — where absences are recorded.
  > _TODO: confirm with Tanja whether presence time must be entered as well, or only absences._
- **Halbtax** — SBB half-fare travelcard; request it through Tanja.
- **ETH Group Management (ACLs)** — access to shared resources is tied to ETH group memberships; ask your supervisor to add you to the relevant groups.

## 12. Mailing lists & recurring meetings

**Mailing lists:**

- **GKR mailing list** — Tanja adds you.
- **NCCR mailing list** — if your project is part of the NCCR (Digital Fabrication).

**Recurring meetings** — ask to be added to the invites:

- Team meeting
- COMPAS dev meeting (bi-weekly)
- Weekly cross section

## 13. First days

Things to do and set up during your first days:

- Get a **tour of the office**.
- Learn the **food options** on campus (food markets and food trucks).
- Read the **office manual**. _TODO: document where it lives._
- Set up a **GKR database** intro meeting with Alessandra Gabaglio.
- Set up your **project folder(s)** on the GKR server (NAS) and in the Google Drive shared project drive.

**For new PhDs:**

- Read the **PhD study guides** by ETH (received per email).

## 14. Who is who

First contacts by topic.

> ⚠️ _This roster comes from notes last edited in 2022 — verify who currently holds each role._

| Where | Role | People |
| --- | --- | --- |
| **GKR** | Admin & finance | Tanja |
| **GKR** | Postdocs | Oliver, Lauren, Petrus, Ines, Ania |
| **GKR** | PR & communication | Alessandra |
| **GKR** | Teaching team, assistants | _TODO_ |
| **NCCR** | Management | Russell, Kaitlin, Blanca |
| **NCCR** | Budget & expenses | Tanja, Blanca |
| **NCCR** | Software ecosystem | Tom, Chen, Gonzalo |
| **RFL** | Lab team | Philippe, Mike, Toby |
| **ITA** | Coordinator, RQEs | _TODO_ |

## Quick checklist

**Accounts & access**

- [ ] Connect to Eduroam (role login, e.g. `@student-net.ethz.ch` + network password)
- [ ] Log in to Outlook (`@ethz.ch` + global password)
- [ ] Access and map the NAS
- [ ] Accept the Slack invite (`@arch.ethz.ch`)
- [ ] Accept the GitHub invite (`@arch.ethz.ch`) and join the project repos
- [ ] Request Google Workspace license + get added to shared drives
- [ ] Request Microsoft 365 license
- [ ] Log in to Zoom (`@ethz.ch` + global password)
- [ ] Request the Rhino license
- [ ] Set up the VPN
- [ ] Get added to the ETH groups (ACLs)

**Workspace**

- [ ] Hardware: laptop, screen, keyboard (US/DE/CH), mouse
- [ ] Dev environment: git, VS Code, Python/Anaconda, COMPAS links

**Admin & people**

- [ ] ETHIS: clarify absence (and presence?) recording with Tanja
- [ ] Halbtax request (Tanja)
- [ ] GKR mailing list (Tanja); NCCR list if it applies
- [ ] Recurring meeting invites (team, COMPAS dev, cross section)
- [ ] RFL access & security training; IDL access & training
- [ ] Office tour + campus food intro
- [ ] Read the office manual
- [ ] GKR database intro with Alessandra Gabaglio
- [ ] Coding guidelines intro with Gonzalo Casas / Chen Kasirer
- [ ] Project folders on the GKR server + Google Drive shared drive
- [ ] (PhDs) Read the ETH PhD study guides
