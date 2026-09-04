# Awesome Readwise with stars

A curated list of awesome [Readwise](https://readwise.io/) and [Reader](https://readwise.io/read) libraries, plugins, software, and resources. For official software, visit [Readwise.io's GitHub Page](https://github.com/readwiseio).

* [Awesome Readwise](#awesome-readwise)
  * [Official Apps](#official-apps)
  * [Client Libraries](#client-libraries)
    * [API Documentation](#api-documentation)
    * [API Endpoint Collections](#api-endpoint-collections)
  * [AI - Agent Skills, MCP, and CLI](#ai---agent-skills-mcp-and-cli)
    * [Agent Skills](#agent-skills)
    * [MCP](#mcp)
    * [CLI](#cli)
  * [Tools](#tools)
    * [AI](#ai)
    * [Amplenote](#amplenote)
    * [Anki](#anki)
    * [Blinkist](#blinkist)
    * [Calibre](#calibre)
    * [MCP - Model Context Protocol](#mcp---model-context-protocol)
    * [Datasette](#datasette)
    * [Discord](#discord)
    * [Kindle](#kindle)
    * [Kobo](#kobo)
    * [KOReader](#koreader)
    * [LaunchBar](#launchbar)
    * [LiquidText](#liquidtext)
    * [Logseq](#logseq)
    * [Mastodon](#mastodon)
    * [Obsidian](#obsidian)
    * [Pinboard](#pinboard)
    * [Raycast](#raycast)
    * [RemNote](#remnote)
    * [Roam](#roam)
    * [Shortcuts (for iPhone and iPad)](#shortcuts-for-iphone-and-ipad)
    * [Shortform](#shortform)
    * [Telegram](#telegram)
    * [Twitter](#twitter)
    * [Wallabag](#wallabag)
    * [Weread](#weread)
    * [Workflowy](#workflowy)
    * [Zotero](#zotero)
    * [Other](#other)
  * [Third-Party Integrations](#third-party-integrations)
    * [Notes Apps](#notes-apps)
      * [Drafts](#drafts)
      * [Podcasts](#podcasts)
  * [Resources](#resources)
    * [Official Channels](#official-channels)
    * [Feedback & FAQ](#feedback--faq)
    * [Content & Guides](#content--guides)
  * [Contributing](#contributing)

## Official Apps

* [Reader web app](https://read.readwise.io/)
* [Readwise web app](https://readwise.io/)
* [Reader for Android](https://play.google.com/store/apps/details?id=com.readermobile) – Google Play link.
* [Readwise for Android](https://play.google.com/store/apps/details?id=com.readwise) – Google Play link.
* [Reader for iOS and iPad](https://apps.apple.com/us/app/readwise-reader/id1567599761) – App Store link.
* [Readwise for iOS and iPad](https://apps.apple.com/us/app/readwise/id1476885528) – App Store link (also for Apple Silicon Macs).
* [Reader for macOS and Windows](https://readwise.io/read/download) - Download page for the “alpha” version of Reader for Desktop. Also installable for macOS via Homebrew: `brew install reader`.

## Client Libraries

This section lists client libraries for the *Readwise API* and the *Readwise Reader API*.

**Python:**

* [pyreadwise](https://github.com/rwxd/pyreadwise) ⚠️ Archived - A Python module for using the Readwise API.
* [readwise-api](https://github.com/floscha/readwise-api) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2023-06-12 - An unofficial Python client for the Readwise Reader API.

**Go:**

* [readwise-go](https://github.com/ethanholz/readwise-go) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2022-09-29 - A wrapper around Readwise API.

**Ruby:**

* [readwise-ruby](https://github.com/joshbeckman/readwise-ruby) ⭐ 11 | 🐛 2 | 🌐 Ruby | 📅 2025-07-18 - A minimal Readwise API client and highlight parsing library.

**Node.js:**

* [readwise-reader-api](https://github.com/Scarvy/readwise-reader-api) ⭐ 13 | 🐛 0 | 🌐 TypeScript | 📅 2024-08-20 - An unofficial JS/TS client for the Readwise Reader API.

**Rust:**

* [readwise](https://github.com/terror/readwise) ⭐ 8 | 🐛 1 | 🌐 Rust | 📅 2022-10-15 - A Rust wrapper for the Readwise API.

### API Documentation

* [Readwise](https://readwise.io/api_deets)
* [Readwise Reader](https://readwise.io/reader_api)

### API Endpoint Collections

* [readwise-postman](https://github.com/herczogzoltan/readwise-postman) ⭐ 9 | 🐛 0 | 📅 2022-04-20 - A Postman collection for Readwise API endpoints.
* [readwise-bruno](https://github.com/Scarvy/readwise-bruno) ⭐ 6 | 🐛 0 | 📅 2024-01-28 - A Bruno collection for Readwise and Reader API endpoints.

## AI - Agent Skills, MCP, and CLI

### Agent Skills

* [readwise-skills](https://github.com/readwiseio/readwise-skills) ⭐ 305 | 🐛 5 | 🌐 Python | 📅 2026-06-19 - The official agent skills from RW.
* [readwise-skill](https://github.com/ryanlyn/readwise-skill) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2026-04-03 - A collection of agent skills and CLI for RW + Reader.

### MCP

* [readwise-mcp](https://github.com/readwiseio/readwise-mcp) ⭐ 152 | 🐛 6 | 🌐 JavaScript | 📅 2026-03-14 - The official RW MCP (Deprecated)
* [readwise-mcp-enhanced](https://github.com/arnaldo-delisio/readwise-mcp-enhanced) ⭐ 67 | 🐛 3 | 🌐 TypeScript | 📅 2026-02-09 - A MCP server unifying RW Reader + RW with text processing and context optimization.

### CLI

* [readwise-cli](https://github.com/readwiseio/readwise-cli) ⭐ 72 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-27 - The official RW CLI.
* [readwise-reader-cli](https://github.com/Scarvy/readwise-reader-cli) ⭐ 41 | 🐛 0 | 🌐 Python | 📅 2026-03-26 - A Python-based CLI for Readwise Reader.
* [ReadwiseSync](https://github.com/heshanpadmasiri/ReadwiseSync) ⭐ 5 | 🐛 5 | 🌐 Go | 📅 2024-01-01 - Sync Readwise highlights to local files.
* [readwise](https://github.com/thoreinstein/readwise) ⭐ 5 | 🐛 0 | 📅 2026-02-07 - A Gemini CLI extension for interfacing with your RW Reader highlights.
* [readwise-reader-cli](https://github.com/lis186/readwise-reader-cli) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-01-02 - A TS-based CLI for RW Reader API.
* [readwise-rs](https://github.com/prasincs/readwise-rs) ⭐ 0 | 🐛 3 | 🌐 Rust | 📅 2023-10-09 - A Rust-based CLI for RW.

## Tools

A collection of open-source tools for Readwise and Reader.

### AI

* [smoothbrain-anki](https://github.com/smoothbrain-ai/smoothbrain-anki) ⭐ 56 | 🐛 29 | 🌐 Python | 📅 2024-01-25 - An Anki plugin to create flashcards from Readwise highlights using the OpenAI GPT.
* [quoordinates](https://github.com/bramses/quoordinates) ⭐ 30 | 🐛 2 | 🌐 JavaScript | 📅 2024-05-14 - A tool to visualize Kindle Highlights from Readwise using OpenAI Embeddings.
* [readwise-chat](https://github.com/acmeyer/readwise-chat) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2024-05-25 - A chatbot that pulls highlights from your Readwise account, using the ChatGPT API.
* [readwise-highlights-chat](https://github.com/intellectronica/readwise-highlights-chat/tree/main) ⭐ 3 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-05-14 - Chat over highlights with OpenAI, LangChain, and Chroma.

### Amplenote

* [readwise](https://github.com/alloy-org/readwise) ⭐ 7 | 🐛 1 | 🌐 JavaScript | 📅 2024-07-18 - Amplenote Readwise integration.

### Anki

* [readwise-anki](https://github.com/mattbarlow-sg/readwise-anki) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2023-09-04 - An unofficial Readwise add-on for Anki.
* [readwise2anki](https://github.com/ethan-butler-alight/readwise2anki) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-03-19 - An Anki plugin to export Readwise highlights to Anki decks.
* [readwise2anki](https://github.com/volker-fr/readwise2anki) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-25 - A CLI tool to sync Readwise highlights to Anki using AnkiConnect.

### Blinkist

* [Blinkist-to-Readwise](https://github.com/tibobrc/Blinkist-to-Readwise) ⭐ 47 | 🐛 3 | 🌐 Python | 📅 2021-04-12 - Export highlights to Readwise.

### Calibre

* [calibre-plugin-readwise](https://github.com/iamwillbar/calibre-plugin-readwise) ⭐ 65 | 🐛 11 | 🌐 Python | 📅 2023-08-20 - An export plugin for Calibre.

### MCP - Model Context Protocol

* [readwise-mcp-http-server](https://github.com/CaseyRo/readwise-mcp-http-server) ⭐ 1 | 🐛 13 | 🌐 Python | 📅 2026-08-31 - A Node.js HTTP server that provides proper MCP over HTTP.
* [readwise-mcp](https://www.npmjs.com/package/@readwise/readwise-mcp) - the official Readwise MCP server.
* [remote-readwise-mcp](https://github.com/mayankbohra/remote-readwise-mcp) - a Python MCP server.

### Datasette

* [readwise-to-datasette](https://github.com/iloveitaly/readwise-to-datasette) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-08-31 - Extract Readwise highlights into a Datasette SQLite database.

### Discord

* [Readwise Discord bot](https://docs.readwise.io/readwise/docs/faqs/discord-bot) – The official Discord bot lets members save messages, links, and images to their Readwise Library.

### Kindle

* [kindle2readwise](https://github.com/biokraft/kindle2readwise) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2025-08-26 - A Python app for exporting Kindle highlights to Readwise.

### Kobo

* [october](https://github.com/marcus-crane/october) ⭐ 240 | 🐛 37 | 🌐 Go | 📅 2025-09-29 - A simple GUI for retrieving Kobo highlights and syncing them with Readwise.
* [kobwise](https://github.com/osteel/kobwise) ⭐ 12 | 🐛 0 | 🌐 PHP | 📅 2023-01-08 - Convert Kobo annotations into Readwise highlights.
* [kobo-to-readwise](https://github.com/zakkolar/kobo-to-readwise) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2022-01-18 - Extract highlights from Kobo devices and convert them into a CSV file for Readwise.
* [kobo\_readwise](https://github.com/taiansu/kobo_readwise) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2022-06-21 - Send Kobo eReader bookmarks to Readwise.

### KOReader

* [readwisereader](https://github.com/tomtom800/readwisereader) ⚠️ Archived - A plugin to sync documents to KOReader.

### LaunchBar

* [Reade](https://github.com/quinncomendant/Reade.lbaction) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-26 - LaunchBar action to interact with the Readwise and Reader APIs.

### LiquidText

* [LT→R](https://gregwolanski.com/lt2r?ref=awesome-readwise) - Add grouped highlights to your imports from LiquidText into Readwise.

### Logseq

* [logseq-readwise-plugin](https://github.com/hkgnp/logseq-readwise-plugin) ⭐ 65 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-03 - Pull Readwise highlights into Logseq.
* [logseq-readwise-reader-export](https://github.com/pstuifzand/logseq-readwise-reader-export) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2024-01-09 - Export blocks to Readwise Reader.

### Mastodon

* [mastobot](https://github.com/nicolevanderhoeven/mastobot) ⭐ 13 | 🐛 0 | 🌐 JavaScript | 📅 2022-12-31 - A Mastodon bot for sending toots to Readwise.

### Obsidian

* [obsidian-readwise](https://github.com/renehernandez/obsidian-readwise) ⭐ 114 | 🐛 15 | 🌐 TypeScript | 📅 2021-08-27 - Sync Readwise highlights into your Obsidian vault.
* [obsidian-readwise-inbox](https://github.com/TfTHacker/obsidian-readwise-inbox) ⭐ 79 | 🐛 1 | 🌐 JavaScript | 📅 2022-09-12 - An inbox for processing Readwise highlights in Obsidian.
* [obsidian-readwise-reader](https://github.com/joerncodes/obsidian-readwise-reader) ⭐ 28 | 🐛 1 | 🌐 TypeScript | 📅 2022-08-24 - An Obsidian plugin to publish notes to Readwise Reader.

### Pinboard

* [reader\_to\_pinboard](https://github.com/basepi/reader_to_pinboard) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-08-11 - A script for sending archived Readwise Reader items to Pinboard.
* [reader2pinboard](https://github.com/moefuerst/reader2pinboard) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2024-03-16 - Import articles saved in Readwise Reader to Pinboard.

### Raycast

* [readwise-reader](https://github.com/raycast/extensions/tree/main/extensions/readwise-reader) ⭐ 7,726 | 🐛 1,554 | 🌐 TypeScript | 📅 2026-09-04 - extension to interact with Reader.
* [readwise](https://github.com/raycast/extensions/tree/main/extensions/readwise) ⭐ 7,726 | 🐛 1,554 | 🌐 TypeScript | 📅 2026-09-04 - extension to interact with Readwise.

### RemNote

* [remnote-readwise](https://github.com/bjsi/remnote-readwise) ⭐ 8 | 🐛 17 | 🌐 TypeScript | 📅 2024-07-19 - Sync Readwise highlights into RemNote.

### Roam

* [Readwise2Roam](https://github.com/jammastergirish/Readwise2Roam) ⭐ 23 | 🐛 2 | 🌐 PHP | 📅 2020-11-11 - Migrate Readwise highlights to Roam Research.

### Shortcuts (for iPhone and iPad)

* **Reader & Readwise:**

  * [Batch Save to Readwise Reader](https://www.icloud.com/shortcuts/ba4101ca05ce4a5ebccb857999287a78) - Batch saves links to Readwise Reader.
  * [Readwise Reader Search](https://www.icloud.com/shortcuts/3f7d49fb62704499ba3b97128c06c383) - Takes text input to search within Readwise Reader.
  * [Readwise Search](https://www.icloud.com/shortcuts/9536fd1b96c44150ac0255e8a7bdecbc)
  * [Save to Readwise Reader](https://www.icloud.com/shortcuts/1b0d4bc72603483cbac0a559844713d1) - Takes text input to search within Readwise.
  * [Show Latest Readwise Highlights](https://www.icloud.com/shortcuts/976c4d2059ea4e869a9e25a648cba2f4) - Displays your latest Readwise highlights.
  * [Show Readwise Highlights for Tag](https://www.icloud.com/shortcuts/d6e98b5046eb450eb0aceb5234a8b721) - Display Readwise highlights for a specific tag.

  > Note: All of the shortcuts listed above were created by Chris.sk and were last updated on **2023-09-16**.
  > These shortcuts may become outdated over time, so please refer to the Discord conversation for the most recent updates. [here](https://discord.com/channels/886992134505398314/1092171483792556182).

* **Other Apps:**

  * [Bear Note App Integration](https://benbailey.me/2023/06/03/how-i-sync.html) - User-built RW 1.0 integration with the Bear Note App.
  * [PodNote](https://www.icloud.com/shortcuts/1c13a7d9b33b4b6d85231b1c7d572b35) - A shortcut to highlight sections of podcasts.

### Shortform

* [shortform-to-readwise](https://github.com/nicolevanderhoeven/shortform-to-readwise) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2021-10-10 - Import highlights from Shortform.com.

### Telegram

* [readwise\_telegram\_bot](https://github.com/ixnet/readwise_telegram_bot) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2023-01-14 - A bot for Telegram integration.

### Twitter

* [SaveToReadwiseReaderOnTwitter](https://github.com/floriankilian/SaveToReadwiseReaderOnTwitter) ⭐ 7 | 🐛 1 | 🌐 JavaScript | 📅 2024-02-13 - save tweets to Readwise Reader.

### Wallabag

* [wallabag2readwise](https://github.com/rwxd/wallabag2readwise) ⚠️ Archived - Export / synchronize Wallabag annotations to Readwise highlights.

### Weread

* [wereadwise](https://github.com/fuergaosi233/wereadwise) ⭐ 99 | 🐛 2 | 🌐 TypeScript | 📅 2024-01-01 - Export Weread highlights to Readwise.
* [weread-to-readwise](https://github.com/wogong/weread-to-readwise) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2022-02-18 - Convert Weread notes into a CSV file compatible with Readwise.

### Workflowy

* [readwise-workflowy-integration](https://github.com/zackdn/readwise-workflowy-integration) ⭐ 29 | 🐛 1 | 🌐 JavaScript | 📅 2024-11-24 - Import Readwise notes directly into Workflowy.

### Zotero

* [Zotero2Readwise](https://github.com/e-alizadeh/Zotero2Readwise) ⭐ 183 | 🐛 6 | 🌐 Python | 📅 2025-11-23 - A Python library to retrieve annotations and notes from Zotero and upload them to Readwise.
* [Zotero2Readwise-Sync](https://github.com/e-alizadeh/Zotero2Readwise-Sync) ⭐ 86 | 🐛 3 | 📅 2025-11-23 - Automated and scheduled trigger for the Zotero2Readwise Python library.

### Other

* [Readform](https://github.com/fr0der1c/Readform) ⭐ 83 | 🐛 4 | 🌐 Go | 📅 2024-03-09 - Send full articles from paywalled news websites to Reader feed.
* [readwise2directory](https://github.com/nicrivard/readwise2directory) ⭐ 78 | 🐛 2 | 🌐 Python | 📅 2022-06-11 - Update and store highlights locally (in markdown).
* [rextract](https://github.com/zachwick/rextract) ⭐ 62 | 🐛 1 | 🌐 Python | 📅 2021-10-28 - A toolchain for moving Remarkable highlights to Readwise.
* [readwise-reader-management](https://github.com/LZong-tw/readwise-reader-management) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2026-05-08 - A CLI-based tool to manage documents in Readwise, currently focus on bulk duplicate deletions.
* [alfred-readwise](https://github.com/giovannicoppola/alfred-readwise) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2026-09-01 - An Alfred Workflow for your Readwise account.
* [readwise-epub](https://github.com/GeorgeHahn/readwise-epub) ⭐ 16 | 🐛 4 | 🌐 Rust | 📅 2023-07-08 - Create EPUBs from your Readwise Reader inbox.
* [Readwise.md](https://github.com/bobbyhiddn/Readwise.md) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2023-07-29 - A script that pushes all quotes from a folder to Readwise.
* [Kindle-highlight-to-Word-document-script](https://github.com/AEchRod/Kindle-highlight-to-Word-document-script) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2023-04-25 - Create a Word document from your highlights.
* [comments-to-readwise](https://github.com/marcus-crane/comments-to-readwise) ⭐ 7 | 🐛 4 | 🌐 TypeScript | 📅 2022-12-31 - A basic extension for sending comments to Readwise as "tweets".
* [mem-readwise-sync](https://github.com/riclib/mem-readwise-sync) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2021-12-10 - Sync books, articles, and highlights to Mem.ai.
* [readwise-feed](https://github.com/jckw/readwise-feed) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2024-01-02 - A passive social media feed of user's reading activity.
* [scribd-readwise-integration](https://github.com/micahlt/scribd-readwise-integration) ⭐ 6 | 🐛 2 | 🌐 JavaScript | 📅 2023-11-19 - Send highlights from Scibd to Readwise.
* [plus-readwise](https://github.com/jchen1/plus-readwise) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2020-11-08 - Save snippets from the browser to Readwise.
* [readspace](https://github.com/maxprogram/readspace) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2023-08-07 - A semantic search tool for your Readwise highlights.
* [readwise-gpt-tagger](https://github.com/duartemartins/readwise-gpt-tagger) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2024-09-09 - Export all highlights to CSV, tag them using GPT, and update them on Readwise.
* [readwise-note-extractor](https://github.com/elchead/readwise-note-extractor) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2022-03-23 - Export markdown highlights to Readwise.
* [readwise-list](https://github.com/rockiedo/readwise-lite) ⭐ 4 | 🐛 0 | 🌐 Dart | 📅 2023-01-21 - A minimal version of the Readwise app.
* [diiggo-to-readwise](https://github.com/dexter-stpierre/diiggo-to-readwise) ⭐ 3 | 🐛 2 | 🌐 TypeScript | 📅 2021-09-28 - Sync Diigo highlights to Readwise.
* [enhanced-readwise-reader](https://github.com/sodastereo/enhanced-readwise-reader) ⭐ 3 | 🐛 0 | 🌐 CSS | 📅 2022-12-22 - An enhanced version of the Readwise Reader UI for the Arc browser Boost.
* [miniflux-to-reader](https://github.com/th1nkful/miniflux-to-reader) ⚠️ Archived - Export Miniflux articles to Readwise Reader.
* [readwise-craft-extension](https://github.com/mattflux/readwise-craft-extension?tab=readme-ov-file) ⭐ 3 | 🐛 0 | 📅 2021-12-11 - An extension to import highlight to craft.
* [readwise-s3](https://github.com/fedragon/readwise-s3) ⭐ 3 | 🐛 1 | 🌐 Go | 📅 2021-09-28 - Backup Readwise.io content to AWS S3.
* [readwise-template](https://github.com/natterstefan/readwise-template) ⭐ 3 | 🐛 2 | 🌐 Python | 📅 2022-03-18 - A Readwise export template for Roam (or other tools for thought).
* [raindrop-highlights-readwise](https://github.com/luhmann/raindrop-highlights-readwise) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2022-07-31 - Import highlights from Raindrop to Readwise.
* [reader-google-docs](https://github.com/marcus-crane/reader-google-docs) ⚠️ Archived - Import Google Docs into Reader (archived).
* [readwise-random-quote](https://github.com/TedisAgolli/readwise-random-quote) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2021-07-06 - A Next.js app that generators quotes from Readwise highlights.
* [readwise-reader-desktop](https://github.com/ondrejfuhrer/readwise-reader-desktop) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2023-03-10 - A simple Electron app for the Readwise Reader web application.
* [readwise-ulusses](https://github.com/terror/readwise-ulysses) ⭐ 2 | 🐛 3 | 🌐 JavaScript | 📅 2021-12-01 - Sync highlights from Readwise to Ulysses.
* [readwise\_to\_discord](https://github.com/clement0910/readwise_to_discord) ⭐ 2 | 🐛 0 | 🌐 Ruby | 📅 2024-01-07 - Share notes and articles by sending Readwise data to Discord.
* [mrexpt2html](https://github.com/lockcp/mrexpt2html) ⭐ 1 | 🐛 0 | 📅 2021-06-15 - Import Moon+ Reader highlights to Readwise.
* [tana-readwise-exporter](https://github.com/ashrithr/tana-readwise-exporter) ⭐ 1 | 🐛 2 | 🌐 Go | 📅 2022-11-15 - A CLI to export highlights to Tana.io.
* [readwise-reader-filter](https://github.com/volker-fr/readwise-reader-filter) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-25 - A CLI tool to filter and manage Readwise Reader feed entries by configurable rules.
* [FeedWise](https://chromewebstore.google.com/detail/feedwise/mddkmjedifnddecckcjlfcoahjfgdcmb) - Transform your social media feeds into daily wisdom with Readwise highlights and Obsidian notes.

## Third-Party Integrations

A selection of products and services integrated with Readwise and/or Reader.

* [Beeminder](https://www.beeminder.com/readwisereader) - Beeminder, a self-tracker with commitment contracts.
  * [Beeminder Blog](https://blog.beeminder.com/readwise/) - A blog post discussing the integration.
* [PopClip](https://www.popclip.app/extensions/#q=readwise) - Instant text actions to save highlights to Readwise.

### Notes Apps

#### Drafts

* [Drafts - Readwise](https://actions.getdrafts.com/a/1fl) - add highlights from Draft to Readwise.
* [Drafts - Readwise Reader](https://actions.getdrafts.com/a/2E9) - add highlights from Draft to Reader.

#### Podcasts

* [PodHighlighter](https://www.podhighlighter.io/) - Sync podcast highlights to Readwise.
* [snipd](https://www.snipd.com/) - Highlight, take notes, and summarize your favorite podcasts using AI.

## Resources

A collection of official resources and content.

### Official Channels

* [Blog](https://blog.readwise.io/) - The official Readwise blog.
* [YouTube](https://www.youtube.com/@readwise-official/playlists) - The official Readwise YouTube channel.
  * [Onboarding Materials](https://www.youtube.com/playlist?list=PLF-dRXiEENypisIeJV4aik6NSNfoM3VI1) - A tutorial on how to set up and use Reader.

### Feedback & FAQ

* [Customer Feedback & Feature Request Board](https://readwise.canny.io/) - The official customer feedback page.
* [FAQ](https://help.readwise.io/) – The official Readwise FAQ page.
* [r/readwise](https://www.reddit.com/r/readwise/) – The official subreddit moderated by the Readwise team.
* [Readwise Community Server (RCS)](https://discord.gg/readwise) – The official Discord server.

### Content & Guides

* [Wisereads](https://wise.readwise.io/) ([RSS](https://wise.readwise.io/feed/)) - A weekly newsletter featuring the most highlighted documents in Readwise during the past week.
* [WiseUp!](https://wiseup.readwise.io/) ([RSS](https://wiseup.readwise.io/rss/)) - A weekly newsletter designed to help you make the most of Readwise and Reader.
* [Reader Filter Guide 📖](https://readwise.notion.site/readwise/Reader-Filtering-Guide-d4b249df2eaa492283099ec2a3551640) - A how-to guide for document filtering and syntax in Reader.
* [(Unofficial) - Ghostreader Prompts](https://github.com/Scarvy/ghostreader-prompts) ⭐ 58 | 🐛 0 | 📅 2024-03-18 - A collection of user-created prompts for Readwise Reader's "Copilot of Reading" feature Ghostreader.

## Contributing

Contributions are always welcome!

**Please adhere to these guidelines:**

1. Fork this repository on GitHub.
2. Add a link with a concise description to README.md:

```md
- [project-name](https://example.com/) - A short description ending with a period.
```

3. Add a new section if necessary.
4. Submit a GitHub pull request.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
