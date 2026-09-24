# PRC / EU–EEA transfer regimes — a practitioner comparison

**Content verification date:** this file adds no new sources. Every statement
below is carried from `china/routes.md` (verified 2026-09-13) or
`eu/chapter-v.md` (verified 2026-09-15), each cited to the section it comes
from. Recheck both source files, and this one, against their own verification
dates before relying on anything here.

Label key, carried across unchanged from both source files: `[Statutory]` the
instrument says this · `[Interpretive]` a defensible reading or a regulator's
published guidance, not statutory text · `[Unsettled]` genuinely open ·
`[Dynamic — retrieve current version]` changes without any instrument being
amended · `[To be verified]` not confirmed against a retrieved source. A label
attached to a point in one file is carried to this file unchanged — this file
never upgrades or downgrades a label on its own authority.

Citations below are written `(china §n)` / `(eu §n)`, meaning the numbered
section of `china/routes.md` or `eu/chapter-v.md`.

This file does not repeat everything in either source. Where the two regimes
address the same practitioner question with genuinely comparable content, it
is set out side by side. Where one file speaks and the other doesn't, or
where a shared vocabulary word means different things on each side, that
mismatch is stated in prose rather than forced into a table.

---

## 1. What counts as a transfer — and does remote access count?

**China.** No instrument reviewed in `china/routes.md` defines 数据出境 (data
export/"providing personal information abroad"), the term PIPL Art. 38, DSL
Art. 31 and CSL Art. 39 all use without defining it (china §1, §4). The file's
own `[Unsettled]` note is explicit: "Whether remote access from outside China
to personal information stored in China constitutes 数据出境 for these
purposes. None of the instruments retrieved defines 数据出境, and no
retrieved CAC Q&A addresses remote access" (china §4). The question is not
narrowed by any guidance the file found — it is open at the level of the
core trigger term itself.

**EU/EEA.** Art. 44 GDPR also does not define "transfer" — it states the
condition and consequence without defining the trigger (eu §1). But the gap
has been filled, `[Interpretive]`, by EDPB Guidelines 05/2021 v2.0's three
cumulative criteria: an EU-regulated exporter, disclosure or making-available
to another controller/processor, and a third-country importer "irrespective
of whether that importer is itself subject to the GDPR" (eu §1). On that
test, remote access is expressly a transfer — "including where the data is
only displayed on a screen," with no requirement that data physically move
(eu §1, `[Interpretive]`). The same guidelines carve out one adjacent point
`[To be verified]` in `eu/chapter-v.md`: that an exporter's own employee
accessing the exporter's data from a third country may **not** be a transfer,
because the employee is not "another" controller — but this was sourced to a
consultation draft, not the retrieved v2.0 text, and stays unconfirmed on
that basis (eu §1).

**Where the two diverge.** Both regimes leave "transfer" undefined in their
respective primary instruments. The EU side has an authoritative-in-practice
gloss on top of that gap, `[Interpretive]` but settled enough that
`eu/chapter-v.md` states remote access counts as a flat rule with named
consequences. The China side has no such gloss on record: `china/routes.md`
does not merely lack a rule for remote access, it records that no rule has
been found. A practitioner cannot import the EU's "screen display is enough"
conclusion into the PRC analysis — the two files simply do not converge here,
and that gap is itself the comparison.

---

## 2. Is there a concept of adequacy, and what substitutes for it?

**EU/EEA.** Adequacy is a defined, Commission-run mechanism: Art. 45(1)
lets transfers to a covered country, territory, sector or international
organisation proceed with no specific authorisation (eu §3, §4). It is
decided by implementing act, reviewed at least every four years, can be
suspended or repealed (without retroactive effect) and is limited to the
territorial/sectoral scope stated in the act (eu §4, all `[Statutory]`,
Art. 45(3)–(8)). It can also be annulled by the Court of Justice — Case
C-311/18 did exactly that to the EU–US Privacy Shield decision (eu §4,
`[Statutory]`). The current list, and the litigation status of any decision,
are both `[Dynamic — retrieve current version]` — the file deliberately does
not state a count (eu §4).

**China.** `china/routes.md` describes no mechanism that assesses a
destination country's legal system, and no destination-country list. The
routing structure in §§2–4 is keyed entirely to who the exporter is (CIIO or
not), what is being exported (personal information, sensitive personal
information, important data) and how much has been exported since 1 January
of the current year — never to where it is going. Order No. 16's exemptions
(Arts. 3–6, china §3) and threshold routing (Arts. 7–8, china §4) contain no
destination-country criterion at any point. This is a description of what
`china/routes.md` establishes, not an affirmative claim that no such concept
exists anywhere in PRC law outside the instruments the file reviews.

**Where the two diverge.** This is not a case of the same concept under a
different name. The EU's adequacy is a country-level, Commission-decided,
periodically-reviewed determination that substitutes for a transfer
mechanism entirely once made. Nothing in `china/routes.md` performs that
function or anything resembling it — the closest thing on the PRC side, the
Art. 6 free-trade-zone negative list (china §3), is *location-of-the-exporter*
specific, not destination-country specific, and only exempts from needing a
route, the same way Arts. 3–5 do. There is no PRC substitute for adequacy to
report; the honest comparison is that the question doesn't arise on that
side of the file.

---

## 3. What instruments are available, and are they chosen freely or fixed?

**China — fixed by volume and classification, not chosen.** Once no
exemption applies (china §2, §3), Order No. 16 Arts. 7–8 fix the route:

| Exporter / data | Route | Basis |
| --- | --- | --- |
| CIIO exporting personal information or important data | Security assessment — no volume threshold | Art. 7(1) `[Statutory]` |
| Non-CIIO exporting important data | Security assessment | Art. 7(2) `[Statutory]` |
| Non-CIIO, ≥1,000,000 individuals (non-sensitive) or ≥10,000 (sensitive), cumulative since 1 Jan | Security assessment | Art. 7(2) `[Statutory]` |
| Non-CIIO, 100,000–999,999 individuals (non-sensitive) or <10,000 (sensitive) | Standard contract **or** certification — chooser's choice | Art. 8 `[Statutory]`; choice between the two is `[Interpretive]`, china §4 |
| Non-CIIO, <100,000 individuals, no sensitive data, and one of the Art. 5 conditions met | Exempt from all three routes (obligations still apply — see §7 below) | Art. 5(4) `[Statutory]` |

(china §4). The only point of free choice in this table is standard contract
vs. certification within the Art. 8 band, described as "alternatives within
the same band, not a sequence" (china §4, `[Interpretive]`) — everything else
is determined by classification and a running headcount.

**EU/EEA — chosen by adequacy status and relationship, not volume.** The
GDPR sets no numeric threshold anywhere in Chapter V as reviewed in
`eu/chapter-v.md`. The order of analysis is adequacy first (Art. 45), then —
only in its absence — a safeguard chosen from the Art. 46(2) list: SCCs, BCR,
an approved code of conduct, an approved certification mechanism, or (with
authorisation) ad hoc clauses (eu §3, §5, all `[Statutory]`). Among the
Art. 46(2) options that need no supervisory authorisation, the choice is the
exporter's, constrained by the parties' roles rather than by volume — SCC
module selection (One–Four) tracks controller/processor status, not headcount
(eu §5). Only BCR and ad hoc clauses require prior approval from the
competent supervisory authority (eu §5, `[Statutory]`, Art. 46(3), Art. 47(1)).

**Where the two diverge.** These are not the same kind of choice. On the PRC
side, "which instrument" is very largely answered by arithmetic — a running
count of individuals since 1 January — with almost no room for the exporter
to select a route it would prefer. On the EU side, volume plays no role at
all in `eu/chapter-v.md`; what changes the instrument is the legal status of
the destination country (adequate or not) and the parties' relationship
(controller/processor roles, group structure). A German company sizing up
"how many people are affected" is asking the right question for its PRC
export and the wrong one for its EU/EEA transfer.

---

## 4. Is a filing or approval required, and to whom?

**China.**
- Security assessment: declared **to the CAC**, through the **provincial
  cyberspace administration** where the processor is located (china §4,
  Art. 7, `[Statutory]`) — an approval, not a notification; §6 covers the
  3-year validity and extension procedure that follows a successful one.
- Standard contract: **filed** with the provincial cyberspace administration
  **within 10 working days of the contract taking effect**, submitting the
  contract and the impact assessment report (china §6, Order No. 13 Art. 7,
  `[Statutory]`). This is a post-execution filing, not a pre-clearance.
- Certification: obtained from a professional certification body; before
  applying, the processor must have already performed notice, separate
  consent and the impact assessment (china §6, Order No. 20 Art. 6,
  `[Statutory]`).

**EU/EEA.**
- Adequacy transfers: Art. 45(1) states in terms that adequacy transfers
  "shall not require any specific authorisation" (eu §3, §4, `[Statutory]`).
- SCCs under Art. 46(2)(c): also listed among the safeguards available
  "without any specific supervisory authority authorisation" (eu §5,
  Art. 46(2), `[Statutory]`). `eu/chapter-v.md` records no filing or
  notification duty to any supervisory authority that attaches to executing
  SCCs as such.
- BCR: require **approval** by the competent supervisory authority through
  the Art. 63 consistency mechanism (eu §5, Art. 47(1), `[Statutory]`) —
  described as "an authorisation-based route with a lead-time measured in
  years" (eu §5, `[Interpretive]`).
- Ad hoc clauses under Art. 46(3): also require supervisory authority
  authorisation (eu §5, `[Statutory]`).

**Where a resemblance misleads.** China's standard-contract route and the
EU's SCC route sound parallel — both are labelled "standard contract(s)" and
neither requires prior government approval to use. But the PRC route still
carries an affirmative filing obligation to a state authority within a fixed
deadline, with named required attachments (china §6). Nothing in
`eu/chapter-v.md`'s treatment of the 2021 SCCs describes an equivalent filing
step — the EU mechanism as described there is self-executing between the
parties, subject only to the exporter's own duty to suspend if Clause 14
conditions fail (eu §6) and to inform data subjects (eu §2, Decision
2021/914 recital 4). Calling the PRC route "just a filing, like the EU SCCs"
understates it: it is a filing *to a regulator*, on a deadline, with
substantive attachments — the EU route has no equivalent step at all.

---

## 5. Is an impact assessment required, what is it called, and when?

**China — PIPIA, and it survives every exemption.** Order No. 16 Art. 10
requires notice, separate consent, **and** a "personal information protection
impact assessment" (个人信息保护影响评估, PIPIA) as obligations that sit
**outside** Arts. 3–8 entirely — qualifying for an exemption "removes the
route, not these obligations" (china §5, `[Statutory]`). Its statutory basis
is PIPL Art. 55(4) (required before any cross-border provision of personal
information, with the processing recorded) and its content is fixed by
PIPL Art. 56: lawfulness/justification/necessity of purpose and method, the
impact on individuals' rights and the security risk, and whether protective
measures are lawful, effective and commensurate with the risk (china §5,
`[Statutory]`). It must also be filed as an attachment for the standard
contract route (china §6, Order No. 13 Art. 5, before export) and completed
before applying for certification (china §6, Order No. 20 Art. 6). The file
flags the practical failure mode directly: treating a volume-based exemption
as a compliance exit, when notice, consent and the PIPIA are still owed
(china §5, `[Interpretive]`).

**EU/EEA — TIA, and it is not a GDPR-defined term.** "Transfer impact
assessment" appears nowhere in the GDPR text; `eu/chapter-v.md` sources the
obligation to Case C-311/18 (Schrems II) and to Clause 14 of the 2021 SCCs,
and states explicitly that it is separate from the Art. 35 data protection
impact assessment (eu §6, `[Interpretive]` for the naming and DPIA
distinction; `[Statutory]` for the underlying Clause 14 duties). Unlike the
PRC PIPIA, the TIA is not a universal cross-border obligation — it is tied to
the Art. 46 safeguard route specifically. An adequacy transfer under Art. 45
does not need one, because the "essentially equivalent protection" finding
has already been made by the Commission for that country (eu §3, §4, §6).
Where it does apply (SCCs), Clause 14(b) requires the exporter and importer
to take due account of the specific circumstances of the transfer, the third
country's laws and practices, and any supplementary safeguards, and Clause
14(d) requires the assessment to be **documented** and produced to the
supervisory authority on request (eu §6, all `[Statutory]`).

**Where a resemblance misleads.** A PIPIA is not a TIA, and treating them as
the "same document under a different name" would be wrong in both directions.
Trigger: the PIPIA is owed on *every* cross-border personal information
transfer in China, exemption or not (china §5); the TIA is owed only when the
EU exporter is relying on Art. 46 safeguards, not on adequacy (eu §3, §6).
Content: the PIPIA's statutory focus (PIPL Art. 56) is the lawfulness,
necessity and risk of the *processing itself* and the adequacy of protective
measures; the TIA's focus (Clause 14(b), read with C-311/18) is squarely the
**third country's laws and practices** on public authority access, assessed
against an "essentially equivalent protection" standard. A single combined
document built to satisfy one is unlikely, on the sources here, to satisfy
the other without separate work addressing the question each was built to
answer.

---

## 6. Is individual consent required, and what kind?

**China — separate consent, conditional on legal basis, but notice always.**
PIPL Art. 39 requires **separate consent** (单独同意) for cross-border
provision of personal information, plus notice of the overseas recipient's
identity and contact details, processing purpose and method, data
categories, and how the individual exercises PIPL rights against the
recipient (china §5, `[Statutory]`). Order No. 16 Art. 10 places this
obligation, like the PIPIA, outside Arts. 3–8 — it survives every exemption
(china §5). One conditionality is recorded, `[Interpretive]`, from CAC policy
Q&A: where the underlying processing rests on a PIPL Art. 13(1)(ii)–(vii)
basis rather than consent, separate consent is not required, but the notice
obligation remains (china §5). The same guidance requires the consent to be
specific and unbundled — no omnibus "一揽子" consent — collectable by
signature, pop-up, email or SMS (china §5, `[Interpretive]`).

**EU/EEA — two consent concepts, and the file is explicit they must not be
merged.** `eu/chapter-v.md` §2 is organised around exactly this risk. Art. 6(1)(a)
consent is consent **to the processing**; it is one of six lawful bases and
has nothing to do with Chapter V by itself (eu §2, `[Statutory]`). Separately,
Art. 49(1)(a) requires **explicit** consent **to the proposed transfer**,
given after the data subject is informed of the risks arising from the
absence of adequacy and appropriate safeguards (eu §2, §8, `[Statutory]`) —
and this is one of the Art. 49 derogations, meaning it is available **only**
where adequacy and Art. 46 safeguards are both absent (eu §3, §8). The file
states plainly: "That is not the Art. 6(1)(a) consent to the processing, and
one does not carry the other" (eu §2). EDPB Guidelines 2/2018 add that the
Art. 49(1)(a) consent must be explicit, specific to *that* transfer, and the
derogations generally must be read restrictively, reserved for
non-repetitive transfers outside the regular course of business (eu §8,
`[Interpretive]`).

**Where the two diverge.** China's separate consent functions as a baseline
obligation that rides alongside whichever route is used (when the processing
is consent-based) — it is not itself a transfer mechanism, and it does not
compete with the security assessment, standard contract or certification
routes. The EU's Art. 49(1)(a) consent is different in kind: it *is* one of
the transfer mechanisms, available only as a narrow fallback when adequacy
and Art. 46 both fail, and the file's own framing warns against treating it
as routine. A practitioner carrying PIPL's model — "get separate consent as
a standing obligation" — into the EU analysis risks reaching for Art. 49(1)(a)
consent as if it were an ordinary, repeatable step, which is precisely the
reading EDPB Guidelines 2/2018 rule out (eu §8).

---

## 7. What happens to the obligations when an exemption applies?

**China.** This maps cleanly onto china §5: Order No. 16 Art. 10 (notice,
separate consent, PIPIA) and Art. 11 (data security protection obligations,
incident response and reporting) sit outside the exemption structure of
Arts. 3–8 altogether. An exemption removes the need for a security
assessment, standard contract or certification; it does not touch these
obligations (china §5, `[Statutory]`, with the point restated `[Interpretive]`
as the file's flagged common error).

**EU/EEA.** `eu/chapter-v.md` does not use "exemption" the same way — there
is no PRC-style set of activity- or volume-based carve-outs from Chapter V as
a whole. The nearest structural parallel is narrower and works differently:
Art. 45(1) adequacy removes the need for "specific authorisation" but, per
the file's own `[Interpretive]` reading, "does not touch Art. 6, Art. 28 or
the information duties" (eu §4). More generally, §2 of `eu/chapter-v.md` is
built around the point that Art. 6 lawfulness and Art. 28 processor
obligations are never displaced by *any* Chapter V mechanism — adequacy,
safeguards or derogations alike — because Art. 44 makes Chapter V "subject to
the other provisions of this Regulation" (eu §2, `[Statutory]`). Even the
Art. 49 derogations, which are themselves an exception to needing adequacy or
Art. 46 safeguards, carry their own surviving duties — the second
subparagraph's compelling-legitimate-interests fallback requires informing
the supervisory authority and the data subject, and documenting the
assessment in Art. 30 records (eu §8, `[Statutory]`).

**Why this should not be flattened into a table.** The two files are not
answering the same structural question here. China's Arts. 3–6 are exemptions
from an otherwise-mandatory route-selection step, with a named, separate set
of obligations (Art. 10–11) stated to survive them. The EU has no equivalent
"exemption from Chapter V" concept for the practitioner to hold up against
that — its closest analogues (adequacy's removal of "specific authorisation";
Art. 49's own narrow fallback status) are each doing something different from
what Order No. 16's exemptions do. The one genuine common thread, worth
stating plainly: on both sides, nothing in either file describes any
mechanism, general or narrow, that relieves the exporter of the baseline
lawfulness/notice-type obligations that sit outside the transfer-mechanism
choice itself — china's Art. 10/11 on one side, Art. 6/28/13/14 on the other.

---

## 8. How long is a mechanism valid, and what triggers a fresh one?

| Mechanism | China | EU/EEA |
| --- | --- | --- |
| Government-level periodic check | Not established — no destination-country mechanism exists to review (china, throughout; see §2 above) | Adequacy decision: periodic review **at least every 4 years** (eu §4, Art. 45(3), `[Statutory]`) |
| Exporter-specific route, fixed term | Security assessment: valid **3 years** from issuance (china §6, Order No. 16 Art. 9, `[Statutory]`, superseding Order No. 11's 2-year term); extension application within **60 working days before expiry**, available only if no fresh-declaration trigger has arisen | Not established — `eu/chapter-v.md` describes no fixed validity term for any Art. 46 safeguard |
| Exporter-specific route, ongoing/reactive | Not established — routes.md does not state a validity period or expiry trigger for the standard contract or certification routes beyond the initial 10-working-day filing deadline (china §6) | SCCs: no fixed term recorded. Instead, Clause 14(e) requires the importer to notify the exporter promptly of a relevant change in the third country's law or practice, and Clause 14(f) requires the exporter to suspend the transfer if no appropriate safeguard remains available (eu §6, `[Statutory]`) — continuous reassessment rather than a periodic renewal cycle |
| Mid-term fresh-filing triggers | Order No. 11 Art. 14 (carried forward under Order No. 16 per china §6, `[Interpretive]`): change in purpose/method/scope/categories of the export or the recipient's processing; extension of overseas retention; change in the recipient jurisdiction's data security law, policy or network security environment; force majeure; change of control of either party; change to the governing legal documents; or any other circumstance affecting security (china §6, `[Statutory]`) | Clause 14(e)/(f): importer must notify on a change in law or practice, or a disclosure request evidencing one; exporter must then suspend if no safeguard can be ensured (eu §6, `[Statutory]`) |

**Reading the table.** The one genuinely parallel row is the top one, and it
does not actually pair up: China has no government-level periodic review to
compare against the EU's four-year adequacy cycle, because China has no
adequacy-equivalent mechanism at all (§2 above). Where a real parallel does
exist — the PRC security assessment's fixed 3-year term against the EU's
complete absence of any fixed term for SCCs — the honest comparison is a
contrast, not a match: China runs its highest-tier route on a calendar; the
EU runs its default safeguard on continuous monitoring with no expiry date.
The mid-term triggers list is the closest genuine likeness in this section —
both regimes tie a fresh look to materially the same categories of change
(law of the destination country, control of the parties, the governing
contractual documents) — though china §6 states its list as a numbered,
statutory enumeration (Order No. 11 Art. 14) while the EU's is built from two
contractual clauses (Clause 14(e)–(f)) rather than a statutory list.

---

## 9. Where the analysis stops being data protection

**China — localisation and important data pull the analysis into CSL/DSL
territory.** `china/routes.md` §1 documents three points at which the
question stops being "how do we lawfully export personal information" and
becomes a data-security or localisation question governed by a different
instrument:

- CSL Art. 39 (renumbered from Art. 37 by the 2025 amendment, china §1,
  `[Statutory]`): CIIOs must store personal information and important data
  collected/generated in their PRC operations **within China**; export, where
  needed, goes through a CAC-organised security assessment. This is a
  localisation rule, not a transfer-mechanism rule — it operates before the
  Art. 38 PIPL routing question is even reached for a CIIO.
- DSL Art. 31 (china §1, `[Statutory]`): important-data export by CIIOs is
  governed by the CSL; for other processors, by CAC/State Council measures —
  routing important data through a track that sits alongside, not inside,
  the personal-information routes of Order No. 16.
- PIPL Art. 40 (china §1, `[Statutory]`): CIIOs, and non-CIIO processors
  above a CAC-specified volume, must store PRC-collected personal
  information domestically. The triggering volume for non-CIIOs is
  `[Unsettled]` — "No instrument retrieved specifies it" (china §1).
- Practically, important data does not get its own separate track once
  triggered: Order No. 16 Art. 7(2) folds it straight into the mandatory
  security-assessment route with no volume threshold (china §4,
  `[Statutory]`). What stays genuinely open is the **classification**
  question upstream of that — whether a given dataset *is* important data at
  all, which china §2 describes as running on a notification-based safe
  harbour (Order No. 16 Art. 2) layered under the DSL Art. 21 catalogue
  system, with real gaps flagged `[Unsettled]` (e.g., whether unnotified data
  that plainly fits an announced sectoral description can still rely on the
  safe harbour).

**EU/EEA — member-state employment law is scoped out, not analysed.**
`eu/chapter-v.md` §1 states its own boundary directly, in an unlabelled scope
note rather than a labelled statement of instrument text: the file "covers
Chapter V of Regulation (EU) 2016/679... It does not cover Regulation (EU)
2018/1725..., the Law Enforcement Directive, or any national implementing
law" (eu §1). Member-state employment law
— the layer where, in a GDPR system, national labour-law derogations and
implementing provisions typically sit — falls inside that excluded category.
`eu/chapter-v.md` contains no analysis of it, because the file was scoped not
to reach it, not because the question was researched and found settled or
open.

**Why this pairing is asymmetric, and that asymmetry is itself the finding.**
On the China side, the employment/HR question is squarely *in scope* and
analysed: Order No. 16 Art. 5(2) exempts cross-border HR management from all
three routes where it rests on lawfully adopted labour rules **and** a
lawfully concluded collective contract, with two `[Unsettled]` points flagged
— whether a collective contract is strictly required where none exists, and
CAC guidance on recruitment-necessity that treats the overseas entity's
participation in the hiring decision as controlling (china §3, `[Statutory]`
for the exemption text, `[Interpretive]`/`[Unsettled]` for the gloss). On the
EU side, the comparable question — how member-state employment law modifies
or supplements Chapter V for HR data — is not in `eu/chapter-v.md` at all; it
was excluded by the scope note rather than addressed and found clear or
unclear. That is not a gap this file can fill by researching EU employment
law fresh — doing so would make `comparison.md` a third, unsourced source,
which the brief for this file rules out. The honest statement is: this
question is answered for China and marked `[To be verified — outside the
scope of eu/chapter-v.md]` for the EU side, pending a file that actually
covers member-state implementing law.

---

*Research material, not legal advice. Built entirely from `china/routes.md`
(verified 2026-09-13) and `eu/chapter-v.md` (verified 2026-09-15); no
independent verification was performed for this file. Recheck all three
files' source material before relying on any of it.*
