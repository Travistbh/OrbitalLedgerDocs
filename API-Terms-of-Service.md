# Orbital Ledger — Custom API Terms of Service

**Effective date:** 2026-10-03
**Version:** 1.0
**Operator:** Independent Solutions Ltd., a Colorado business, doing business as Digital City, ("**we**", "**us**", "**Orbital Ledger**")
**Contact:** independentsolutionsltd.2018@gmail.com

> **All policies are subject to change.** We may update this document at any time. Check back from time to time; where changes are material we may ask you to review and accept again in the Game.

These terms govern any software, script, bot, bridge, agent, integration or other program that connects to Orbital Ledger's servers, the Orbital Ledger SpacetimeDB backend, or any API we provide, other than the official Orbital Ledger client we publish. By connecting, pairing a credential, calling a reducer, subscribing to a table, or publishing a Custom Tool, you agree to these terms. If you don't agree, don't connect.

---

## 1. Definitions

- **Game**: Orbital Ledger, including its simulation, rules, economy, data, art, text, audio, interface and all related services.
- **Backend**: the SpacetimeDB module, database, tables, reducers, views, subscriptions, HTTP endpoints, authentication and pairing services, and any hosted infrastructure we operate for the Game.
- **API**: every way of reading from or writing to the Backend, including the SpacetimeDB connection, reducers, table subscriptions, pairing and agent tokens, and the documentation, schemas, generated bindings and client libraries we publish.
- **Custom Tool**: any software, script, bot, plugin, overlay, spreadsheet, agent, website, app or service that uses the API or connects to the Backend, whether or not it is built from our published examples.
- **Game Content**: all data and material that originates from the Game or Backend, including item, recipe, research, market, station, ship, route, price and event data, and the table schemas and reducer names and signatures.
- **Credential**: any pairing code, agent token, JWT, identity or key that lets a program act as a player's corporation.
- **Monetize**: see Section 4.
- **You**: the person or entity that builds, runs, shares or uses a Custom Tool.

## 2. Relationship to the EULA

These terms sit alongside the Orbital Ledger EULA and Modding and Custom Tools Policy. You must accept both. If they conflict about a Custom Tool, the stricter provision applies.

## 3. License to use the API

Subject to these terms, we grant you a limited, personal, non-exclusive, non-transferable, non-sublicensable, revocable license to:

1. connect Custom Tools to the Backend using the API as documented, for the purpose of playing the Game, or helping other players play the Game, with your own account or with accounts whose owners have authorized you;
2. use Game Content inside Custom Tools to display, analyze or interact with the Game; and
3. share your Custom Tool with other players **free of charge**, under Section 5.

All rights not expressly granted are reserved. The license is **non-commercial only**.

**Public-read data is not a public license.** Some tables may be readable by anyone who connects. That is a technical convenience for players and tool builders. It does not grant you ownership of, or any right to republish, resell, mirror, redistribute at scale, or build a competing product from, Game Content, except as Section 5 allows.

## 4. No monetization

You may not Monetize a Custom Tool, or any access to the API, the Backend or Game Content. "Monetize" means to obtain or seek any money, goods, services, credit, cryptocurrency, token, advantage or other consideration, directly or indirectly, in connection with a Custom Tool. This includes, without limitation:

- selling, licensing, renting, leasing or subscribing a Custom Tool, in whole or in part;
- charging for access, features, premium tiers, keys, downloads, updates, support, customization or setup;
- placing a Custom Tool, or any feature or download of it, behind a paywall, membership, Patreon-style tier, Discord role purchase, or donation requirement;
- advertising, sponsorship, affiliate links, referral codes, or paid placement inside or alongside the Custom Tool;
- collecting, selling or licensing user data or Game Content obtained through the Custom Tool;
- bundling a Custom Tool with something paid so the paid item is what makes the tool available;
- selling or trading in-game currency, items, accounts, ships, shares or corporation positions for real money or anything of real-world value, whether or not a Custom Tool is involved;
- using a Custom Tool to run a paid service, such as a paid automation or "bot-for-hire" service, a paid signal, tip or analytics service, or a paid league;
- charging for the development of a Custom Tool for a client, where the tool uses the API or Backend.

[OPTIONAL — DECIDE: voluntary tips. Option A, default and safest: tips and donations that are linked to a Custom Tool are also prohibited. Option B: a clearly voluntary tip jar, such as Ko-fi or GitHub Sponsors, is allowed only if it unlocks nothing, is not promoted inside the tool, and is not tied to features, priority or support.]

You may recover **no** costs from other players. If you host a Custom Tool as a service for others, you absorb the hosting cost.

A written commercial agreement signed by us is the only exception. Contact us at independentsolutionsltd.2018@gmail.com to ask.

## 5. Sharing Custom Tools

You may share a Custom Tool with others, free of charge, if all of the following hold:

1. **It's free.** No price, gate, ad or other consideration (Section 4).
2. **It uses the real Backend only through the official, documented API** and does not bundle, mirror or redistribute the Backend, its source, a database snapshot, or a substantial copy of Game Content.
3. **It tells users what it does,** including that it connects to Orbital Ledger, what data it reads and writes, and what Credentials it needs. It must not hide functionality.
4. **Every user uses their own Credential.** A Custom Tool must not ask players to hand over their Discord or Google login, nor request a long-lived Credential beyond what the pairing flow issues. It must never collect, log or forward a Credential to anyone but the Backend.
5. **It carries this notice** in its README, store page or about screen: "Unofficial community tool for Orbital Ledger. Not made, endorsed or supported by Digital City. Free to use. Use at your own risk."
6. **It doesn't pose as official.** No use of our name, logos or trade dress in a way that suggests the tool is the Game or is endorsed by us. Plain factual references ("for Orbital Ledger") are fine.
7. **It is licensed to others on terms no broader than these.** If you publish your own source code under an open-source license, that license covers your original code only. It cannot grant any rights in the API, the Backend or Game Content. If you license your code in a way that lets others sell it, those others are still bound by these terms and the sale is a breach by them.

You own the original code you write. We own the Game, the Backend, Game Content, the schemas, the API and our brands. Nothing here transfers ownership either way.

## 6. Prohibited conduct

You must not:

1. **Cheat or gain unfair advantage** by exploiting bugs, race conditions, malformed reducer input, schema quirks or server errors. Report them to us instead.
2. **Bypass restrictions.** No circumventing authentication, rate limits, visibility rules, permissions, ownership checks, pairing expiry, admin or owner-only reducers, or any other access control.
3. **Act as someone else.** No using Credentials you were not given by the account's owner. No impersonating a player, an NPC, us, or an administrator.
4. **Impose unreasonable load.** No flooding, stress-testing, load testing, scraping or denial of service. Respect published rate limits; where none are published, keep call volume to what a single human player of the Game would plausibly generate with reasonable automation. We may throttle or block any traffic at our discretion.
5. **Build a competitor or clone.** No using the API, Backend, Game Content, schema or documentation to build, host, train or operate a competing game, a private server, a compatible backend, or a reimplementation of the Backend. No extracting the full dataset of the Game to seed one.
6. **Reverse engineer.** No decompiling, disassembling or deriving the source of the Backend or any non-public part of the Game, except to the extent the law gives you the right regardless of this term.
7. **Use for AI training.** No using Game Content, API responses or documentation to train, fine-tune or evaluate a machine-learning model, or to build a dataset for that purpose, without our written permission. An agent that plays the Game on a player's behalf is allowed; an agent or pipeline that harvests Game Content for training is not.
8. **Write in bad faith.** No spam, harassing or deceptive content posted via reducers (chat, messages, news, names), no content that is unlawful, hateful, sexual involving minors, or infringing.
9. **Run unattended mass-account operations.** No creating, farming, trading between or operating multiple accounts to evade limits, manipulate markets, or collude to extract unfair advantage.
10. **Manipulate the economy** through coordinated tools in ways that the Game's rules forbid, or that harm other players' experience, such as market cornering by automation designed to deny others access.
11. **Interfere with the Game's integrity**, including tampering with the NPC economy, news feed, or live-tuning or admin channels, unless you are authorized by us in writing.
12. **Violate third-party terms.** Tools that use Discord, Google, itch.io or other platforms must comply with those platforms' rules.

## 7. Credentials and security

- You are responsible for everything done with any Credential issued to you or your Custom Tool.
- Keep Credentials secret. Never put them in public code, screenshots, chat, logs or shared configuration. If one leaks, revoke it immediately and tell us.
- Pairing codes are one-time and short-lived; agent tokens expire. Don't build workarounds that persist access past expiry or past the owner's revocation.
- We may revoke any Credential at any time.
- If you find a vulnerability, report it privately to independentsolutionsltd.2018@gmail.com and give us reasonable time to fix it before disclosure. Don't exploit it, access other players' private data, or disrupt the Game while testing.

## 8. Data and privacy

- A Custom Tool may only read and act on data the player behind the Credential is allowed to see and do through the Game itself.
- A Custom Tool must not collect personal data beyond what it needs, and must not store, sell or share another person's account identifiers (Discord or Google IDs, emails), Credentials, IP addresses or private game data except as that person has clearly agreed.
- If your Custom Tool stores data about other players, you are responsible for complying with applicable privacy laws and must provide a way to delete it on request.
- Our handling of data is described in our Privacy Policy (/legal/privacy).

## 9. Content you send us

If you send content to the Backend (names, messages, news, feedback, bug reports), you grant us a worldwide, perpetual, irrevocable, royalty-free, sublicensable license to use, host, copy, modify, display and distribute it in connection with the Game. You confirm you have the right to do this. Feedback and suggestions you give us may be used freely without compensation or credit.

## 10. Our rights over the Backend and API

- We may change, limit, deprecate or discontinue any part of the API or Backend at any time, with or without notice, including reducer names, signatures, table schemas, authentication flow, rate limits and the pairing mechanism. We have no obligation to keep any Custom Tool working.
- We may add, remove or reclassify data visibility (Private, Global, Public) at any time.
- We may monitor API usage to run, secure and improve the Game and to enforce these terms.
- The Game's data, balance and rules can change or be reset, including wipes. Nothing in a Custom Tool entitles you to any particular state, price, result or outcome.

## 11. Suspension and termination

We may, at our sole discretion and without prior notice, suspend or revoke Credentials, block IPs or accounts, remove or reverse in-game effects of a breach, disable a Custom Tool's access, and take down a shared Custom Tool, where we believe you have breached these terms, endangered the Game or other players, or where the law requires it.

You may stop at any time by ceasing to use the API and deleting your Credentials. Sections that by nature should survive do survive (including 3 (non-commercial limit), 4, 5, 6, 9, 12, 13, 14).

If you Monetize a Custom Tool in breach of Section 4, in addition to other remedies you must stop immediately, and we may require you to account for and pay us the consideration you received from the breach, to the extent the law allows.

## 12. Disclaimer of warranties

THE API, BACKEND AND GAME ARE PROVIDED "AS IS" AND "AS AVAILABLE", WITHOUT WARRANTIES OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, ACCURACY, AVAILABILITY AND NON-INFRINGEMENT. We do not guarantee uptime, data accuracy, backward compatibility or that a Custom Tool will work or be safe. Custom Tools made by others are not ours; we are not responsible for them.

## 13. Limitation of liability

TO THE MAXIMUM EXTENT PERMITTED BY LAW, WE ARE NOT LIABLE FOR INDIRECT, INCIDENTAL, SPECIAL, CONSEQUENTIAL, EXEMPLARY OR PUNITIVE DAMAGES, OR FOR LOST PROFITS, DATA, GOODWILL OR IN-GAME PROGRESS, ARISING FROM THE API, BACKEND, GAME OR CUSTOM TOOLS. OUR TOTAL LIABILITY FOR ALL CLAIMS RELATING TO THESE TERMS IS LIMITED TO USD 50. Some jurisdictions don't allow some of these limits; in that case they apply to the fullest extent allowed.

## 14. Indemnity

You will defend and indemnify us and our personnel against claims, losses and costs (including reasonable legal fees) arising from your Custom Tool, your breach of these terms, your violation of law or third-party rights, or content you send through the API.

## 15. Enforcement and equitable relief

You acknowledge that a breach of Sections 3 to 6 may cause us harm that money cannot fully repair, and that we may seek injunctive or other equitable relief in addition to any other remedy, without posting bond to the extent the law allows.

## 16. Copyright and takedown

If you believe material shared in connection with the Game infringes your copyright, send notice to independentsolutionsltd.2018@gmail.com with the details required by applicable law. We may remove material and terminate repeat infringers. We may also issue takedown requests to third-party platforms for Custom Tools that breach these terms.

## 17. Changes to these terms

We may update these terms. Material changes take effect on the date we post them and may require you to re-accept them in the Game. Continued use of the API after that date means you accept the update. If you don't, stop using the API.

## 18. General

- **Governing law and venue:** the State of Colorado, USA. Disputes go to the courts of Colorado (state and federal courts located in Colorado), unless you are a consumer with non-waivable rights elsewhere. [OPTIONAL: binding arbitration and class-action waiver — confirm with counsel.]
- **Age:** you must be at least 13 to use the API, or have a parent's or guardian's permission and supervision where the law allows.
- **Entire agreement:** these terms, the EULA and the Modding and Custom Tools Policy are the whole agreement about the API.
- **Severability:** if a provision is unenforceable, the rest stays in effect.
- **No waiver:** not enforcing a term is not giving it up.
- **Assignment:** you may not assign these terms; we may.
- **Order of precedence:** a signed written agreement with us overrides these terms only for what it expressly covers.
- **Contact:** independentsolutionsltd.2018@gmail.com.
