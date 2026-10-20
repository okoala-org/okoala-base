<div align="center">
  <img src="https://cdn.iasoft.dev/okoala/logo.png" alt="OKoala Logo" width="190" style="border-radius: 1.15rem;"/>
  <br/>

  <img src="https://img.shields.io/badge/Email-darkred.svg" alt=""/>
  <img src="https://img.shields.io/badge/Chat-darkgreen.svg" alt=""/>
  <img src="https://img.shields.io/badge/Calendar-darkblue.svg" alt=""/>

  <p style="padding-top: 0.2rem;">
    <b>OKoala: Open Source Collaboration Platform</b>
  </p>
</div>

## Overview

This repository hosts the base code shared by both OKoala server and client. 
- JMAP Wire Types
- Calendar and Contacts Models
- Shared Protocol Logic

## Repository Layout

| Path | Contents |
|---|---|
| `crates/types` | JMAP wire types, JMAP Sharing, JMAP for Quotas, calendar/contacts capabilities, JSON Pointer, result references, patch objects |
| `crates/model` | JSCalendar and JSContact types, the JMAP Calendars and Contacts objects and methods |
| `crates/recurrence` | Recurrence expansion of JSCalendar events |
| `crates/wasm` | `wasm-bindgen` exports for the client |
| `ts/` | npm package `@okoala/base` |

## License

Copyright © 2026 IASoft (PVT) LTD.

Licensed under the [AGPL, version 3.0](https://www.gnu.org/licenses/agpl-3.0.en.html). See [COPYING](COPYING).

## Use of AI in this Project

Our engineers design each component. Claude (by Anthropic) writes most of the code,
and an engineer reviews it before it counts as reviewed.

Commits up to the one listed in [ni-review-log.md](ni-review-log.md) have been
reviewed by an engineer. Later commits have not yet been reviewed.
