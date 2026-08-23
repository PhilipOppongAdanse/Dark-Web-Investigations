# Dark-Web-Investigations
## Dark Web Vendor Profiling & OSINT Correlation

This investigation focuses on profiling a vendor operating on a dark web marketplace and identifying publicly available information associated with usernames observed during the investigation.

The purpose of this exercise was to demonstrate how investigators can combine dark web intelligence gathering with open-source intelligence (OSINT) techniques to build an intelligence profile while remaining within legal and ethical boundaries.

---

# Table of Contents

- Investigation Overview
- Objectives
- Scope
- Tools Used
- Phase 1: Marketplace Reconnaissance
- Phase 2: Vendor Profiling
- Phase 3: Username Pivoting
- Phase 4: Social Media Correlation
- Phase 5: Public Footprint Analysis
- Findings
- Attribution Assessment
- Limitations
- Conclusion
- Disclaimer

---

# Investigation Overview

During this investigation, a vendor profile identified as **Blacknoir001** was located on a dark web marketplace.

The vendor appeared to be actively selling products and maintained an established reputation within the marketplace ecosystem.

The investigation focused on:

1. Vendor profiling
2. Username enumeration
3. Public footprint discovery
4. Correlation of publicly available accounts
5. Attribution assessment

No intrusive techniques were used during this investigation.

---

# Objectives

The objectives of this investigation were:

- Identify vendor information available on the marketplace
- Collect observable marketplace intelligence
- Pivot using discovered usernames
- Search for matching usernames across public platforms
- Determine whether publicly available accounts could be associated with the observed vendor identity
- Document findings using a structured methodology

---

# Scope

The investigation was limited to:

- Dark web marketplace observations
- Publicly accessible websites
- Open-source intelligence collection
- Username correlation

No account access attempts were performed.

No authentication bypasses were conducted.

No exploitation activities were performed.

---

# Tools Used

| Tool | Purpose |
|--------|---------|
| Tor Browser | Dark web access |
| Kali Linux | Investigation platform |
| SpiderFoot | Automated OSINT collection |
| DuckDuckGo | Public search correlation |
| GitHub | Repository discovery |
| YouTube | Channel discovery |
| Pinterest | Username correlation |
| Telegram | Username verification |

---

# Phase 1: Marketplace Reconnaissance

## Tor Browser Configuration

The investigation began by launching Tor Browser within Kali Linux and establishing a secure connection to the Tor network.

![Kali Config Tor Browser](./Evidence/01-Kali-Config-Tor-Browser.png)

![Establishing Tor Connection](./Evidence/02-Establishing-Tor-Connection.png)

![Tor Browser Established](./Evidence/03-Tor-Browser-Established.png)

Successful connection to the Tor network was confirmed before beginning any investigative activities.

---

## Hidden Service Discovery

Open-source dark web directories were used to locate accessible onion services.

![Hidden Wiki Search](./Evidence/04-Hidden-Wiki-Search.png)

![Private Savy Opened](./Evidence/05-Private-Savy-Opened.png)

![Onion Site List](./Evidence/06-Onion-Site-List.png)

Multiple onion resources were identified and reviewed to locate active marketplaces and vendor profiles suitable for investigation.

---

## Marketplace Access

An account was created and authenticated to access marketplace resources.

![Awazon Market Registration](./Evidence/07-Awazon-Market-Registration.png)

![Awazon Market Login](./Evidence/08-Awazon-Market-Login.png)

![Awazon Market Homepage](./Evidence/09-Awazon-Market-Homepage.png)

The marketplace environment was successfully accessed, allowing further vendor reconnaissance activities.

---

# Phase 2: Vendor Profiling

## Vendor Discovery

A vendor operating under the alias **Blacknoir001** was identified.

![Drug Vendor Page](./Evidence/10-Drug-Vendor-Page.png)

![Drug Vendor Profile](./Evidence/11-Drug-Vendor-Profile.png)

### Observations

- Established vendor profile
- Active marketplace presence
- Multiple product listings
- Historical transaction activity
- Positive marketplace reputation indicators

The profile appeared active and maintained a visible history within the marketplace ecosystem.

---

# Phase 3: Username Pivoting

## Telegram Enumeration

The username identified on the marketplace was used as the basis for OSINT pivoting.

![Vendor Telegram Search](./Evidence/12-Vendor-Telegram-Search.png)

The search revealed multiple Telegram accounts using similar naming conventions.

![Vendor Telegram Profile 01](./Evidence/13-Vendor-Telegram-Profile-01.png)

![Vendor Telegram Profile 02](./Evidence/14-Vendor-Telegram-Profile-02.png)

### Usernames Observed

- @blacknoir001
- @blacknoir001USA

The discovery suggested potential reuse of the marketplace alias outside the dark web environment.

---

# Phase 4: Social Media Correlation

## SpiderFoot Analysis

SpiderFoot was used to automate username correlation across multiple public platforms.

![Spiderfoot Username Search Vendor](./Evidence/15-Spiderfoot-Username-Search-Vendor.png)

![Spiderfoot Username Search Matches](./Evidence/16-Spiderfoot-Username-Search-Matches.png)

![Spiderfoot Username Results](./Evidence/17-Spiderfoot-Username-Results.png)

The tool identified multiple online services associated with the observed username.

---

## Search Engine Correlation

Additional searches were performed to validate SpiderFoot findings.

![Vendor Google Name Search](./Evidence/18-Vendor-Google-Name-Search.png)

Public search results revealed several accounts using the same alias across different platforms.

---

# Phase 5: Public Footprint Analysis

## Pinterest

A Pinterest account using the username was identified.

![Vendor Pinterest](./Evidence/19-Vendor-Pinterest.png)

---

## GitHub

A GitHub account using the same alias was discovered.

![Vendor Github](./Evidence/20-Vendor-Github.png)

---

## YouTube

A YouTube channel utilizing the same username was identified.

![Vendor Youtube](./Evidence/21-Vendor-Youtube.png)

---

# Findings

1. A vendor operating under the alias **Blacknoir001** was identified on a dark web marketplace.

2. Multiple public accounts utilizing the same username were discovered.

3. Telegram profiles matching the alias were identified.

4. SpiderFoot successfully correlated the username across multiple online platforms.

5. Public profiles were discovered on Pinterest, GitHub, and YouTube.

6. The investigation demonstrated consistent username reuse across different environments.

7. No definitive real-world attribution was established.

---

# Attribution Assessment

The investigation identified several accounts utilizing the same alias across multiple platforms.

While this demonstrates username reuse and creates investigative leads, the available evidence is insufficient to conclusively attribute ownership of all discovered accounts to a single individual.

Confidence Level: **Low to Moderate**

---

# Limitations

- Reliance on publicly available information
- Potential username impersonation
- Limited profile activity
- Absence of corroborating identity evidence

---

# Conclusion

This investigation demonstrated how dark web reconnaissance and OSINT techniques can be combined to identify and profile online personas.

The vendor known as **Blacknoir001** maintained a marketplace presence and appeared to reuse the same alias across several publicly accessible platforms. While attribution was not possible based on the available evidence alone, multiple investigative leads were identified for future research.

---

# Disclaimer

This investigation was conducted exclusively using publicly available information and open-source intelligence techniques for educational, research, and digital forensics training purposes.

No unauthorized access, exploitation, intrusion, or circumvention of security controls was performed during this investigation.

The appearance of a username on multiple platforms does not constitute proof of ownership or identity. All findings should be treated as investigative leads requiring independent verification before attribution conclusions are made.
