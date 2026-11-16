# jolantaenko.github.io

Personal research website of Jolanta Enko (SWPS University, Poznań). Live at https://jolantaenko.github.io

## Files

- `index.html`: the homepage, a single self-contained page with all styles inline. Sections in order: header, student links bar (Polish), ORCID and email row, Research, Grants, Papers (psychology, grouped by year, newest first), Earlier work (biology and commodity science), Background.
- `nissel-enko-2026-relationship-satisfaction.html` + `.pdf`: a paper page with an accepted manuscript. Use it as the template for any future accepted-manuscript page.
- `sitemap.xml`: list every page here and update `lastmod` when a page changes.
- `robots.txt`: points search engines to the sitemap.

## Adding a new paper

1. Add an `<article class="paper">` entry in `index.html` under the right year in Papers (or Earlier work), and update the count in that section's heading. Bold Jolanta's name with `<b>Enko, J.</b>`.
2. If there is a free accepted manuscript (AAM):
   - Name the files `firstauthor-secondauthor-year-short-title.pdf` and `.html`.
   - Copy the existing paper page and replace the `citation_*` meta tags (these are what Google Scholar reads), the title, authors, abstract, keywords, citation and the publisher's posting statement.
   - In `index.html`, point the paper's title to its new page and add a "Free PDF (accepted manuscript)" link.
   - Add the new page to `sitemap.xml`.
3. Check the publisher's self-archiving rules in Open Policy Finder first. Repositories such as the SWPS repository are often under embargo, while personal websites may be allowed sooner.
4. After uploading, request indexing for the new page in Google Search Console.

## Editing

Upload files on github.com with **Add file → Upload files** (files with the same name are replaced). The site updates within a minute or two; reload it with Ctrl+Shift+R.

Style: keep the existing colour tokens and fonts (Bricolage Grotesque, Inter, IBM Plex Mono). Light and dark themes are both defined in the `:root` blocks.
