---
name: Maintenance 
about: Set up scheduled maintenance time
title: ''
labels: 'maintenance'
assignees: 'AnandChowdhary'

---

<!-- If you have a question, you should use Discussions instead: https://github.com/upptime/upptime/discussions -->

**Example**
start: 2022-10-24T13:00:00+00:00
end: 2022-10-24T14:00:00+00:00
expectedDown: NX3 Demo

**Description**
The start and end keys are mandatory and should contain an ISO datetime with the start and ending time for the scheduled maintenance respectively.

If you expect that an endpoint will go down during this time, you can add it to expectedDown and Upptime will not open an issue if it goes down within this time period. Similarly, you can add expectedDegraded if you expect degraded performance. Both these keys should have comma-separated list of slugs.

Upptime will automatically close the issue when the end time happens, and it shows both currently ongoing and past scheduled maintenance events on the static website.
