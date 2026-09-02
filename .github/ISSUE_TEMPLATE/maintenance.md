---
name: Scheduled maintenance
about: Announce a planned work window on the public status page
title: "[Scheduled Maintenance] <Service> unavailable"
labels: 'maintenance'
assignees: ''

---

<!--
start: 2026-09-10T06:00:00.000Z
end: 2026-09-10T07:00:00.000Z
expectedDown: member-portal
expectedDegraded:
-->

<!--
The block above drives the status page — keep it. `start` and `end` are
required and must be UTC ISO-8601. `expectedDown` and `expectedDegraded` take
a comma-separated list of site slugs (member-portal, employer-portal,
provider-portal, platform-api); checks that fail inside the window are
attributed to the maintenance instead of opening an incident.

Everything below is PUBLIC. No member data in the title, body or comments.
-->

**What is changing**

**Who is affected**

**Expected impact**
