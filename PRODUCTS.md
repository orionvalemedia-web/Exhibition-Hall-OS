# Devadex Exhibition Hall OS

The product in this package.

Every entry below is taken from the package's own documentation. Nothing here is a plan or a
roadmap item; all of it is built.

---

## Devadex Exhibition Hall OS

26 tests

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

### Who it is for

A venue operator managing exhibitors and stands by hand.

---

Full detail, including file-level inventory and provenance, is in the data room, available under a
signed non-disclosure agreement. See [ACQUISITION.md](ACQUISITION.md).
