This page is a running list of Open Source Operating Systems and Software (Linux & *BSD distributions, system components, etc.) and what their current status is regarding age verification.

There are several locales which have laws (in various stages) which require Operating Systems and their software components to perform some level of age verification and reporting.

Passed OS-Level Age Verification Laws: [Brazil](https://x.com/lundukejournal/status/2033927808196481101), & [California](https://x.com/lundukejournal/status/2026783141298360692).

Proposed OS-Level Age Verification Laws: [Colorado](https://x.com/lundukejournal/status/2026331487499370988), [Illinois](https://x.com/lundukejournal/status/2031047619225493597), & [New York](https://x.com/lundukejournal/status/2029081398577922173?s=61).

### Operating Systems Not Implementing Age Verification

The developers or publishers of these open source Operating Systems have decided to not implement Age Verification, or are currently restricting access in regions with Age Verification laws.

| &nbsp; | Operating System | Notes |
| - | - | - |
| :no_entry: | **Omarchy Linux** | [Developer statement](https://x.com/lundukejournal/status/2029580164498108846) |
| :no_entry: | **Devuan Linux** | [Developer statement](https://x.com/lundukejournal/status/2034697759291310115) |
| :no_entry: | **Vendefoul Wolf Linux** | [Developer statement 1](https://x.com/lundukejournal/status/2035390136356077822), [2](https://x.com/vendefoulwolf/status/2035441292520386852) |
| :no_entry: | **GrapheneOS** | Android-based mobile OS, [Developer statement](https://x.com/lundukejournal/status/2035073741613338964) |
| :no_entry: | **FreeDOS** | [Developer statement](https://x.com/lundukejournal/status/2034770975309361583) |
| :no_entry: | **Artix Linux** | [Developer statement](https://x.com/lundukejournal/status/2034776326901555488) |
| :no_entry: | **DB48X** | Calculator firmware, [Developer statement](https://x.com/lundukejournal/status/2027358439991615715) |
| :no_entry: | **Arch Linux 32** | [Developer forbids usage in Brazil, California](https://x.com/lundukejournal/status/2033896030178029675) |
| :no_entry: | **Ageless Linux** | [Debian fork created to protest Age Verification](https://x.com/lundukejournal/status/2032951803134837237) |
| :no_entry: | **Vendefoul Wolf Linux** | [Developer statement](https://x.com/vendefoulwolf/status/2035298946554180032) |
| :no_entry: | **Adenix GNU/Linux** | [Developer statement opposing age verification](https://www.adenixgnulinux.org/) — founder also posted to the [Debian debian-legal mailing list](https://lists.debian.org/debian-legal/2026/03/msg00022.html) requesting mechanisms to remove age verification packages and blacklist affected regions; raises constitutional and free speech concerns |
| :no_entry: | **Garuda Linux** | [Community statement opposing age verification](https://forum.garudalinux.org/t/a-statement-on-age-verification-the-state-of-the-community-discourse/47652) — official forum post addressing the state of community discourse; project opposed to implementing age verification |
| :speech_balloon: | **Bazzite** | Brazil block was applied by mistake and not intentional; [official clarification on X](https://x.com/bazzite_gg/status/2034286537723007222); no official position on age verification adopted |

### Operating Systems Planning to Implement Age Verification

The developers or publishers of these Open Source Operating Systems have made plans and/or statements that they intend to comply with new Age Verification laws.  But, as yet, that Age Verfication functionality is not fully implemented.

| &nbsp; | Operating System | Notes |
| - | - | - |
| :building_construction: | **Ubuntu** | [Planning Discussion](https://lists.ubuntu.com/archives/ubuntu-devel/2026-March/043510.html), [Ubuntu VP Statement](https://x.com/lundukejournal/status/2029198322309681311) |
| :building_construction: | **Pop!_OS** | [System76 Statement opposing, but planning to implement](https://blog.system76.com/post/system76-on-age-verification) |
| :building_construction: | **elementary OS** | [Founder Statement planning to implement](https://mastodon.social/@danirabbit@mastodon.online/116250766314705297) |
| :building_construction: | **Whonix / Kicksecure** | [Forum discussion](https://forums.whonix.org/t/whonix-adding-age-verification/22969) — actively investigating compliance while prioritizing privacy; researching age-bracket API approach that avoids storing full birth dates; no implementation yet, team committed to announcing before any changes affect users |

### Operating Systems With Ongoing Discussions (No Decision Yet)

The developers or publishers of these Operating Systems have active community or developer discussions about Age Verification laws but have not yet made an official decision.

| &nbsp; | Operating System | Notes |
| - | - | - |
| :speech_balloon: | **NixOS** | [Community discussion](https://discourse.nixos.org/t/compliance-with-u-s-age-verification-laws/75791) — contributors skeptical NixOS will implement verification independently without a standardized ecosystem-wide approach; no official position adopted |
| :speech_balloon: | **Fedora** | [Community discussion](https://discussion.fedoraproject.org/t/a-practical-architectural-solution-to-os-level-age-verification-laws/183387) — proposal to make networking an optional patch to avoid triggering regulatory requirements; community raises technical concerns; coordinating cross-distro solutions with openSUSE; no official position adopted |
| :speech_balloon: | **Debian** | [debian-legal mailing list](https://lists.debian.org/debian-legal/2026/03/msg00022.html) — Adenix GNU/Linux founder (March 4, 2026) states his distros will not implement age checks and requests mechanisms to remove age verification packages and blacklist affected regions (California, Colorado); raises constitutional and free speech concerns; no official Debian project position adopted |
| :speech_balloon: | **EndeavourOS** | [Developer comment](https://www.gamingonlinux.com/2026/03/endeavouros-titan-released-devs-comment-on-age-verification-laws/) — acknowledge complexity, lack resources for independent compliance; called on OSI, FSF, and Linux Foundation to take a stance |
| :speech_balloon: | **OpenMandriva** | No official position adopted yet; project is considering multiple approaches to dealing with what they characterize as "stupid, dumb, and evil" age verification laws; opposed to implementation |

### Operating Systems Which Have Already Implemented Age Verification

| &nbsp; | Operating System | Notes |
| - | - | - |
| :white_check_mark: | **MidnightBSD** | [Age verification daemon added](https://github.com/MidnightBSD/src/commit/6e4e5dfb3270f05d35e2c24bf152662c30acbdf7) — `ageverifd` daemon committed to the base system; previously had [license temporarily forbidding usage in Brazil and California](https://github.com/MidnightBSD/src?tab=License-1-ov-file) [until implementation finished](https://x.com/midnightbsd/status/2030992394703732872) |

---

## Other Open Source Software

Age verification is not limited to full Operating Systems. System-level components and desktop infrastructure projects are also beginning to implement or plan support for age verification.

### Software With Ongoing Discussions (No Decision Yet)

| &nbsp; | Software | Notes |
| - | - | - |
| :speech_balloon: | **F-Droid** | No official statement on California AB-1043, Brazil Lei 15.211, or Colorado SB26-051; internal GitLab issues discuss segregating adult content to a separate repository; [forum thread on EU age verification laws](https://forum.f-droid.org/t/european-internet-age-verification-law/33098); legal analysis suggests F-Droid may fall outside scope as a nonprofit FOSS project; broader [legal resilience initiative](https://f-droid.org/2025/08/04/strengthening-f-droids-legal-resilience-introducing-the-research-series.html) underway; notably F-Droid published an [open letter opposing Google's mandatory developer identity verification](https://f-droid.org/en/2026/02/24/open-letter-opposing-developer-verification.html) requirement (effective September 2026) — if Google enforces identity verification for all Android developers, age verification for app distribution may become redundant as developer identity would already be established |

### Software Planning to Implement Age Verification

| &nbsp; | Software | Notes |
| - | - | - |
| :building_construction: | **AccountsService** | [MR: Add BirthDate with polkit-gated GetBirthDate and SetBirthDate methods](https://gitlab.freedesktop.org/accountsservice/accountsservice/-/merge_requests/176) — stores birth date in `/var/lib/AccountsService/users/`; reading is gated by polkit (`org.freedesktop.accounts.read-own-protected-data`), writing requires `org.freedesktop.accounts.user-administration`; uses same YYYY-MM-DD validation as systemd PR #40954; MR open |
| :building_construction: | **XDG Desktop Portal** | [Draft PR: Add parental controls to the Accounts portal](https://github.com/flatpak/xdg-desktop-portal/pull/1922) — proposes an age verification API allowing apps to query age ranges rather than exact birth dates; discussion thread locked by maintainers (March 10, 2026), further comments restricted to collaborators only |
| :building_construction: | **archinstall** | [PR: Add required birth date field to user creation](https://github.com/archlinux/archinstall/pull/4290) — by the same author as the systemd birthDate PR; stores birth date in a systemd userdb drop-in at `/etc/userdb/<user>.user` during Arch installation; PR open but discussion locked as "too heated"; maintainer (Torxed) awaiting an official organizational stance from Arch Linux before merging |
| :building_construction: | **Pacman** | [Draft MR: Age verification support](https://gitlab.archlinux.org/pacman/pacman/-/merge_requests/353) — draft merge request proposing age verification integration into the Arch Linux package manager; currently only updates `doc/PKGBUILD.5.asciidoc` (documentation only); may be a joke or placeholder, but could still be taken as a serious suggestion |

### Software Which Has Already Implemented Age Verification

| &nbsp; | Software | Notes |
| - | - | - |
| :white_check_mark: | **systemd** | [Merged: Add `birthDate` field to user database records](https://github.com/systemd/systemd/pull/40954) — administrators can store birth dates in user records to support age verification laws (Brazil, California, Colorado); [revert attempt rejected](https://github.com/systemd/systemd/pull/41179) |
| :no_entry: | **Liberated Systemd** *(systemd fork)* | [Fork of systemd without age verification](https://github.com/Jeffrey-Sardina/systemd) — created in opposition to the merged `birthDate` field; removes age verification functionality from the base |
| :no_entry: | **dinit** | [Developer discussion](https://github.com/davmac314/dinit/discussions/539) — developer considers age verification irrelevant to the project and is opposed to implementing it |

---

## Mobile Operating Systems

Both major mobile OS vendors have already shipped age verification APIs at the OS and App Store levels.

### Mobile Operating Systems Not Implementing Age Verification

| &nbsp; | OS | Notes |
| - | - | - |
| :no_entry: | **GrapheneOS** | [Developer statement](https://x.com/GrapheneOS/status/2034957604682621229) |

### Mobile OS Which Have Already Implemented Age Verification

| &nbsp; | OS | Notes |
| - | - | - |
| :white_check_mark: | **Android (Google)** | [Play Age Signals API](https://developer.android.com/google/play/age-signals/overview) — live for Brazil (March 17, 2026) and rolling out for California (AB-1043, effective Jan 1, 2027); shares age brackets (0–12, 13–15, 16–17, 18+) with apps; data may not be used for advertising or profiling |
| :white_check_mark: | **iOS (Apple)** | [Declared Age Range API](https://developer.apple.com/documentation/declaredagerange/) — live for Brazil, Australia, Singapore, Utah, and Louisiana (February 24, 2026); shares age range only with user consent; no PII or document scans passed to developers; [developer announcement](https://developer.apple.com/news/?id=f5zj08ey) |

---

## Browsers

### Browsers With Published Analysis or Discussion

| &nbsp; | Browser | Notes |
| - | - | - |
| :speech_balloon: | **Brave** | [Blog: "The Limits of Zero-Knowledge for Age Verification"](https://brave.com/blog/zkp-age-verification-limits/) — published skeptical technical analysis of ZKP-based approaches; raises concerns about reidentification risks, centralization, and exclusion of users without formal ID; no implementation announced |
| :speech_balloon: | **Mozilla Firefox** | No official public statement found regarding California AB-1043, Brazil Lei 15.211, or Colorado SB26-051; only existing age check is a COPPA-related 13+ gate for Firefox Account signup |
| :speech_balloon: | **Chromium / Google Chrome** | No formal public statement on the specific laws; Google has implemented age verification for signed-in Chrome users via Credential Manager API; [Digital Credentials API](https://developer.chrome.com/blog/digital-credentials-api-origin-trial) documented for identity verification but not directly tied to the OS-level laws |

---

## Messaging Apps

### Messaging Apps Which Have Already Implemented Age Verification

| &nbsp; | App | Notes |
| - | - | - |
| :white_check_mark: | **Telegram** | [Official age verification bot](https://core.telegram.org/api/age-verification) — on-device facial analysis (no data sent to servers); currently live in the UK and expanding to other jurisdictions; restricts access to 18+ content based on verification result |

### Messaging Apps Planning to Implement Age Verification

| &nbsp; | App | Notes |
| - | - | - |
| :building_construction: | **WhatsApp (Meta)** | [Meta AgeKey](https://about.fb.com/news/video/age-verification/) — uses on-device biometric authentication to confirm age bracket without sharing PII; Phase 1 rolling out in UK, Australia, and Brazil; parent-managed accounts for under-13 users announced March 11, 2026 |
| :building_construction: | **Discord** | [Age assurance rollout](https://discord.com/blog/getting-global-age-assurance-right-what-we-got-wrong-and-whats-changing) delayed to second half of 2026 after user backlash; uses age inference model for most users (90%+ require no action); offers on-device facial estimation or government ID via third-party vendor; **note:** a [breach of third-party vendor 5CA](https://discord.com/press-releases/update-on-security-incident-involving-third-party-customer-service) in October 2025 exposed government ID photos submitted for age verification appeals, affecting ~70,000 users |

---

## Video Platforms

### Video Platforms Which Have Already Implemented Age Verification

| &nbsp; | Platform | Notes |
| - | - | - |
| :white_check_mark: | **YouTube (Google)** | Live in the UK, EU, EEA, Switzerland, and Australia; rolling out in the US; uses AI age estimation (viewing patterns, account history) combined with optional ID upload, credit card check, or Yoti-based facial scan; [blog announcement](https://blog.youtube/news-and-events/using-technology-more-consistently-apply-age-restrictions/) |
| :white_check_mark: | **TikTok (ByteDance)** | Live globally; uses signal-based detection plus Yoti facial estimation and ID verification; reports removing ~6 million underage accounts per month; complying with Brazil Lei 15.211 under ANPD regulatory order; [Europe rollout announcement](https://newsroom.tiktok.com/updates-to-how-we-enforce-age-appropriate-experiences-in-europe?lang=en) |

---

### Messaging Apps With Ongoing Discussions

| &nbsp; | App | Notes |
| - | - | - |
| :speech_balloon: | **Signal** | No official statement on California AB-1043, Brazil Lei 15.211, or Colorado SB26-051; only existing requirement is a 13+ minimum age in Terms of Service; no age verification features found in public repositories |
| :speech_balloon: | **Matrix** | [Blog post (February 2026)](https://matrix.org/blog/2026/02/welcome-discord/) — acknowledges laws are legally binding and must be followed; Safety team and DPO evaluating privacy-preserving compliance options; notes Matrix's decentralized nature allows individual server operators to make their own assessments; no implementation announced |
