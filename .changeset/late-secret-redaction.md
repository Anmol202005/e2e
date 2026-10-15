---
"e2e": patch
---

Step records and app logs are rechecked against provider-backed secrets when they are returned or written, including values and prefixes truncated before the provider resolved.
