# Still Tide privacy and support site

Static source for Thomas Gorup's personal Still Tide app information pages.

Planned public URLs:
- Privacy: https://tide.cybrpulse.com/
- Support: https://tide.cybrpulse.com/support.html

The app itself is offline; these pages separately disclose website connection logs and support email handling. They were prepared from the app's Release/privacy-draft.md, Release/support-draft.md, and data-flow audit on October 10, 2026. The approved privacy@cybrpulse.com and support@cybrpulse.com routing aliases are shared with Tom's other personal app sites. No new personal address is published.

This source is buildless HTML/CSS. Run python3 -m http.server 8080 here for local preview. The public repository is [Tom-Gorup/still-tide-site](https://github.com/Tom-Gorup/still-tide-site); GitHub Pages deploys main/root and reads the tracked CNAME for tide.cybrpulse.com. The Cloudflare DNS-only CNAME to tom-gorup.github.io and HTTPS enforcement are still pending the required DNS approval. Verify the final HTTPS pages and links before giving the URLs to the app owner to wire into a future build.

The CybrPulse subdomain is for information and routed contact only; no Apple seller status is asserted. Review the policy when the app's data flow changes, especially if a future build adds hosted links, telemetry, an account, or a support form.
