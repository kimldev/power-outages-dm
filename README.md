# Dominica Power Outage Tracker

An independent, interactive dashboard of electricity reliability in Dominica, compiled from publicly available outage notices published by Dominica Electricity Services Ltd (DOMLEC).

## What it shows

The dashboard reads a structured log of power outages and presents it through three views:

- **Power Outages Across the Island** — grid-wide statistics: total outages, planned vs unplanned, average duration, on-time restoration rate, outages per month (with hurricane season highlighted), causes, duration distribution, and outages by parish.
- **Power Outages In Your Community** — pick a community to see how often the power goes out there, how long outages typically last, the planned/unplanned split, and whether restorations run on time.
- **Power Outage Data** — the underlying record, with the ability to inspect, edit, add, and export rows.

Figures including working hours lost and estimated total hours without power are derived from the notices and shown for the loaded data period.

## Data

The dashboard runs on a CSV of outage records. It opens with the current dataset built in, and the Load, Paste, and Download CSV controls let you update it with newer records over time. The data reflects outage notices up to the most recent date in the loaded file, not real-time status.

Sources: DOMLEC public WhatsApp channel (unplanned and emergency notices), the DOMLEC website (planned interruptions), and the DOMLEC Facebook page (corroboration and backfill). All times are Atlantic Standard Time (AST, UTC minus 4).

## Disclaimer

This dashboard is an independent, unofficial record compiled from publicly available outage notices published by Dominica Electricity Services Ltd (DOMLEC). It is not affiliated with, endorsed by, or maintained by DOMLEC. All figures, including durations, restoration times, and hours without power, are estimates derived from those notices and may be incomplete, delayed, or inaccurate. Many values are inferred or assumed where notices were unclear or absent. Nothing here should be relied upon for any operational, safety, medical, financial, or legal purpose. For authoritative and current information about any power outage, contact DOMLEC directly. This data is provided as is, without warranty of any kind, express or implied.
