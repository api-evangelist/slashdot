# Slashdot

Slashdot (https://slashdot.org/) is a technology news aggregation and community discussion site founded in 1997, operating under the tagline "News for nerds, stuff that matters." The site focuses on open source software, Linux, science, and technology topics. Readers can submit stories, vote on submissions, and participate in threaded comment discussions with a scoring and moderation system. Slashdot is one of the earliest and longest-running technology news communities on the internet.

## RSS Feeds

Slashdot does not offer a traditional REST API, but provides RSS 1.0 and Atom 1.0 feeds for programmatic access to its content. All feeds are available at `https://rss.slashdot.org/` and are rate-limited to one request per 30 minutes. To get an Atom feed, substitute `atom` for `rss` in the feed URL.

### Main Feed

- **Main Feed:** https://rss.slashdot.org/Slashdot/slashdotMain

### Section Feeds

- **Developers:** https://rss.slashdot.org/Slashdot/slashdotDevelopers
- **Apple:** https://rss.slashdot.org/Slashdot/slashdotApple
- **Linux:** https://rss.slashdot.org/Slashdot/slashdotLinux
- **Games:** https://rss.slashdot.org/Slashdot/slashdotGames
- **Science:** https://rss.slashdot.org/Slashdot/slashdotScience
- **Your Rights Online:** https://rss.slashdot.org/Slashdot/slashdotYourRightsOnline

### Feed Usage Policy

Slashdot requests that feed consumers limit requests to once every 30 minutes. Excessive polling may result in IP blocks lasting up to 72 hours.

## The Firehose

Slashdot's Firehose is a real-time stream of all content submitted to the site, including user story submissions, journal entries, comments, and RSS feed items. It allows readers to participate in the editorial process by voting on submissions. More details are available in the [Firehose FAQ](https://slashdot.org/faq/firehose.shtml).

## Artifacts

### OpenAPI

| File | Description |
|---|---|
| [openapi/slashdot-rss-openapi.yml](openapi/slashdot-rss-openapi.yml) | OpenAPI 3.1 specification for all Slashdot RSS/Atom feed endpoints |

### Linked Data

| File | Description |
|---|---|
| [json-ld/slashdot-context.jsonld](json-ld/slashdot-context.jsonld) | JSON-LD context for Slashdot news articles, discussion threads, comments, RSS feeds, and users |

### Examples

| File | Description |
|---|---|
| [examples/slashdot-rss-feed-example.json](examples/slashdot-rss-feed-example.json) | Example RSS feed response with story items |

### Rules

| File | Description |
|---|---|
| [rules/slashdot-rules.yml](rules/slashdot-rules.yml) | Spectral ruleset for Slashdot OpenAPI specs |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/slashdot-vocabulary.yml](vocabulary/slashdot-vocabulary.yml) | Domain vocabulary covering Slashdot community terms, moderation system, feed formats, and site culture |

## Resources

- **Website:** https://slashdot.org/
- **About / FAQ:** https://slashdot.org/faq/slashmeta.shtml
- **FAQ Index:** https://slashdot.org/faq/index.shtml
- **Feeds FAQ:** https://slashdot.org/faq/feeds.shtml
- **Firehose FAQ:** https://slashdot.org/faq/firehose.shtml
- **Privacy Policy:** https://slashdot.org/privacy

## Maintainers

- **Kin Lane** - kin@apievangelist.com
