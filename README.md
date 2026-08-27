# Devadex Exhibition Hall OS

An offline management system for exhibition halls and trade-show venues: floor plans and stand allocation, exhibitor contracts, a service catalogue with orders, and build-up and breakdown scheduling.

## What it does

- **Floor plans and stand allocation.** Halls are defined with a name and total floor area in square metres, and an optional loading dock capacity (maximum simultaneous crews).
- **Exhibitor contracts.** Exhibitors are recorded with company name, contact name, email, and phone.
- **Service catalogue and orders.** A reusable catalogue of services (for example: power drops, internet, furniture, cleaning, rigging) is defined once, each with a name, unit, price, and category.
- **Build-up and breakdown scheduling.** Time slots for move-in (build-up) and move-out (breakdown) crews are booked per stand, with a crew name attached.
- **Utilities billing.** Meter readings (start and end) are recorded per stand for electricity, water, or compressed air.
- **Invoicing.** An invoice for a given contract combines: the stand fee, every service order tied to that stand and event, and every utility charge tied to that stand and event, less any deposit already...
- **Web dashboard.** Started with a serve command; listens on a local port (default 4600, overridable).
- **Command-line interface.** A single entry point (bin/exhibitionhallos.js) exposes every function above as a subcommand (hall, stand, event, exhibitor, contract, catalog, service, schedule, utility, invoice, serve,...

## Who it is for

A venue operator managing exhibitors and stands by hand.

---

Available for acquisition as an outright transfer of ownership.

This repository is **documentation only**. It describes what the product is, what has been
measured, and what is known to be incomplete. It contains no source code. See
[LICENSING.md](LICENSING.md).

---

## What is included

One finished product.

| Product | Scale |
|---|---|
| Devadex Exhibition Hall OS | 26 tests |

Feature-by-feature detail is in [PRODUCTS.md](PRODUCTS.md).

## Measured

| Measure | Value |
|---|---|
| Tests passing | 26 |
| Tests failing | 0 |
| Tests skipped | 0 |
| Files delivered | 19 |
| Authored lines | 1,733 |

Every figure came from running the software while the data room was prepared, and a buyer can
reproduce each one from the delivered files. Method and known gaps are in
[VERIFICATION.md](VERIFICATION.md).

## How it is sold

Outright transfer of ownership, sold as is. No ongoing maintenance or support obligation, and no
licence-back, so the seller keeps nothing that depends on it.

A full data room is available under a signed non-disclosure agreement: product inventory,
provenance, third-party notices, the complete verification record, and an open-items document
listing every known gap. See [ACQUISITION.md](ACQUISITION.md).

## Documents

| Document | What is in it |
|---|---|
| [PRODUCTS.md](PRODUCTS.md) | Every product, described |
| [VERIFICATION.md](VERIFICATION.md) | What was measured, how, and what is not proven |
| [LICENSING.md](LICENSING.md) | Proprietary status, and what this repository is |
| [ACQUISITION.md](ACQUISITION.md) | How to open a conversation |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Why code contributions are not taken |

---

Jesse Duncan, doing business as Devadex Labs. Proprietary; all rights reserved.
