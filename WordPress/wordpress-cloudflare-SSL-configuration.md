{{{
  "title": "WordPress Cloud Flare SSL Termination",
  "date": "08-25-2015",
  "author": "Earl Herman",
  "attachments": [],
  "contentIsHTML": false
}}}
### IMPORTANT NOTE

There are multiple methods that could be used to terminate SSL for an existing CenturyLink Cloud WordPress site. This method covers using CloudFlare CDN's SSL Termination.

### This article assumes the following:

* Working knowledge of basic WordPress functionality

### Prerequisites:

1. A CenturyLink WordPress site
2. A Custom Fully Qualified Domain Name (FQDN) added to your WordPress Site.
3. An existing [CloudFlare] (https://www.cloudflare.com/) account 
4. Your customer site name must be configured for use with CloudFlare.
### CloudFlare Settings Supported

* SSL (with SPDY)						= Full, FLexible, or Off (Strict is not currently supported)
* HTTP Strict Transport Security (HSTS)
 * Max Age Header (max-age)			= Any Setting
 * Apply HSTS policy to subdomains	= On or Off
 * Preload								= On or Off
 * No-Sniff Header						= On or Off
* Authenticated Origin Pulls			= On or Off

Aditional [SSL related information] (https://support.cloudflare.com/hc/en-us/categories/200276247) on CloudFlare
