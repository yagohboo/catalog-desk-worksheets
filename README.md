# The Catalog Desk — practical CSV worksheets

Four free, manual worksheets for reviewing a product catalog, recording extra project work, planning a wholesale collection, and keeping an event cue sheet. Each worksheet includes a blank CSV and a clearly labeled fictional example.

Use the files in your usual spreadsheet application. They contain **no formulas, macros, automatic calculations, or connections to an online service**. No paid app or AI service is needed to use them.

[Browse the worksheet library and download the complete starter pack](https://catalog-desk-resources.silentsnake2003.chatgpt.site?utm_source=github&utm_medium=resource_repository&utm_campaign=free_worksheets).

**Direct download:** [Get all four free worksheets and examples as one ZIP](https://github.com/yagohboo/catalog-desk-worksheets/releases/download/worksheets-v1.0.0/The-Catalog-Desk-Free-Starter-Kit.zip). No signup is needed. [Release notes and file checksum](https://github.com/yagohboo/catalog-desk-worksheets/releases/tag/worksheets-v1.0.0).

## Choose a task

| Task | Start with | See a filled example |
| --- | --- | --- |
| Record questions before a product catalog update | [Catalog review checklist](worksheets/catalog-review-checklist.csv) | [Fictional catalog review](worksheets/catalog-review-checklist-fictional.csv) |
| Estimate and record work outside a project's agreed scope | [Scope change worksheet](worksheets/scope-change-worksheet.csv) | [Fictional scope changes](worksheets/scope-change-worksheet-fictional.csv) |
| Review wholesale quantities, prices, minimums, and case sizes | [Wholesale collection worksheet](worksheets/wholesale-collection-worksheet.csv) | [Fictional wholesale collection](worksheets/wholesale-collection-worksheet-fictional.csv) |
| Plan event cues and trace the effect of a rehearsal overrun | [Run of show cue sheet](worksheets/run-of-show-cue-sheet.csv) | [Fictional event cue sheet](worksheets/run-of-show-cue-sheet-fictional.csv) |

The catalog blank contains eight review questions. The other blank files contain headers and an empty row. The example files contain invented projects, products, people, and decisions; they are not customer records or instructions to act on a real store.

## Start in five steps

1. Open a blank file's link above and save its raw CSV contents, or download the complete starter pack from the worksheet library. Keep the fictional example unchanged as a reference.
2. Import the CSV into your spreadsheet application. Set identifier columns such as `sku` to **text** before import when leading zeroes matter. Spreadsheet applications may otherwise change `000101` to `101`.
3. Replace or add rows with your own information. Enter calculated amounts and times yourself; example results are typed values, not formulas.
4. Save a separate copy for each project, review, collection, or event. If you add formulas or formatting, keep an editable workbook copy as well: CSV does not preserve workbook formatting or multiple sheets.
5. Review the results and any private client or supplier information before sharing. Keep collaborators on the same current version.

Need help with the import? [Open a CSV worksheet without losing leading-zero IDs](https://catalog-desk-resources.silentsnake2003.chatgpt.site/guides/open-csv-worksheet) walks through text handling, a one-row check, and saving a working copy. Compare imported identifiers with your untouched source; changing the display format afterward does not recover a changed identifier.

## Catalog review checklist

Use this checklist to record questions about an unchanged current export and a proposed update before deciding what to do. Keep both source files, list the changes you intend, and record evidence and a next action for every unresolved item.

In the fictional example, a price moves from `24.00` to `30.00`. The increase is `6.00`, and `(30.00 - 24.00) / 24.00 × 100 = 25%`. Other findings include a changed SKU, a previously populated vendor becoming blank, a price becoming blank, and an absent option combination.

This is a **review checklist, not a Shopify product import template**. Do not upload it or its fictional example into your store. It does not validate an import or inspect a live store. An absent variant does not by itself establish deletion, and zero reported errors does not mean there are no unresolved issues. Check each finding against your intended change list.

## Scope change worksheet

Start by recording the agreed project baseline. For each extra request, write what is included, estimate the minutes, enter the hourly rate and currency, and retain a decision reference.

Calculate each amount as `estimated minutes / 60 × hourly rate`. Round each request to the nearest currency cent, then sum line amounts by the status you need to review.

The fictional website project has three requests:

| Request | Calculation | Recorded status |
| --- | --- | --- |
| Add a journal landing page | `240 / 60 × 85.00 = 340.00 USD` | Proposed |
| Prepare a second homepage concept | `90 / 60 × 85.00 = 127.50 USD` | Approved |
| Write all service-page copy | `180 / 60 × 85.00 = 255.00 USD` | Declined |

Proposed work totals `340.00 USD`; recorded-as-approved work totals `127.50 USD`. The declined request is excluded from both totals. Statuses are manual records, not authenticated client approval. Amounts exclude taxes and fees. The worksheet is not a contract, invoice, or billing service.

**Prefer Notion for scope changes?** [Use the free Scope Change Log for Freelancers](https://verbena-concrete-a09.notion.site/Scope-Change-Log-for-Freelancers-3fb88db589cc80efb8a7dd245a7f1aa1). It includes a project baseline, manual estimates, three fictional requests, and separate Proposed, Recorded approved, and Declined views. Duplicate the whole page for one project and clear the samples before use. A Notion account is needed to duplicate it into your workspace; this is a separate online template, not a file in the CSV ZIP. Amounts are entered manually, and recorded statuses do not authenticate client consent. It is not a contract or invoice.

## Wholesale collection worksheet

Record a product's wholesale price, suggested retail price, minimum units, case size, and requested quantity. Calculate each line subtotal as `order quantity × wholesale unit price`. Check minimum quantities and case multiples independently.

The fictional order selects six cups at `12.50 USD` and four bowls at `18.00 USD`: `6 × 12.50 + 4 × 18.00 = 147.00 USD` before tax and shipping. No vases are selected. Verify your own stock and commercial terms before taking an order.

This worksheet does not check stock, place orders, accept payment, embed product photos, or convert currencies. It is a manual companion, not a promised import format for another app or store.

## Run of show cue sheet

Give each cue an owner, planned duration, buffer, and crew note. Starting from the event's agreed start time:

- Next planned start = prior planned start + planned duration + buffer.
- Next projected start = prior projected start + (measured actual duration if entered, otherwise planned duration) + buffer.

In the fictional event, arrival takes `27` minutes instead of `25`, and the welcome takes `6` instead of `5`. The remaining cues keep their planned durations. The event therefore moves from a planned `20:02` finish to a projected `20:05` finish, three minutes later.

A blank actual duration means it has not been recorded; an entered zero is a different value. These are manual wall-clock calculations, not live countdowns or time-zone/daylight-saving conversions. If a schedule crosses midnight, record its day and date explicitly in your own copy. Keep the current crew version aligned.

## Optional structured tools

The worksheets work independently. If you need structured entry, checks, and exports, the [worksheet library also describes the separate paid browser tools](https://catalog-desk-resources.silentsnake2003.chatgpt.site?utm_source=github&utm_medium=resource_repository&utm_campaign=free_worksheets). The paid applications and their source code are not included here. No purchase is required to use this collection.

Catalog Change Review is an independent product and is not affiliated with, endorsed by, or supported by Shopify. None of these worksheets or tools guarantees a business, financial, or event outcome.

## Use and support

The original starter pack instructions and terms are preserved in [worksheets/README.txt](worksheets/README.txt). Their **USE AND SUPPORT** section is reproduced here without changes:

> You may copy, adapt and use these free worksheets for your own work and client work, and share your completed worksheets with collaborators. Keep fictional examples labeled when sharing them. This starter pack does not include the paid applications or grant redistribution rights to those applications.
> Support: https://payhip.com/TheCatalogDesk/contact
> Include the worksheet or product name and a small fictional example when reporting a problem; avoid sending private client or supplier data.

These are the supplied worksheet usage terms; this repository does not add a separate software license or expand the rights to any paid application.
