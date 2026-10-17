# Backlink Verification & Indexability Checklist

A practical checklist for SEO professionals, freelancers, agencies, link builders, and website owners who need to review backlinks that have already been created.

This project focuses on **operational backlink checks**—not Domain Authority (DA), Page Authority (PA), or other third-party authority scores, and not guarantees of Google indexing.

## What it helps you review

- Whether the backlink is present on the source page
- Whether the link points to the intended destination URL
- Link attributes: `nofollow`, `sponsored`, and `ugc`
- Anchor text and link target
- Source-page HTTP response and accessibility
- Page-level robots directives and `X-Robots-Tag` where verifiable
- `robots.txt` restrictions and canonical URL signals
- Whether the source page appears technically eligible for crawling/indexing
- Follow-up actions for missing, blocked, or unsuitable links

## Files

- `index.html` — browser-based interactive checklist with progress tracking, CSV export, and print/PDF support
- `css/style.css` — responsive styling and print styles
- `data/backlink-verification-checklist.csv` — spreadsheet template for documenting backlink checks
- `LICENSE` — MIT License

## Getting started

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Review each check and mark its status.
4. Use the notes field to record evidence, source URLs, or next actions.
5. Export a CSV or print/save the checklist as a PDF.

No build tools or package installation are required.

## Recommended workflow

1. Collect the list of backlink source URLs and intended target URLs.
2. Check whether each source page is accessible and the link is present.
3. Verify the destination, anchor text, and link attributes.
4. Review indexability signals, including robots directives and canonicalization.
5. Classify each backlink as **OK**, **Needs Review**, **Blocked**, or **Missing**.
6. Fix what is within your control, contact the publisher when appropriate, and recheck later.

## Important limitations

- A technically crawlable or indexable page is **not guaranteed** to be indexed by Google.
- Search operators and search results are not a definitive, complete index-status API.
- `nofollow`, `sponsored`, and `ugc` are link attributes that search engines may use as hints; they do not by themselves prove whether a page is indexed.
- A `robots.txt` block can prevent crawling but does not necessarily prevent a URL from appearing in search results.
- Canonical tags are signals, not absolute guarantees. A canonical pointing elsewhere may affect which URL a search engine selects.
- Checks may vary by CMS, hosting environment, redirects, JavaScript rendering, access restrictions, and publisher implementation.
- This checklist does not calculate DA/PA or promise ranking improvements, link value, or indexing.
- Respect website terms, robots policies, and applicable laws when checking URLs.

## Useful resources

- **WEB HOST PUNE:** https://www.webhostpune.com/
- **Backlink Analysis Tool:** https://tools.webhostpune.com/
- **Ajit360View — 360° Virtual Tours:** https://ajit360view.com/

The WEB HOST PUNE Backlink Analysis Tool is intended to help users inspect existing backlink URLs and review practical signals such as link presence, link attributes, indexability-related directives, HTTP status, anchor text, and canonical signals. Available checks can depend on the target website and tool implementation.

## Contributing

Suggestions and corrections are welcome. Please keep checklist items practical, evidence-based, and clear about what can and cannot be verified.

## License

This project is released under the MIT License. See `LICENSE`.
