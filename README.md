# Awesome Open Legal Data Switzerland

[![GitHub Stars](https://img.shields.io/github/stars/rnckp/awesome-open-legal-switzerland.svg)](https://github.com/rnckp/awesome-open-legal-switzerland)
[![GitHub Issues](https://img.shields.io/github/issues/rnckp/awesome-open-legal-switzerland.svg)](https://github.com/rnckp/awesome-open-legal-switzerland)
[![GitHub Issues](https://img.shields.io/github/issues-pr/rnckp/awesome-open-legal-switzerland.svg)](https://img.shields.io/github/issues-pr/rnckp/awesome-open-legal-switzerland)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A manually curated list of open legal data sources, tools, and resources in Switzerland.

## Contents

- [Parliamentary Data](#parliamentary-data)
- [Federal Legislation & Official Publications](#federal-legislation--official-publications)
- [Legal Data Infrastructure & Metadata](#legal-data-infrastructure--metadata)
- [Cantonal Legislation](#cantonal-legislation)
- [Judicial Decisions](#judicial-decisions)
- [Legal Commentary & Secondary Sources](#legal-commentary--secondary-sources)
- [MCP Servers](#mcp-servers)
- [Miscellaneous](#miscellaneous)

## Parliamentary Data

- [Swiss Parliament](https://www.parlament.ch/de/suche) - Federal Assembly data, with a [web service](https://ws-old.parlament.ch/) available.
- [OpenParlData.ch](https://openparldata.ch/) - Harmonized [API](https://api.openparldata.ch/documentation) offering data on political actors, legislative proposals, motions, and voting results across 78 parliaments (federal, cantonal, municipal).
- [Consultation Procedures Dataset (1960-1991)](https://applab.bar.admin.ch/de/datenbanken-und-apis/vernehmlassungen) - Metadata on federal consultation procedures (Vernehmlassungen) from 1960 to 1991.
- [Official Bulletins](https://www.parlament.ch/de/ratsbetrieb/amtliches-bulletin) - Full transcripts of Federal Assembly debates from 1891 onward.

## Federal Legislation & Official Publications

- [Fedlex](https://www.fedlex.admin.ch/) - Publication platform for Swiss federal law. Includes the Systematic Compilation of Federal Law (SR), the Official Compilation (AS), the Federal Gazette (BBl), international treaties, and consultation procedures. Multilingual (DE/FR/IT) with a SPARQL endpoint.
- [Historical Federal Law (AS 1948-2018)](https://applab.bar.admin.ch/databases-and-apis/official-compilation-of-federal-legislation) - Bulk-data archive from the Swiss Federal Archives. Contains all Official Compilation files from 1948 to 2018 as XML, with legal classification tables in three languages.
- [Swiss Federal Gazette (BBl)](https://www.fedlex.admin.ch/de/fga) - Official journal of federal legislation. Publishes drafts, dispatches, and official texts weekly. Archives back to 1849 are accessible via Fedlex.
- [Official Gazettes Portal (Amtsblattportal)](https://amtsblattportal.ch/) - Central platform for official legal notices. Hosts the Swiss Official Gazette of Commerce (SOGC/SHAB) and cantonal gazettes. A [REST API](https://amtsblattportal.ch/docs/api/) is available.

## Legal Data Infrastructure & Metadata

- [Fedlex Linked Data](https://lindas.admin.ch/data-usage/fedlex/) - Persistent URIs for each act or article. SPARQL endpoint with a documented ontology (JOLux data model). Enables programmatic retrieval of law texts, metadata, versions, and relationships.
- [TERMDAT](https://www.termdat.ch/) - Federal Administration's multilingual terminology database for legal and administrative terms.
- [International Treaties Database](https://www.fedlex.admin.ch/de/treaty) - Switzerland's binding international agreements.

## Cantonal Legislation

All 26 cantons maintain official, freely accessible law collections:

- [LexFind](https://www.lexfind.ch/) - Unified search tool indexing all federal and cantonal law collections.
- [Aargau (AG)](https://gesetzessammlungen.ag.ch/)
- [Appenzell Innerrhoden (AI)](https://ai.clex.ch/app/de/systematic/texts_of_law)
- [Appenzell Ausserrhoden (AR)](https://ar.clex.ch/app/de/systematic/texts_of_law)
- [Bern (BE)](https://www.belex.sites.be.ch/)
- [Basel-Landschaft (BL)](https://bl.clex.ch/app/de/systematic/texts_of_law)
- [Basel-Stadt (BS)](https://www.gesetzessammlung.bs.ch/)
- [Fribourg (FR)](https://bdlf.fr.ch/)
- [Geneva (GE)](https://www.ge.ch/legislation/)
- [Glarus (GL)](https://gesetze.gl.ch/app/de/systematic/texts_of_law)
- [Graubünden (GR)](https://www.gr-lex.gr.ch/)
- [Jura (JU)](https://rsju.jura.ch/)
- [Luzern (LU)](https://srl.lu.ch/)
- [Neuchâtel (NE)](https://rsn.ne.ch/)
- [Nidwalden (NW)](https://gesetze.nw.ch/app/de/systematic/texts_of_law)
- [Obwalden (OW)](https://gdb.ow.ch/app/de/systematic/texts_of_law)
- [St. Gallen (SG)](https://www.gesetzessammlung.sg.ch/)
- [Schaffhausen (SH)](https://sh.clex.ch/)
- [Solothurn (SO)](https://bgs.so.ch/)
- [Schwyz (SZ)](https://www.sz.ch/kanton/gesetze.html/8756-8757-10021)
- [Thurgau (TG)](https://www.rechtsbuch.tg.ch/app/de/systematic/texts_of_law)
- [Ticino (TI)](https://www3.ti.ch/CAN/RLeggi/public/index.php/raccolta-leggi)
- [Uri (UR)](https://rechtsbuch.ur.ch/app/de/systematic/texts_of_law)
- [Vaud (VD)](https://prestations.vd.ch/pub/blv-publication/accueil)
- [Valais (VS)](https://lex.vs.ch/)
- [Zug (ZG)](https://bgs.zg.ch/)
- [Zürich (ZH)](https://www.zh.ch/de/politik-staat/gesetze-beschluesse/gesetzessammlung.html#zhlex_ls)
- [Zürich ZHLAW](https://www.zhlaw.ch/) - Private project aiming to improve the digital accessibility of the Canton of Zurich's law collection.
- [Intlex](https://www.intlex.ch/) - Contains all intercantonal agreements to which the cantons of Zug, Schaffhausen, St. Gallen, Graubünden, Thurgau, and Valais are currently party.

## Judicial Decisions

### Federal Courts

- [Federal Supreme Court](https://www.bger.ch/ext/eurospider/live/de/php/clir/http/index.php?lang=de) - Official database with all judgments (mostly anonymized) from 1954 onward. Newer decisions (since around 2000) are available in full text (DE/FR/IT). Identifies precedential cases (BGE).
- [Federal Administrative Court (BVGer)](https://bvger.weblaw.ch/dashboard) - Decisions of the Bundesverwaltungsgericht.
- [Federal Criminal Court (BStGer)](https://bstger.weblaw.ch/) - Major rulings are published online. Selected decisions are compiled in the official "TPF" report series.
- [Federal Patent Court](https://www.bundespatentgericht.ch/rechtsprechung/aktuelle-entscheide) - First-instance patent dispute judgments. Searchable archive from 2012 onward.

### Aggregated & Research Data

- [Entscheidsuche.ch](https://entscheidsuche.ch/search?query=%2a) - Non-profit initiative aggregating all publicly available Swiss court decisions (federal and cantonal). [[GitHub](https://github.com/entscheidsuche)]
- [Swiss Federal Supreme Court Dataset (SCD)](https://zenodo.org/records/14867950) - Structured dataset of all Federal Supreme Court cases from 2007 to 2024 (127k+ cases). Updated quarterly. Released under CC-BY 4.0.
- [FSCS Swiss Court Decisions Corpus](https://zenodo.org/records/5529712) - Multilingual text corpus of 85k Federal Supreme Court judgments (2000-2020) in DE/FR/IT for NLP research and legal judgment prediction. [[GitHub](https://github.com/JoelNiklworthy/Swiss-Judgment-Prediction)]
- [Swiss Landmark Decisions Summarization (SLDS)](https://huggingface.co/datasets/ipst/slds) - Cross-lingual dataset with 20k Federal Supreme Court rulings paired with official headnote summaries in DE/FR/IT (60k data points). Released under CC-BY 4.0.
- [Justement.ch](https://justement.ch/) - Commercial legal search engine aggregating Swiss court decisions. A free tier is available for Federal Supreme Court decisions; advanced features require a paid subscription.

## Legal Commentary & Secondary Sources

- [Onlinekommentar.ch](https://onlinekommentar.ch/) - The first non-profit, open-access commentary platform in Switzerland. [[API](https://onlinekommentar.ch/en/apis)]
- [Repositorium.ch](https://www.repositorium.ch/) - Specialist subject repository for Swiss law. Central, freely and openly accessible, Switzerland-wide and Switzerland-related, institution-independent and discipline-specific.
- [Fragmeisterjuristen.ch](https://fragmeisterjuristen.ch/) - Open-access legal AI chatbot by University of St. Gallen (2024). Answers questions on Swiss law with citations to classical legal scholarship.
- [sui-generis.ch](https://sui-generis.ch/) - Open-access law journal and non-profit publisher. Published Switzerland's first open-access law textbook, "Introduction to Swiss Law," in 2018.
- [ex/ante](https://www.ex-ante.ch/) - Open-access journal for (young) legal scholars. Publishes peer-reviewed articles, essays, and case comments in multiple languages.
- [Center for Legal Data Science (UZH)](https://www.clds.uzh.ch/en/knowledge/databases.html) - Data-driven legal research and dataset links.

## MCP Servers

> [!WARNING]
> MCP servers can create security and privacy risks even when you do not use them with sensitive data. Depending on how they are built and configured, they may read data from your AI tool, workspace, or local machine, send data to third-party services, change files, run commands, or expose your device to additional attack surfaces. Even a server that runs only on your own computer can still pose a serious risk to that computer. Only use MCP servers that you understand and trust, and review their code, permissions, operator, and deployment setup before enabling them.

### Core Swiss Law & Legislation

- [Ansvar-Systems/switzerland-law-mcp](https://github.com/Ansvar-Systems/switzerland-law-mcp) - Swiss federal-law MCP server for Fedlex/SR, covering searchable provisions, citation validation, currency checks, and EU-law cross-references.
- [malkreide/fedlex-mcp](https://github.com/malkreide/fedlex-mcp) - Fedlex MCP server for Swiss federal law; searches the Systematic Compilation, recent publications, upcoming legal changes, Federal Gazette, treaties, and law history.
- [janmanuelwinkler/hf_lexfind_mcp](https://github.com/janmanuelwinkler/hf_lexfind_mcp) - Offline Swiss law search MCP server over 35,000+ federal and cantonal laws from a LexFind-derived Hugging Face dataset.
- [JayTheSkier/fedlex-connector](https://github.com/JayTheSkier/fedlex-connector) - A connector that gives Claude direct access to the official text of Swiss federal legislation on Fedlex.

### Swiss Case Law & Courts

- [jonashertner/caselaw-repo-1](https://github.com/jonashertner/caselaw-repo-1) - OpenCaseLaw Swiss case-law dataset and MCP server, with 965k+ court decisions, citation analysis, statute lookup, and legislation search.
- [malkreide/swiss-courts-mcp](https://github.com/malkreide/swiss-courts-mcp) - MCP server for Swiss court decisions via entscheidsuche.ch, covering the Federal Supreme Court, federal courts, and all 26 cantonal courts.
- [self-tech-labs/entscheidsuche-MCP-server](https://github.com/self-tech-labs/entscheidsuche-MCP-server) - MCP server for searching and retrieving Swiss federal and cantonal court decisions through the Entscheidsuche API.
- [Gian-MarcoModer/opencaselaw-mcp](https://github.com/Gian-MarcoModer/opencaselaw-mcp) - Minimal OpenCaseLaw MCP deployment/wrapper repository; appears to launch a local FastAPI/uvicorn MCP service.

### Swiss Legal Commentary & Doctrine

- [self-tech-labs/onlinekommentar-mcp](https://github.com/self-tech-labs/onlinekommentar-mcp) - MCP server for Swiss legal commentaries from onlinekommentar.ch, including search, retrieval, multilingual support, and act filtering.
- [self-tech-labs/onlinekommentar-remote-mcp](https://github.com/self-tech-labs/onlinekommentar-remote-mcp) - Remote MCP/Cloudflare Workers variant related to Online Kommentar; the public README appears mostly template-like, so verify implementation before relying on it.

### Swiss Legal-Agent Frameworks

- [fedec65/bettercallclaude](https://github.com/fedec65/bettercallclaude) - Swiss legal-intelligence plugin that connects multiple MCP servers for Swiss court search, BGE search, citation verification, Fedlex SPARQL, Online Kommentar, CAS/TAS jurisprudence, and document intelligence.
- [fedec65/BetterCallClaudeMCP](https://github.com/fedec65/BetterCallClaudeMCP) - Dedicated MCP-server source repository referenced by BetterCallClaude for its remote Swiss legal MCP servers and HTTP aggregator.

### Swiss Regulatory / Public-Law MCP Servers

- [malkreide/swiss-public-data-mcp](https://github.com/malkreide/swiss-public-data-mcp) - Central index for Swiss public-data MCP servers; its “Legal & Regulatory” section lists Fedlex, BAKOM telecom/media, and Swiss IP MCP servers.
- [malkreide/bakom-mcp](https://github.com/malkreide/bakom-mcp) - BAKOM telecommunications and media open-data MCP server, categorized as “Legal & Regulatory” in the Swiss Public Data MCP portfolio.
- [malkreide/swiss-ip-mcp](https://github.com/malkreide/swiss-ip-mcp) - Swiss IP MCP server for IGE/IPI Swissreg data, including trademarks, patents, and supplementary protection certificates.
- [malkreide/register-mcp](https://github.com/malkreide/register-mcp) - Read-only MCP server for the Swiss Federal Commercial Register/Zefix and Swiss Official Gazette of Commerce references.
- [Ansvar-Systems/ch-land-woodland-mcp](https://github.com/Ansvar-Systems/ch-land-woodland-mcp) - Swiss land and woodland law/regulation MCP server covering land acquisition, forest protection, building zones, farmland protection, and agricultural lease rules.
- [Ansvar-Systems/ch-food-safety-mcp](https://github.com/Ansvar-Systems/ch-food-safety-mcp) - Swiss food-safety law MCP server for Lebensmittelgesetz, HACCP, labelling, and Swissness origin-marking regulations.
- [Ansvar-Systems/ch-farm-safety-mcp](https://github.com/Ansvar-Systems/ch-farm-safety-mcp) - Swiss farm workplace-safety MCP server covering BUL/SPAA, Suva, EKAS, machinery safety, chemical exposure, youth-work restrictions, and accident-reporting duties.
- [malkreide/swiss-food-safety-mcp](https://github.com/malkreide/swiss-food-safety-mcp) - BLV/Federal Food Safety and Veterinary Office data MCP server; not purely legal, but useful for regulated food/veterinary compliance and links to food-law workflows.

### Fact-Checking / Legal-Reference Adjacent

- [swisstruthorg/swiss-truth-mcp](https://github.com/swisstruthorg/swiss-truth-mcp) - Swiss fact-checking MCP server that uses official sources and can cite Swiss legal mandates, such as KVG health-insurance obligations.

## Miscellaneous

- [Open Access content collection University of Basel](https://ius.unibas.ch/de/bibliothek/recherche/open-access/) - List of repositories, collections, e-journals and blogs with open access content.
- [ejustice.ch](https://ejustice.ch) - Association connecting cantonal and federal legal authorities, practitioners, service providers, and stakeholders to promote digital innovation in Swiss justice administration.
- [Open Legal Lab](https://ejustice.ch/open-legal-lab/) - Free two-day event bringing together legal, tech, design, and data experts to develop innovative solutions for Swiss justice.
- [Awesome Legal Data](https://github.com/openlegaldata/awesome-legal-data) - Curated list of open legal data sources, tools, and resources worldwide.
