# Awesome Open Legal Data Switzerland

[![GitHub Stars](https://img.shields.io/github/stars/rnckp/awesome-open-legal-switzerland.svg)](https://github.com/rnckp/awesome-open-legal-switzerland)
[![GitHub Issues](https://img.shields.io/github/issues/rnckp/awesome-open-legal-switzerland.svg)](https://github.com/rnckp/awesome-open-legal-switzerland/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/rnckp/awesome-open-legal-switzerland.svg)](https://github.com/rnckp/awesome-open-legal-switzerland/pulls)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Curated sources, datasets, and tools for Swiss legal research and reuse, including lawmaking, democratic participation, and political accountability. Registers and specialist tools must expose legal records, rights, obligations, or regulatory disclosures; general government statistics and sector data are outside the scope.

- **Free access:** read or search without payment; this does not establish reuse rights.
- **Open data:** reuse under an explicit open licence or public-domain dedication.
- **Open source:** software under an open-source licence; data and hosted services may have separate terms.

Entries identify access methods and licences where known. An omitted licence means reuse terms have not been established here. Free trials, limited commercial free tiers, and general-purpose tools without a concrete Swiss legal use are excluded. Directories are included for discovery; not every linked publication is freely available.

Source collections and literature are free to consult unless an entry states an access restriction. Descriptions distinguish official publishers, independent aggregators, and derived research datasets.

Language lists describe available content, not necessarily translations of each document. Geographic coverage does not imply complete coverage of courts, dates, or decisions. An API link does not by itself establish anonymous access or unrestricted reuse; consult the linked documentation for credentials, limits, and terms.

<details>
<summary>Contents</summary>

- [Legislation, Treaties & Official Publications](#legislation-treaties--official-publications)
  - [Federal Legislation & Treaties](#federal-legislation--treaties)
  - [Federal & Cantonal Official Notices](#federal--cantonal-official-notices)
  - [Cantonal & Intercantonal Legislation](#cantonal--intercantonal-legislation)
- [Legislative Process, Parliament & Direct Democracy](#legislative-process-parliament--direct-democracy)
  - [Parliamentary Data](#parliamentary-data)
  - [Direct Democracy & Political Transparency](#direct-democracy--political-transparency)
- [Judicial Decisions](#judicial-decisions)
  - [Federal Courts](#federal-courts)
  - [Case-Law Search](#case-law-search)
  - [Specialist Collections](#specialist-collections)
- [Administrative Decisions & Regulatory Practice](#administrative-decisions--regulatory-practice)
- [Administrative Guidance & Drafting Resources](#administrative-guidance--drafting-resources)
- [Public Registers & Regulatory Disclosures](#public-registers--regulatory-disclosures)
- [International Decisions & Arbitration](#international-decisions--arbitration)
- [Commentary, Journals & Legal Literature](#commentary-journals--legal-literature)
  - [Commentaries & Case Analyses](#commentaries--case-analyses)
  - [Journals](#journals)
  - [Repositories & Catalogues](#repositories--catalogues)
- [Legal History & Archives](#legal-history--archives)
- [Research Datasets & Benchmarks](#research-datasets--benchmarks)
- [Developer Tools & Infrastructure](#developer-tools--infrastructure)
  - [APIs, Metadata & Libraries](#apis-metadata--libraries)
  - [AI Applications](#ai-applications)
  - [MCP Servers & Agent Integrations](#mcp-servers--agent-integrations)
- [Community & Related Directories](#community--related-directories)
  - [Discovery Resources](#discovery-resources)
  - [Community & Events](#community--events)
- [Contributing](#contributing)
- [Licence](#licence)

</details>

## Legislation, Treaties & Official Publications

### Federal Legislation & Treaties

- [Fedlex](https://www.fedlex.admin.ch/) - Official federal-law portal: consolidated legislation (SR), enacted texts and amendments (AS), the [Federal Gazette (BBl)](https://www.fedlex.admin.ch/de/fga) with drafts and explanatory dispatches, [international treaties](https://www.fedlex.admin.ch/de/treaty), and consultations. Federal legislation is available in German, French, and Italian; see [developer access](#apis-metadata--libraries).

### Federal & Cantonal Official Notices

- [Official Gazettes Portal (Amtsblattportal)](https://amtsblattportal.ch/) - Central platform for official legal notices. Hosts the Swiss Official Gazette of Commerce (SOGC/SHAB) and cantonal gazettes. A [REST API](https://amtsblattportal.ch/docs/api/) is available.

### Cantonal & Intercantonal Legislation

#### Cross-Jurisdiction Search

- [LexFind](https://www.lexfind.ch/) - Cross-jurisdiction search of federal and cantonal law collections; follow source links for official texts.

#### Official Cantonal Collections

Free official law collections for all 26 cantons, ordered by canton code:

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

#### Intercantonal Agreements

- [Intlex](https://www.intlex.ch/) - Searchable intercantonal agreements involving Zug, Schaffhausen, St. Gallen, Graubünden, Thurgau, and Valais; not a nationwide inventory.

#### Alternative Interfaces

- [Zürich ZHLAW](https://www.zhlaw.ch/) - Independent, accessible presentation of Zurich's cantonal legislation; complements the official collection.

## Legislative Process, Parliament & Direct Democracy

### Parliamentary Data

- [Swiss Parliament](https://www.parlament.ch/de/suche) - Official search for parliamentary business, members, and votes, with a [JSON/XML web service](https://ws-old.parlament.ch/).
- [OpenParlData.ch](https://openparldata.ch/) - Independent, harmonized [API](https://api.openparldata.ch/documentation) for political actors, parliamentary business, and votes at federal, cantonal, and municipal levels. Coverage varies by parliament.
- [Official Bulletins](https://www.parlament.ch/de/ratsbetrieb/amtliches-bulletin) - Full transcripts of Federal Assembly debates from 1891 onward.

### Direct Democracy & Political Transparency

- [Swissvotes](https://swissvotes.ch/page/dataset) - Dataset and codebook for all Swiss federal popular votes since 1848. Available as CSV and XLSX under CC BY 4.0.
- [Federal Popular Votes Dashboard](https://abstimmungen.admin.ch/en/overview) - Official results and open data for federal popular votes.
- [Political Rights: Historical Data](https://www.bk.admin.ch/bk/de/home/politische-rechte/gebrauch-der-volksrechte.html) - Official historical lists of federal votes, popular initiatives, optional and mandatory referendums, and procedural decisions.
- [Political-Financing Disclosures](https://politikfinanzierung.efk.admin.ch/) - Official Federal Audit Office register of federal campaign, party, and donation disclosures, with [Excel exports](https://politikfinanzierung.efk.admin.ch/app/de/exports/).
- [Lobbywatch](https://lobbywatch.ch/datenexport/) - Independent data on parliamentary interests and access badges. Downloads include CSV, JSON, SQL, and GraphML; REST, GraphQL, and SPARQL interfaces are also available. CC BY-SA 4.0.
- [Année Politique Suisse](https://anneepolitique.swiss/de/) - Free political chronicle and legislative-process histories since 1965, with research datasets. Useful for tracing the background of legislation and popular votes.
- [Öffentlichkeitsgesetz.ch](https://www.oeffentlichkeitsgesetz.ch/deutsch/) - Free resources on access to official documents, including federal and cantonal freedom-of-information rules, practical guidance, and reporting on transparency cases.

## Judicial Decisions

### Federal Courts

- [Federal Supreme Court](https://www.bger.ch/index/juridiction/jurisdiction-inherit-template/jurisdiction-recht.htm) - Official full-text databases: selected leading decisions (BGE) from 1954, other judgments largely from 2000 and comprehensively from 2007. The overview also links earlier BGE volumes. Judgments are generally anonymized and published in the language of the proceedings.
- [Federal Administrative Court (BVGer)](https://bvger.weblaw.ch/dashboard) - Official search for published Federal Administrative Court decisions, hosted by Weblaw.
- [Federal Criminal Court (BStGer)](https://bstger.weblaw.ch/) - Official search for published Federal Criminal Court decisions, hosted by Weblaw; selected decisions form the TPF report series.
- [Federal Patent Court](https://www.bundespatentgericht.ch/rechtsprechung/aktuelle-entscheide) - Official collection of patent-dispute judgments, with an archive from 2012 onward.

### Case-Law Search

For cantonal decisions, this list uses independent aggregators as the entry point; official cantonal court portals are not individually listed. These services provide cross-court search; publication and collection coverage vary. Follow original-source links where available to consult the publishing court. For downloadable research corpora, see [research datasets](#research-datasets--benchmarks).

- [OpenCaseLaw](https://opencaselaw.ch/) - Independent search across published federal, cantonal, and regulatory decisions, with metadata and citation links. Provides a REST API, CLI, [Parquet dataset](https://huggingface.co/datasets/voilaj/swiss-caselaw), and [MCP access](#mcp-servers--agent-integrations). Swiss corpus published under CC0; third-party materials may have separate terms. [Source code](https://github.com/jonashertner/opencaselaw) (MIT).
- [Entscheidsuche.ch](https://entscheidsuche.ch/search?query=%2a) - Non-profit search across published federal and cantonal decisions. Offers an [API](https://entscheidsuche.ch/pdf/EntscheidsucheAPI.pdf), [document downloads](https://entscheidsuche.ch/docs/), and [MCP access](#mcp-servers--agent-integrations). [Source code](https://github.com/entscheidsuche).

### Specialist Collections

- [Equality Law](https://www.equality-law.ch/de/) - Free nationwide database of court and conciliation cases concerning the Gender Equality Act, with commentary and procedural resources in DE/FR/IT. Unifies the former regional equality-law databases.
- [Federal Commission against Racism Case Database](https://www.ekr.admin.ch/dienstleistungen/d518.html) - Searchable, anonymized summaries of criminal decisions concerning the anti-discrimination provisions of the Criminal Code and Military Criminal Code. Summaries are available online and as PDFs; coverage is not exhaustive.

## Administrative Decisions & Regulatory Practice

Official collections of decisions, reports, and recommendations.

- [Federal Administrative Practice (VPB/JAAC/GAAC)](https://www.bar.admin.ch/de/amtsdruckschriften-weitere-digitalisierte-unterlagen) - Decisions, legal opinions, leading Federal Council and administration decisions, and reports concerning federal administrative law.
- [FINMA Enforcement Reporting](https://www.finma.ch/en/documentation/enforcement-reporting/) - Selected rulings, searchable anonymized enforcement case reports, related court decisions, and enforcement statistics.
- [Competition Commission Decisions](https://www.weko.admin.ch/en/decisions-2) - COMCO/WEKO competition-law decisions, investigation reports, and merger opinions.
- [FDPIC Findings and Rulings](https://www.edoeb.admin.ch/en/rulings) - Published findings and administrative rulings of general interest under the Federal Act on Data Protection.
- [FDPIC Freedom of Information Recommendations](https://www.edoeb.admin.ch/en/recommendations-according-to-foia) - Recommendations issued after unsuccessful mediation under the Freedom of Information Act.
- [ElCom Decisions](https://www.elcom.admin.ch/en/decisions-en) - Decisions of the independent electricity regulator concerning tariffs, grid access, security of supply, and international electricity trading.
- [ComCom Decisions](https://www.comcom.admin.ch/de/entscheide) - Decisions of the Federal Communications Commission concerning telecommunications regulation and licensing.
- [OFCOM/BAKOM Decision Database](https://www.bakom.admin.ch/de/entscheiddatenbank) - Selected leading decisions on broadcasting and telecommunications, including new legal questions and changes in regulatory practice.
- [Federal Arbitration Commission for Copyright (ESchK/CAF)](https://www.eschk.admin.ch/de/beschluesse) - Published decisions on the collective management of copyright and related rights, organized by year back to 1991. Decisions appear in their original official language and may be anonymized or abridged.
- [PostCom Decisions](https://www.postcom.admin.ch/de/verfuegungen) - Official PDF decisions on postal universal service, delivery, mailbox locations, sectoral working conditions, and cross-subsidization, with information on appeal status.

## Administrative Guidance & Drafting Resources

Official guidance on applying or drafting legislation, distinct from the legislation itself.

- [Federal Tax Administration Publications](https://www.estv.admin.ch/de/publikationen-direkte-bundessteuer) - Circulars, notices, factsheets, rates, and administrative practice concerning direct federal tax.
- [Federal Social Insurance Office Execution Portal](https://sozialversicherungen.admin.ch/) - Current and historical directives, circulars, notices, and selected social-insurance case law.
- [SEM Directives and Circulars](https://www.sem.admin.ch/sem/de/home/publiservice/weisungen-kreisschreiben.html) - Administrative guidance on migration, free movement, asylum, integration, citizenship, data protection, and visas.
- [SEM Asylum and Return Manual](https://www.sem.admin.ch/sem/de/home/asyl/asylverfahren/nationale-verfahren/handbuch-asyl-rueckkehr.html) - Published internal working manual covering asylum procedure, evidence, refugee status, removal, and legal remedies.
- [Swissmedic Journal](https://www.swissmedic.ch/swissmedic/en/home/about-us/publications/swissmedic-journal.html) - Official monthly publication on therapeutic-product regulation, requirements, risks, and authorization decisions.
- [FINMA Circulars](https://www.finma.ch/en/documentation/circulars/) - Freely available explanations of FINMA's application of financial-market legislation, filterable by supervised institution type, with an [archive of earlier circulars](https://www.finma.ch/en/documentation/archiv/rundschreiben/).
- [SECO Labour Act Guidance](https://www.seco.admin.ch/de/wegleitungen) - Official commentary on the Labour Act and its ordinances, with practical examples, complete PDF manuals, individual article PDFs, and change lists.
- [Federal Legislative Drafting Guide](https://www.bk.admin.ch/dam/de/sd-web/mlOCkXFnLE6C/Gesetzgebungsleitfaden-dt.pdf) - Federal Office of Justice handbook on preparing federal legislation, including legislative procedure, legal requirements, and drafting methodology. Freely downloadable PDF, fifth edition (2025).
- [Federal Legislative Drafting Directives (GTR)](https://www.bk.admin.ch/de/gesetzestechnik) - Federal Chancellery guidance on the structure, wording, amendment, and citation of federal enactments, with downloadable directives.
- [TRIAS Public Procurement Guide](https://www.trias.swiss/) - Joint federal, cantonal, and municipal guidance on procurement procedures, with legal references, checklists, templates, and factsheets in DE/FR/IT. Free to consult; the site requires acceptance of its terms and confirmation of location in Switzerland or Liechtenstein.
- [TERMDAT](https://www.termdat.ch/) - Federal Administration's multilingual terminology database for legal and administrative terms.

## Public Registers & Regulatory Disclosures

- [SIMAP](https://www.simap.ch/) - Official Swiss public-procurement platform for tender notices, awards, and procurement documents. Its [JSON API terms](https://www.simap.ch/en/about/legal) permit access to public publications without authentication and reuse under stated conditions.
- [Zefix](https://opendata.swiss/en/dataset/zefix-zentraler-firmenindex) - Official Central Business Name Index with daily updated company core data, Linked Open Data, and a REST API.
- [UID Web Service](https://www.bk.admin.ch/de/uid-webservice) - Official SOAP/XML service for the Swiss enterprise identification register. Public company search and VAT-number validation require no registration.
- [Swissreg](https://www.swissreg.ch/) - Official publication and search service for Swiss trademarks, patents, designs, supplementary protection certificates, and emblems. A documented [IPI Data Delivery API](https://www.swissreg.ch/public/apidocs/) is available with registration.
- [SECO Sanctions Data](https://www.seco.admin.ch/en/searching-for-subjects-sanctions) - Searchable and machine-readable consolidated list of sanctioned individuals, companies, and organizations, with XML data, value lists, and an XSD specification.
- [Public-Law Restrictions on Landownership (PLR/ÖREB/RDPPF Cadastre)](https://www.swisstopo.admin.ch/en/plr-cadastre) - Official public information on restrictions affecting individual parcels. The documented [extract web service](https://www.cadastre-manual.admin.ch/fr/service-web-rdppf-appel-extrait) connects to cantonal systems and supports PDF and XML extracts, with optional JSON support.

## International Decisions & Arbitration

- [HUDOC](https://www.echr.coe.int/en/hudoc-database) - European Court of Human Rights case law, communicated cases, legal summaries, and Committee of Ministers execution decisions, filterable by Switzerland.
- [UN Treaty Body JURIS Database](https://juris.ohchr.org/) - Decisions on individual human-rights complaints before eight United Nations treaty bodies, searchable by country.
- [Court of Arbitration for Sport Jurisprudence](https://jurisprudence.tas-cas.org/) - Published sports-arbitration decisions and awards. Relevant to Swiss arbitration research through the Swiss Federal Supreme Court’s review of CAS awards; see the [CAS explanation](https://www.tas-cas.org/en/general-information/frequently-asked-questions).
- [WTO Dispute Settlement Database](https://data.wto.org/en/dataset/disputedb) - Proceedings, documents, agreements, provisions, and statistics for WTO disputes, searchable by member including Switzerland.

## Commentary, Journals & Legal Literature

### Commentaries & Case Analyses

- [Onlinekommentar.ch](https://onlinekommentar.ch/) - Non-profit, open-access commentaries on Swiss law, with an [API](https://onlinekommentar.ch/en/apis).
- [LawInside](https://lawinside.ch/a-propos/) - Free French-language summaries and analyses of recent Swiss case law, primarily leading Federal Supreme Court decisions.
- [crimen.ch](https://www.crimen.ch/a-propos/) - Free French-language summaries and commentary on Swiss substantive criminal law, criminal procedure, and international mutual assistance in criminal matters.
- [swissprivacy.law](https://swissprivacy.law/a-propos/) - Free French-language analysis of data-protection and transparency law, covering judgments, regulatory decisions, legislation, and scholarship.

### Journals

- [sui-generis.ch](https://sui-generis.ch/) - Open-access Swiss law journal and publisher of legal books, including textbooks.
- [ex/ante](https://www.ex-ante.ch/) - Open-access journal publishing articles, essays, and case comments by early-career legal scholars.
- [LeGes](https://leges.weblaw.ch/die-zeitschrift.html) - Open-access journal on legislation, legal drafting, and evaluation of government action; current issues and archive are free to read.
- [cognitio](https://www.cognitio-zeitschrift.ch/) - Open-access journal for students and early-career researchers, covering Swiss law, legal theory, and interdisciplinary work.

### Repositories & Catalogues

- [Repositorium.ch](https://www.repositorium.ch/) - Free full-text repository for Swiss legal scholarship from multiple institutions.
- [legalis science](https://www.legalis-science.ch/de/) - Open-access collection of Swiss legal dissertations, monographs, and edited volumes from Helbing Lichtenhahn and Dike, with links to publisher-hosted PDFs. Reuse terms depend on the individual publication.
- [juscovery](https://lawlibraries.ch/?page_id=2742) - Free catalogue search across Swiss legal-library collections (swisscovery, Renouvaud, Helveticat). Records identify literature; full texts may require library access or payment.

## Legal History & Archives

The [Swiss Federal Archives AppLab](https://applab.bar.admin.ch/de/datenbanken-und-apis) is an umbrella catalogue for archival databases and APIs, including the historical legislation and consultation datasets below. Collections can overlap with current publication portals; their value here is historical coverage and downloadable archival material.

- [Historical Federal Law (AS 1948-2018)](https://applab.bar.admin.ch/databases-and-apis/official-compilation-of-federal-legislation) - Swiss Federal Archives bulk download of Official Compilation texts from 1948 to 2018 as XML, with classification tables in German, French, and Italian.
- [Consultation Procedures Dataset (1960-1991)](https://applab.bar.admin.ch/de/datenbanken-und-apis/vernehmlassungen) - Metadata on federal consultation procedures (Vernehmlassungen) from 1960 to 1991.
- [Digitized Federal Publications](https://opendata.swiss/de/dataset/ads) - Open dataset covering parliamentary records, the Federal Gazette, federal law, Federal Council records, administrative practice, and other historical official publications.
- [Collection of Swiss Law Sources (SSRQ/SDS/FDS)](https://ssrq-sds-fds.ch/digital/online/) - Historical legal sources through 1798, including TEI/XML editions, entity indexes, OCR volumes, and underlying datasets on Zenodo.
- [E-Periodica](https://www.e-periodica.ch/digbib/about?lang=en) - ETH Library platform for historical Swiss journals. Useful for tracing earlier legal scholarship and case commentary; offers PDF, image, and full-text downloads. Reuse terms depend on the publication.
- [e-rara](https://www.e-rara.ch/doc/home?lang=en) - Digitized books and prints from Swiss libraries, useful for historical legal treatises and older printed law collections. Check the item’s rights statement for reuse terms.
- [Diplomatic Documents of Switzerland (Dodis)](https://www.dodis.ch/de/open-science) - Open-access historical sources on Swiss foreign relations, useful for researching treaty negotiations and international legal history. Document metadata is available as open data; content is CC BY 4.0 unless otherwise indicated.

## Research Datasets & Benchmarks

Derived corpora and benchmarks support empirical research and software evaluation. Date ranges describe the linked release or corpus; benchmark subsets may omit documents or text sections. Check dataset cards for selection criteria, versions, and reuse terms.

- [Swiss Federal Supreme Court Dataset (SCD)](https://zenodo.org/records/14867950) - Federal Supreme Court case metadata for 2007–2024 in CSV, with judgment texts in a separate Parquet file. The linked release reports interrupted updates as of October 2025; see its status note before assuming current coverage.
- [Swiss Judgment Prediction (FSCS Corpus)](https://zenodo.org/records/5529712) - Federal Supreme Court judgment texts from 2000–2020 in German, French, and Italian for natural-language processing and judgment prediction. [Experiment code](https://github.com/JoelNiklaus/SwissJudgementPrediction).
- [Swiss Landmark Decisions Summarization (SLDS)](https://huggingface.co/datasets/ipst/slds) - Federal Supreme Court rulings paired with official headnote summaries for cross-language summarization in German, French, and Italian. CC BY 4.0.
- [RCDS Swiss Legal Datasets](https://huggingface.co/rcds/datasets) - Research dataset collection for Swiss legal retrieval, citation extraction, classification, summarization, and judgment prediction. Coverage and licences vary by dataset.
- [Swiss Legal RAG Bench](https://huggingface.co/datasets/voilaj/swiss-legal-rag-bench) - CC0 benchmark for testing whether AI answers are supported by retrieved Swiss federal-law passages (retrieval-augmented generation, or RAG).
- [SwiLTra-Bench](https://huggingface.co/collections/joelniklaus/swiltra-bench) - Parallel-text corpora for Swiss legal translation: federal legislation, decision headnotes, and court press releases in German, French, and Italian, plus Romansh and English for legislation. Licensing is unspecified in the dataset cards. [Preparation code](https://github.com/JoelNiklaus/SwissLegalTranslations).
- [LEXam](https://huggingface.co/datasets/LEXam-Benchmark/LEXam) - University law-exam questions and reference answers for evaluating legal reasoning. Includes multiple jurisdictions; filter for Swiss-law material. German and English; Parquet, CC BY 4.0. [Project](https://lexam-benchmark.github.io/).

For a broader bulk decision corpus, see the Parquet download under [OpenCaseLaw](#case-law-search).

## Developer Tools & Infrastructure

### APIs, Metadata & Libraries

Source-specific APIs are linked alongside their datasets and registers.

- [Fedlex Linked Data](https://lindas.admin.ch/data-usage/fedlex/) - Programmatic access to federal-law metadata, versions, and document links via SPARQL, a query language for linked data. Includes the [JOLux data model](https://github.com/swiss/fedlex-jolux) and a [query tutorial](https://github.com/swiss/fedlex-sparql).
- [swissparl](https://github.com/zumbov2/swissparl) - R client for Parliament's OData services and OpenParlData's REST API, with examples for votes, speeches, and parliamentary business. MIT.
- [pyramid_oereb](https://github.com/openoereb/pyramid_oereb) - Python server implementation for the PLR cadastre and cadastral extracts. BSD 2-Clause; available on [PyPI](https://pypi.org/project/pyramid-oereb/).
- [SwissLegalEvals](https://github.com/JoelNiklaus/SwissLegalEvals) - MIT-licensed evaluation framework for Swiss legal summarization, translation, and exam reasoning using SLDS, SwiLTra-Bench, and LEXam. Supports local models and API providers; hosted model usage may incur costs.

### AI Applications

- [Alma Lex](https://almalex.ch/en/) - Free legal AI demo grounded in federal legislation and Federal Supreme Court decisions. The site and repository give conflicting descriptions of chat privacy. [Source code](https://github.com/gartmeier/almalex) (MIT).
- [Fragmeisterjuristen.ch](https://www.fragmeisterjuristen.ch/) - Free experimental chatbot answering Swiss-law questions with references to historical legal scholarship; generated answers are not source texts.

### MCP Servers & Agent Integrations

Model Context Protocol (MCP) lets compatible AI tools query external sources. These are third-party integrations, not official government services; their software licences do not determine the terms of upstream data or AI clients.

> Review the operator, code, permissions, and data flows before enabling a server. Depending on configuration, local or remote integrations may transmit data, access files, or execute commands.

- [OpenCaseLaw MCP server](https://opencaselaw.ch/mcp) - Hosted interface to the [OpenCaseLaw corpus](#case-law-search), with decision retrieval, citation traversal, and legislation search. Free access without an API key; [server code](https://github.com/jonashertner/opencaselaw) is MIT-licensed.
- [Entscheidsuche MCP server](https://mcp.entscheidsuche.ch/) - Hosted search and full-text retrieval for [Entscheidsuche](#case-law-search), without an API key. [Server code](https://github.com/entscheidsuche/entscheidsuche-mcp); package metadata declares MIT.
- [malkreide/swiss-courts-mcp](https://github.com/malkreide/swiss-courts-mcp) - Alternative client for the Entscheidsuche API, supporting federal and cantonal decision search. Coverage depends on the upstream collection. MIT.
- [malkreide/fedlex-mcp](https://github.com/malkreide/fedlex-mcp) - Queries official Fedlex legislation, publications, treaties, and consultations, plus TERMDAT terminology. MIT.
- [JayTheSkier/fedlex-connector](https://github.com/JayTheSkier/fedlex-connector) - Retrieves Swiss federal legislation from Fedlex for compatible AI clients. MIT.
- [malkreide/swiss-ip-mcp](https://github.com/malkreide/swiss-ip-mcp) - Queries Swissreg trademark, patent, and supplementary protection certificate data through the IPI API. Requires IPI API credentials; MIT software licence.
- [malkreide/register-mcp](https://github.com/malkreide/register-mcp) - Queries Zefix company records and related official-gazette notices. MIT; upstream access requirements are documented in the repository.
- [BetterCallClaude](https://github.com/fedec65/bettercallclaude) - Claude plugin combining Swiss legal research and document workflows through multiple MCP servers. Plugin: AGPL-3.0; [MCP-server source](https://github.com/fedec65/BetterCallClaudeMCP) is maintained separately.

## Community & Related Directories

### Discovery Resources

- [opendata.swiss Justice Catalogue](https://opendata.swiss/en/group/just) - Federal, cantonal, and municipal open datasets concerning justice, public safety, convictions, criminal procedure, and related government activity.
- [Center for Legal Data Science (UZH)](https://www.clds.uzh.ch/en/knowledge/databases.html) - Data-driven legal research and dataset links.
- [University of Basel Open-Access Directory](https://ius.unibas.ch/de/bibliothek/recherche/open-access/) - Directory of freely accessible legal repositories, journals, and blogs.
- [Awesome Legal Data](https://github.com/openlegaldata/awesome-legal-data) - Curated list of open legal data sources, tools, and resources worldwide.

### Community & Events

- [ejustice.ch](https://ejustice.ch/) - Association bringing together authorities, practitioners, and technology providers to develop digital justice in Switzerland.
- [Open Legal Lab](https://ejustice.ch/open-legal-lab/) - ejustice.ch event for developing Swiss legal and justice technology with legal, data, and software practitioners.

## Contributing

Suggest additions or corrections via an [issue](https://github.com/rnckp/awesome-open-legal-switzerland/issues) or pull request.

- Explain the Swiss legal use, content, and coverage, with a direct resource link. Identify the original publisher, aggregator, or derived dataset.
- State access requirements and known reuse terms. Distinguish free access, open data, and open-source code, including which material a licence covers.
- Prefer one main entry per project. Link APIs, downloads, and code together unless they serve distinct tasks; cross-reference related entries.
- Date release-specific claims; omit volatile record counts and unsupported completeness claims.
- Place entries by the material or task they support, with official sources before independent interfaces and supporting tools.

## Licence

This list is released under [CC0 1.0](LICENSE). Linked resources retain their own licences and terms.
