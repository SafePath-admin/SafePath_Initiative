SafePath Canonical Extraction Prompt
FINAL — Reusable
Copy and paste everything below into the source chat.
___________________________

PROMPT START

You are assisting with the consolidation of information for an initiative called SafePath.

This conversation may be one of multiple chats being reviewed for consolidation into a structured, authoritative workspace. The original chat may be archived after this extraction.

Your task is to extract:
1. Finalized SafePath-related content, along with its necessary supporting information,
2. Relevant but undeveloped SafePath-related concepts for preservation in the Conceptual Backlog (Non-Canonical),
3. All available timestamp and temporal information relevant to legacy records, and
4. Any historical claims that are unverified, disputed, or uncertain, which must be preserved as UNVERIFIED Progress Log entries.

You must also explicitly identify:
- which PLATFORM the content belongs on (ChatGPT, Dropbox, GitHub),
- the exact FOLDER and SUBFOLDER it should be placed in,
- OR whether a NEW SUBFOLDER should be created (and why).

Accuracy, restraint, correct routing, and preservation of uncertainty are critical.

--------------------------------
SafePath Platform, Folder & Subfolder Hierarchy (Reference)
--------------------------------

CHATGPT — Structured Workspace (Primary)
01. Progress Log
02. Core Framework & System Architecture
03. Brand Language & Narrative
04. Visual Identity & Logo System
05. Digital Infrastructure
06. Legal, IP & Governance
07. Funding & Sustainability
08. Founder Reflections & Legacy
09. Conceptual Backlog (Non-Canonical)
UTILITIES (process tools only)

--------------------------------

DROPBOX — Working Archive (Secondary)

01_Progress_Log/
  - Master_Progress_Log_Working/
  - Exports_PDF/

02_Core_Framework/
  - Working_Notes/
  - Diagrams/
  - References/

03_Brand_Language/
  - Drafts/
  - Brand_Book/
  - Messaging/

04_Visual_Identity/
  - Logos_Working/
  - Logos_Final/
  - Style_References/

05_Digital_Infrastructure/
  - Website/
  - Anonymous_Chat/
  - App_References/

06_Legal_Governance/
  - Patents/
  - NDAs/
  - Statutes/
  - Counsel_Correspondence/
  - Operational_Prompts/

07_Funding_Sustainability/
  - Budgets/
  - Funding_Pitches/
  - Grants/

08_Legacy_Reflections/
  - Personal_Notes/
  - Legacy_Drafts/

09_Conceptual_Backlog/
  - Notes/
  - Sketches/
  - Deferred/

--------------------------------

GITHUB — Canonical Record (Final Truth)

- Contains ONLY finalized, authoritative material
- Mirrors top-level structure (01–09)
- Does NOT store drafts, brainstorming, or conceptual backlog content
- Conceptual Backlog exists ONLY as a disclaimer README
- New subfolders may be created ONLY if required by finalized scope

--------------------------------
Rules (Strict)
--------------------------------

A. Finalized Content
- Extract ONLY finalized decisions, definitions, positions, agreements, or locked conclusions
- Include supporting information ONLY if required to preserve intent, scope, or constraints
- Do NOT reinterpret, improve wording, or introduce new ideas
- If something is ambiguous or not clearly finalized, EXCLUDE it from finalized content

B. Conceptual Backlog Candidates (Non-Canonical)
- Extract ideas that are relevant but NOT finalized or approved
- Treat them as non-authoritative
- Do NOT advance, resolve, or advocate for them

C. Legacy & Timestamp Requirements
- Extract ALL explicit timestamps, dates, or temporal references
- Note stated dates, disputed dates, uncertainty, or gaps
- Do NOT infer or guess missing dates

D. UNVERIFIED Historical Claims
- If a historical claim (e.g., origin date, first use of a term, early milestone) is:
  - not source-verified,
  - explicitly questioned,
  - or internally inconsistent,
  it MUST be preserved as an UNVERIFIED item.
- UNVERIFIED items are NOT discarded.
- They must be routed to the Progress Log and explicitly labeled “UNVERIFIED”.
- They must NOT assert truth or be treated as canonical.
- Preserve why the claim is unverified (e.g., memory conflict, lack of documentation).

E. Subfolder Creation Rules
- If content clearly fits an EXISTING subfolder, route it there
- If no existing subfolder is appropriate:
  - Recommend creation of a NEW subfolder
  - Provide a short justification
- Do NOT recommend new top-level folders

F. Exclusions
- Raw brainstorming without coherent conclusions
- Superseded drafts
- Tangential discussion unrelated to SafePath

--------------------------------
Output Format (Required)
--------------------------------

SECTION A — Finalized SafePath Content Extract
Source Chat Identifier: (chat title + approximate date)

Item 1
Topic / Domain:

Finalized Content:
- Bullet-point finalized decisions

Supporting Information (if required):
- Brief bullets preserving intent or constraints

Required Transfer Destination:
- Platform:
- Folder:
- Subfolder:
- New Subfolder Required: YES / NO
  - If YES, proposed name and justification

Timestamp / Legacy Notes:
- Dates stated:
- Dates disputed:
- Certainty level: Confirmed / Disputed / Unknown

(Repeat Section A for each finalized item)

--------------------------------

SECTION B — Conceptual Backlog Candidates (Non-Canonical)

Route ALL items in this section to:
ChatGPT: 09. Conceptual Backlog (Non-Canonical)
Dropbox: 09_Conceptual_Backlog/

For each item provide:
- Concept Name:
- Concept Summary (1–3 sentences):
- Context / Rationale:
- Status Tag: Unexplored / Deferred / Rejected / Promotable (requires governance review)

--------------------------------

SECTION C — UNVERIFIED Historical Claims (For Progress Log)

For each unverified claim provide:
- Claim Description:
- Claimed Date or Period:
- Reason Unverified:
- Who Disputed or Raised Concern:
- Required Transfer Destination:
  - ChatGPT: 01. Progress Log
  - Dropbox: 01_Progress_Log/Master_Progress_Log_Working

These items must be clearly labeled “UNVERIFIED” and must not assert fact.

--------------------------------

SECTION D — Items Explicitly Not Extracted

- List excluded items with brief reasons (e.g., not finalized, superseded, speculative)

--------------------------------

If no finalized content, conceptual backlog items, or unverified historical claims exist, state clearly:

“No SafePath-relevant canonical, conceptual, or legacy content identified in this conversation.”

PROMPT END


___________________________

After You Run This Prompt

Copy the full output

Paste it here with:

External SafePath extract — ready for integration.

Archive the source chat if you wish — nothing essential will be lost

I will then:

Integrate Section A into canonical chats (if approved)

Route Section B into 9. Conceptual Backlog (Non-Canonical)

Explicitly accept, defer, or reject each item — nothing silently
