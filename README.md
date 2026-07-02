# Gramazio Kohler Research — Onboarding

A practical onboarding guide for **Gramazio Kohler Research**, ETH Zürich — accounts, tools, people, and the gotchas the official docs miss.

> Community-maintained — please keep it current for the next person.

## Prerequisites

This guide assumes you have already received the following from ETH:

| Item | Details |
| --- | --- |
| **Global email** | `<username>@ethz.ch` |
| **Department email** | `<username>@arch.ethz.ch` |
| **Global password** | Used for email, NAS, Google/Microsoft logins, etc. |
| **Network password** | Separate password used **only** for Wi-Fi / VPN / Eduroam |

> **Both email addresses point to the same inbox/account.** You do not manage two separate mailboxes.

Every service signs you in as `<username>@ethz.ch` with your **global password**, except **Wi-Fi (Eduroam) and VPN**, which use a role-dependent login and your **network password** (see [Wi-Fi](#31-wi-fi)).

## 1. First day at the office

- Get a **tour of the office**.
- Learn the **food options** on campus.

### 1.1 Food & coffee on campus

_Links open Google Maps; hours & menus shift each semester — see the [live page](https://ethz.ch/en/campus/getting-to-know/cafes-restaurants-shops/gastronomy/restaurants-and-cafeterias/hoenggerberg.html)._

- **[FUSION meal & coffee](https://maps.app.goo.gl/EuoSGRFboac5KGyY7)** — free-flow restaurant (classic/veg, pasta, buffet) + adjacent coffee shop; HCI.
- **[Food Market](https://maps.app.goo.gl/zjg8U73At9AwHuJs8)** — SV counter (pizza/pasta, grill, veg); HPR.
- **[Alumni quattro Lounge](https://maps.app.goo.gl/cGtFkSMN6dCLm8Mj8)** — lounge café.
- **[Rice UP!](https://maps.app.goo.gl/5nKEjqt3zGEhrJY9A)** — Asian rice bowls.
- **[Mendokoro](https://maps.app.goo.gl/wgPFVYDUpktqSjxy7)** — Japanese ramen & snacks, takeaway; HXE.
- **[Restaurant Bellavista](https://maps.app.goo.gl/wWmT2XTKVNs43WGVA)** — table-service restaurant, pricier option.
- **[Coop supermarket](https://maps.app.goo.gl/7Zzzgq639gCaZWWcA)** — on campus.
- **[Street food](https://ethz.ch/en/campus/getting-to-know/cafes-restaurants-shops/gastronomy/street-food.html)** — rotating food trucks, Mon–Fri from 11:00, seasonal (Aug–Dec):
  - **[Stefano-Franscini-Platz](https://maps.app.goo.gl/NMJCScv9bo2ssMJC7)** — coffee & snacks
  - **[Joseph-von-Deschwanden-Platz](https://maps.app.goo.gl/iFgtBzVB6viNLat5A)** — hot meals

| Day | Stefano-Franscini-Platz | Joseph-von-Deschwanden-Platz |
| --- | --- | --- |
| **Mon** | Bar Caffetteria Otter | Caribbean Flair (as of 17.08.) |
| **Tue** | Petit Frère + Äss-Bar | Ada Lokma (Anatolian) + Bra-Bro-Gourmet (burgers, as of 14.09.) |
| **Wed** | Miró Coffee + Äss-Bar (until 11.09.) | Wesley's Kitchen (Asian/momos) |
| **Thu** | Il Macchinista + Äss-Bar (until 11.09.) | Memo Food (kebab) + FAINO (Ukrainian, as of 17.09.) |
| **Fri** | Mate's Coffee + Äss-Bar | Mundo Del Gusto (burgers) |

## 2. Hardware

The group provides your workstation. When yours is being arranged, confirm you get:

- Laptop
- Screen
- Keyboard — check which layout you want (**US / DE / CH**)
- Mouse

## 3. Getting connected

### 3.1 Wi-Fi

Two things trip people up here: your username isn't any of your email addresses, and your password isn't your global password.

**Network** &nbsp;·&nbsp; `eduroam`

**Username** &nbsp;·&nbsp; your ETH username with a **role-specific domain** — *not* `@ethz.ch`:

| Your role | Wi-Fi username |
| --- | --- |
| Staff — professors, assistants, **post-docs**, technical staff | `<username>@staff-net.ethz.ch` |
| Student — incl. **PhD students** | `<username>@student-net.ethz.ch` |
| Visitor | `<username>@eth-visitors.ethz.ch` |

**Password** &nbsp;·&nbsp; your **network password** (Radius / Wi-Fi / VPN password). Set or reset it at <https://password.ethz.ch>.

On Linux and Android, Eduroam needs extra configuration: [Wi-Fi (Linux and Android)](https://unlimited.ethz.ch/en/help/network/manuals-and-documentation/manuals-wlan-wifi/wifi-linux-and-android).

ETH also runs an `eth-iot` network for devices that can't join Eduroam.

More details: <https://isg.inf.ethz.ch/Main/ServicesNetworkWireless>

### 3.2 Email & Calendar

**Outlook** is the recommended email client, it keeps you aligned with the rest of the team. You can use another client if you prefer, but Outlook is the smoothest path.

1. Go to <https://outlook.office.com/mail/>.
2. Enter your `@ethz.ch` email.
3. Sign in with your **global password**.

### 3.3 NAS (storage + website CMS)

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

### 3.4 VPN

Needed to reach some internal services from outside the campus network.

- **Setup** &nbsp;·&nbsp; ETH VPN service page: <https://ethz.ch/staffnet/en/it-services/catalogue/network/vpn.html>
- **Username** &nbsp;·&nbsp; the same role-based login as [Wi-Fi](#31-wi-fi) (e.g. `<username>@student-net.ethz.ch`)
- **Password** &nbsp;·&nbsp; your **network password**

## 4. Software essentials & ecosystem

Slack and GitHub arrive as invites from the team. The Google and Microsoft licenses you request yourself through ETH's **Unlimited** self-service portal: <https://unlimited.ethz.ch/en/help>

### 4.1 Slack

The team will send an invite to your **`@arch.ethz.ch`** address. Accept it to join the group workspace.

### 4.2 GitHub

The team will send an invite to your **`@arch.ethz.ch`** address. Accept it to join the organization, and ask to be added to the project repositories you'll work on.

### 4.3 Google Workspace

1. Follow **"Google Workspace — Getting a License"**: <https://unlimited.ethz.ch/en/help/googlews/getting-started/first-steps>
2. Approval takes about **10 minutes**.
3. Once approved, log in to Google services with your `@ethz.ch` email and **global password**.
4. Ask the team to add you to the **shared project drives**.

### 4.4 Microsoft 365

1. Follow **"Requesting an M365 License"**: <https://unlimited.ethz.ch/en/help/m365/getting-started/m365-first-steps>
2. Approval takes about **5 minutes**.
3. Once approved, you can log in to **Teams** with your `@ethz.ch` email and **global password**.

### 4.5 Zoom

Log in with your `@ethz.ch` email and password; you don't have to request a license.

### 4.6 Rhino

> _TODO: document where the license is requested._

### 4.7 Other tools

- **[Zotero](https://www.zotero.org/)** — reference manager.
- **[ORCiD](https://orcid.org/)** — persistent researcher identifier; worth registering if you'll publish.

### 4.8 Project folders

Set up your **project folder(s)** on the GKR server (NAS) and in the Google Drive shared project drive.

### 4.9 GKR database

Set up a **GKR database** intro meeting with Alessandra Gabaglio.

## 5. Coding

The group's computational stack is Python-centric and built around [COMPAS](https://compas.dev/index.html).

1. Install [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
2. Install a code editor or IDE — [VS Code](https://code.visualstudio.com/) is the common choice.
3. Install Python via **Anaconda**, and get comfortable with virtual environments — one environment per project is the norm.
4. Bookmark the COMPAS resources:
   - [COMPAS documentation](https://compas.dev/index.html)
   - [COMPAS in Rhino](https://compas.dev/compas/latest/gettingstarted/rhino.html)
   - [Tutorials — COMPAS II](https://github.com/compas-teaching/COMPAS-II-FS2023) (FS2023 edition — check whether a newer one exists)
5. Set up a **coding guidelines** intro meeting with Gonzalo Casas or Chen Kasirer.

## 6. Mailing lists & recurring meetings

**Mailing lists:**

- **GKR mailing list** — Tanja adds you.
- **NCCR mailing list** — if your project is part of the NCCR (Digital Fabrication).

**Recurring meetings** — ask to be added to the invites:

- Team meeting
- COMPAS dev meeting (bi-weekly)
- Weekly cross section

## 7. Building access & trainings

- **RFL** (Robotic Fabrication Lab) — request access; the **security training** is required.
- **IDL** (Immersive Design Lab) — request access and training.

> _TODO: document who grants access and how the trainings are scheduled._

## 8. Admin & perks

- **ETHIS** (ETH's administration portal) — where absences are recorded.
  > _TODO: confirm with Tanja whether presence time must be entered as well, or only absences._
- **Halbtax** — SBB half-fare travelcard; request it through Tanja.
- **ETH Group Management (ACLs)** — access to shared resources is tied to ETH group memberships; ask your supervisor to add you to the relevant groups.

## 9. Reading

- Read the **office manual**. _TODO: document where it lives._
- **New PhDs:** read the **PhD study guides** by ETH (received per email).

## Quick checklist

**Arrival & hardware**

- [ ] Office tour + campus food intro
- [ ] Hardware: laptop, screen, keyboard (US/DE/CH), mouse

**Getting connected**

- [ ] Connect to Eduroam (role login, e.g. `@student-net.ethz.ch` + network password)
- [ ] Log in to Outlook (`@ethz.ch` + global password)
- [ ] Access and map the NAS
- [ ] Set up the VPN

**Software & ecosystem**

- [ ] Accept the Slack invite (`@arch.ethz.ch`)
- [ ] Accept the GitHub invite (`@arch.ethz.ch`) and join the project repos
- [ ] Request Google Workspace license + get added to shared drives
- [ ] Request Microsoft 365 license
- [ ] Log in to Zoom (`@ethz.ch` + global password)
- [ ] Request the Rhino license
- [ ] Project folders on the GKR server + Google Drive shared drive
- [ ] GKR database intro with Alessandra Gabaglio

**Coding**

- [ ] Dev environment: git, VS Code, Python/Anaconda, COMPAS links
- [ ] Coding guidelines intro with Gonzalo Casas / Chen Kasirer

**Settling in**

- [ ] GKR mailing list (Tanja); NCCR list if it applies
- [ ] Recurring meeting invites (team, COMPAS dev, cross section)
- [ ] RFL access & security training; IDL access & training
- [ ] ETHIS: clarify absence (and presence?) recording with Tanja
- [ ] Halbtax request (Tanja)
- [ ] Get added to the ETH groups (ACLs)
- [ ] Read the office manual
- [ ] (PhDs) Read the ETH PhD study guides

---

## Who is who

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
