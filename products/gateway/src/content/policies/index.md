---
title: "Policies"
alwaysopen: true
weight: 3
hidden: true
---

import gatewayCreatePolicy from '../static/gateway-create-policy.gif'

Cloudflare Gateway's policy engine allows you to block domains by categories, manually block domains and override domains to allow them even if those domains are getting blocked by a category. You can assign a policy to one or multiple locations. 

<img src={gatewayCreatePolicy} alt="create gateway policy" />

[Blocking a domain](/gateway/policies/blocking-a-domain)
See how you can block a domain using the policy engine.

[Blocking domains by category](/gateway/policies/blocking-domains-by-category)
Shows how you can block a group of domains or multiple groups of domains using category based DNS filtering.

[Configuring a block page](/gateway/policies/configure-block-page) See how you can show a block page when a website is blocked by Gateway.

[Adding a domain to the allow list](/gateway/policies/adding-a-domain-to-the-allow-list)
See how you can force resolve a domain even if the domain is getting blocked by another policy.

[Blocking all subdomains](/gateway/policies/blocking-all-subdomains)
Provides examples of how you can block subdomains 

[Troubleshooting Policies](/gateway/policies/troubleshooting-policies)
Check out the most common issues you may face when you are setting up a policy.