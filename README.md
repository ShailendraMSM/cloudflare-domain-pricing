Why does Cloudflare not publicly list all domain prices like other registrars?
------------------------------------------------------------------------------

Many domain registrars list all the TLDs they offer available for users' convenience.

Such lists generally contain registration, transfer, renewal prices, and other terms for all their TLDs.

It is a good resource for their customers and good marketing, especially if their prices are very competitive.

However, despite being the most competitive of them all, Cloudflare does not publish pricing information in their list of supported[ TLDs](https://www.cloudflare.com/tld-policies/).

There is an interesting reason behind that.

When registering a domain, three parties are involved: [the Registry, the Registrar, and You (the Registrant)](https://support.netim.com/en/docs/general-public/domain-name/registry-registrar-registrant-how-does-it-work).

The domain is actually registered with the registry of that TLD. For that, the registry charges a wholesale price for every domain.

Most good registrars, like Dynadot, add a markup of about 5%-15% of the wholesale price.

#### Example

So when you (Registrant) pay $10.19 for a .com registration to Dynadot (Registrar)\
$0.18 goes to ICANN (central authority)\
$9.59 goes to Verisign (Registry) and\
$0.42 remains with Dynadot (Registrar).

While the registrar has to bear the payment processing charges, provide customer support, and run promotions out of that tiny margin, the registry keeps most of the share from your payment.

So, to avoid bad publicity, many registries mandate in the registry-registrar agreements that they can't disclose the wholesale prices of the domains to customers.

So, though registrars can show off their domain pricing, they can not disclose the wholesale pricing publicly.

The problem with Cloudflare is that their prices ARE the wholesale prices.

So, if they publish their domain pricing, they would indirectly publish the wholesale pricing of all TLDs and violate several agreements.

Hence, they simply do not publish a list of all domains with pricing.

### How did I collect this data on Cloudflare domain pricing

In the past, it was possible to use Cloudflare API to programmatically extract prices of all supported TLDs.

This is an example of such a [script](https://github.com/judge2020/CloudDump).

But it clearly does not work anymore. It means that all such lists are outdated.

So I dug into various sources for wholesale pricing of domains and manually verified prices of randomly selected TLDs on the Cloudflare domain registration page for accuracy.

In fact, using this method, I have even predicted the pricing of upcoming TLDs.

This list would be 99% accurate at the time of publishing.

[Complete table of all Cloudflare-supported domains price list](https://www.worthyblog.com/cloudflare-domain-pricing-complete-list/)
-------------------------------------------------------------
