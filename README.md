# Still Tide privacy and support site

Static source for Thomas Gorup's personal Still Tide app information pages.

Planned public URLs:
- Privacy: https://tide.cybrpulse.com/
- Support: https://tide.cybrpulse.com/support.html

The app itself is offline; these pages separately disclose website connection logs and support email handling. They were prepared from the app's Release/privacy-draft.md, Release/support-draft.md, and data-flow audit on October 10, 2026. The approved privacy@cybrpulse.com and support@cybrpulse.com routing aliases are shared with Tom's other personal app sites. No new personal address is published.

This source is buildless HTML/CSS. Run python3 -m http.server 8080 here for local preview. To publish, use a GitHub Pages repository on main/root, enable Pages, and set its custom domain to tide.cybrpulse.com. The Cloudflare DNS-only CNAME to tom-gorup.github.io and HTTPS enforcement require separate DNS and Pages configuration approval. Verify the final HTTPS pages and links before giving the URLs to the app owner to wire into a future build.

The CybrPulse subdomain is for information and routed contact only; no Apple seller status is asserted. Review the policy when the app's data flow changes, especially if a future build adds hosted links, telemetry, an account, or a support form.
