---
pcx_content_type: configuration
title: Configure in the dashboard
weight: 4
meta:
  title: Configure the OWASP ruleset in the dashboard
---

# Configure the OWASP ruleset in the dashboard

You can configure the following settings of the Cloudflare OWASP Core Ruleset in the dashboard:

* **Set the [paranoia level](/waf/managed-rules/reference/owasp-core-ruleset/concepts/#paranoia-level).** The available levels are *PL1* (default), *PL2*, *PL3*, and *PL4*.
* **Set the [score threshold](/waf/managed-rules/reference/owasp-core-ruleset/concepts/#score-threshold).** The available thresholds are: *Low - 60 and higher*, *Medium - 40 and higher* (default), or *High - 25 and higher*.
* **Set the [action](/ruleset-engine/rules-language/actions/) to perform.** The action is executed when the calculated request threat score is greater than the score threshold. The available actions are: *Block* (default), *Managed Challenge*, *JS Challenge*, *Log*, and *Interactive Challenge*.
* **Disable specific rules or rules with specific tags.**
* **Customize the filter expression.** With a custom expression, the Cloudflare OWASP Core Ruleset applies only to a subset of the incoming requests.
* **Configure [payload logging](/waf/managed-rules/payload-logging/configure/)**.

For details on configuring a managed ruleset in the dashboard, refer to [Configure a managed ruleset](/waf/managed-rules/deploy-zone-dashboard/#configure-a-managed-ruleset).
