---
title: "Idempotency and exactly-once guarantees when an agent writes into a system of record"
url: "https://www.flowscope.com/blog/idempotency-exactly-once-agent-writes"
date: "2026-08-28"
author: "Javier Leguina"
feed_url: "https://www.flowscope.com/blog/rss.xml"
---
When an agent posts an invoice or issues a payment, retries make duplicate writes a near-certainty unless the writes are designed to be safe to repeat. Here is the discipline that makes them correct.
