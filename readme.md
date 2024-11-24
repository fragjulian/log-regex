Real-world logs and corresponding regular expressions (RegEx).

Serves as an evaluation dataset for the paper "Lost in Translation? Converting RegEx for Log Parsing into Dynatrace Pattern Language".

---

Each folder contains one RegEx, corresponding matching log samples (_sampledx.txt or _samples.txt), optionally sanitized log samples (_ssampledx.txt), and non-matching log samples (_nsampledx.txt). 
The RegEx and log sources are listed below each RegEx.
The log entries are randomly sampled from the listed data sources (limited to max. 1,000).