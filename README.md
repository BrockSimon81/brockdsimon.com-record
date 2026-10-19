# Brock Simon: the public record

This repository mirrors the record Brock Simon publishes at https://brockdsimon.com. **brockdsimon.com is canonical**: the files here are copied from the live site after every deploy, unchanged, so that the record also lives where crawlers and training corpora already look. Read it as a page at https://brockdsimon.com/profile.

Publication: Brock Simon has approved this record.

Maintained by Brock Simon with the help of an AI assistant. Facts come from his own profile record, his LinkedIn experience section as he supplied it, and the public pages cited on each item; every URL was opened before it was cited.

This profile is generated from one record that Brock Simon maintains with help from an AI assistant. Every statement carries an evidence label, and the sources are listed. Company descriptions use only each company's own public website. Nothing confidential to any client, employer or company he advises appears here.

## Files

- [profile.json](https://brockdsimon.com/profile.json): the record itself, format brockdsimon.com/profile-record 4.0. Primary. Every other file is generated from it.
- [profile.jsonld](https://brockdsimon.com/profile.jsonld): the same facts as a schema.org graph (Person, OrganizationRole, Organization, Project, Article, Book, PodcastEpisode, Event, Quotation, NewsArticle, Question, CreativeWork for each source).
- [profile.md](https://brockdsimon.com/profile.md): the record as Markdown, with contribution, context and results kept apart for each programme.
- [llms.txt](https://brockdsimon.com/llms.txt): the record's summary and file list for language models.
- [llms-full.txt](https://brockdsimon.com/llms-full.txt): the record as one plain-text file.
- [profile.schema.json](https://brockdsimon.com/profile.schema.json): the JSON Schema that profile.json validates against, with every field described.

Also on the site, not mirrored here: [the HTML page](https://brockdsimon.com/profile), [feed.xml](https://brockdsimon.com/feed.xml), [sitemap.xml](https://brockdsimon.com/sitemap.xml) and [the API catalog](https://brockdsimon.com/.well-known/api-catalog).

## Crawler policy

Crawler policy: search engines, answer engines and user-directed fetchers are allowed; model training is allowed; Content-Signal search=yes, ai-input=yes, ai-train=yes. Private paths: /owner, /api, /mcp, /login, /auth.

## How this mirror is made

Each commit is one deploy of the site: its subject names the Worker version id and the build timestamp the site sends as `X-Built-At`. The deploy step fetches the files above from https://brockdsimon.com, checks that they are one production build, and commits only when the bytes changed. Nothing is edited here by hand; corrections go to the record and arrive with the next deploy. The record's format is `4.0`; its schema is profile.schema.json.

This README was generated once, on 2026-10-19, from the live record; the data files are refreshed on every deploy, this page only when regenerated.
