# Awesome Open Legal Data Switzerland

[![GitHub Stars](https://img.shields.io/github/stars/rnckp/awesome-open-legal-switzerland.svg)](https://github.com/rnckp/awesome-open-legal-switzerland)
[![GitHub Issues](https://img.shields.io/github/issues/rnckp/awesome-open-legal-switzerland.svg)](https://github.com/rnckp/awesome-open-legal-switzerland)
[![GitHub Issues](https://img.shields.io/github/issues-pr/rnckp/awesome-open-legal-switzerland.svg)](https://img.shields.io/github/issues-pr/rnckp/awesome-open-legal-switzerland)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A manually curated list of open legal data sources, tools, and resources in Switzerland.

## Contents

- [Federal Legislation & Official Publications](#federal-legislation--official-publications)
- [Cantonal Legislation](#cantonal-legislation)
- [Judicial Decisions](#judicial-decisions)
- [Parliamentary Data](#parliamentary-data)
- [Legal Commentary & Secondary Sources](#legal-commentary--secondary-sources)
- [Legal Data Infrastructure & Metadata](#legal-data-infrastructure--metadata)
- [International Law](#international-law)
- [Contribute](#contribute)

## Parliamentary Data

- [Swiss Parliament](https://www.parlament.ch/de/suche) - Federal Assembly data. [Web service](https://ws-old.parlament.ch/) available.
- [OpenParlData.ch](https://openparldata.ch/) - Harmonized [API](https://api.openparldata.ch/documentation) offering data on political actors, legislative proposals, motions, and voting results across 78 parliaments (federal, cantonal, municipal).
- [Consultation Procedures Dataset (1960-1991)](https://applab.bar.admin.ch/de/datenbanken-und-apis/vernehmlassungen) - Metadata on federal consultation procedures (Vernehmlassungen).
- [Official Bulletins](https://www.parlament.ch/de/ratsbetrieb/amtliches-bulletin) - Full transcripts of Federal Assembly debates from 1891 onward.

## Federal Legislation & Official Publications

- [Fedlex](https://www.fedlex.admin.ch/) - Publication platform for Swiss federal law. Includes the Systematic Compilation of Federal Law (SR), Official Compilation (AS), Federal Gazette (BBl), international treaties, and consultation procedures. Multilingual (DE/FR/IT) with SPARQL endpoint.
- [Historical Federal Law (AS 1948-2018)](https://applab.bar.admin.ch/databases-and-apis/official-compilation-of-federal-legislation) - Bulk data archive from the Swiss Federal Archives. All Official Compilation files from 1948-2018 as XML with legal classification tables in three languages.
- [Swiss Federal Gazette (BBl)](https://www.fedlex.admin.ch/de/fga) - Official journal of federal legislation. Publishes drafts, dispatches, and official texts weekly. Archives back to 1849 accessible via Fedlex.
- [Official Gazettes Portal (Amtsblattportal)](https://amtsblattportal.ch/) - Central platform for official legal notices. Hosts the Swiss Official Gazette of Commerce (SOGC/SHAB) and cantonal gazettes. [REST API](https://amtsblattportal.ch/docs/api/) available.

## Legal Data Infrastructure & Metadata

- [Fedlex Linked Data](https://lindas.admin.ch/data-usage/fedlex/) - Persistent URIs for each act/article. SPARQL endpoint with documented ontology (JOLux data model). Enables programmatic retrieval of law texts, metadata, versions, and relationships.
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
- [Zürich ZHLAW](https://www.zhlaw.ch/) - Private project that aims to improve the digital accessibility of the Canton of Zurich's law collection.
- [Intlex](https://www.intlex.ch/) - Intlex currently contains all intercantonal agreements to which the cantons of Zug, Schaffhausen, St. Gallen, Graubünden, Thurgau, and Valais are currently party.

## Judicial Decisions

### Federal Courts

- [Federal Supreme Court](https://www.bger.ch/ext/eurospider/live/de/php/clir/http/index.php?lang=de) - Official database with all judgments (mostly anonymized) from 1954 onward. Newer decisions (since ~2000) available in full text (DE/FR/IT). Identifies precedential cases (BGE).
- [Federal Administrative Court (BVGer)](https://bvger.weblaw.ch/dashboard) - Decisions of the Bundesverwaltungsgericht.
- [Federal Criminal Court (BStGer)](https://bstger.weblaw.ch/) - All important rulings published online. Selected decisions compiled in official "TPF" report series.
- [Federal Patent Court](https://www.bundespatentgericht.ch/rechtsprechung/aktuelle-entscheide) - First-instance patent dispute judgments. Searchable archive from 2012 onward.

### Aggregated & Research Data

- [Entscheidsuche.ch](https://entscheidsuche.ch/search?query=%2a) - Non-profit initiative aggregating all publicly available Swiss court decisions (federal and cantonal). [[GitHub](https://github.com/entscheidsuche)]
- [Swiss Federal Supreme Court Dataset (SCD)](https://zenodo.org/records/14867950) - Structured dataset of all Federal Supreme Court cases 2007-2024 (127k+ cases). Updated quarterly. Released under CC-BY 4.0.
- [FSCS Swiss Court Decisions Corpus](https://zenodo.org/records/5529712) - Multilingual text corpus of 85k Federal Supreme Court judgments (2000-2020) in DE/FR/IT for NLP research and legal judgment prediction. [[GitHub](https://github.com/JoelNiklworthy/Swiss-Judgment-Prediction)]
- [Swiss Landmark Decisions Summarization (SLDS)](https://huggingface.co/datasets/ipst/slds) - Cross-lingual dataset with 20k Federal Supreme Court rulings paired with official headnote summaries in DE/FR/IT (60k data points). Released under CC-BY 4.0.
- [Justement.ch](https://justement.ch/) - Commercial. Legal search engine aggregating Swiss court decisions. Free tier for Federal Supreme Court decisions; advanced features require paid subscription.

## Legal Commentary & Secondary Sources

- [Onlinekommentar.ch](https://onlinekommentar.ch/) - The first non-profit and Open Access commentary platform in Switzerland. [[API](https://onlinekommentar.ch/en/apis)]
- [Repositorium.ch](https://www.repositorium.ch/) -  Specialist subject repository for Swiss law. Central, freely and openly accessible, Switzerland-wide and Switzerland-related, institution-independent and discipline-specific.
- [Fragmeisterjuristen.ch](https://fragmeisterjuristen.ch/) - Open-access legal AI chatbot by University of St. Gallen (2024). Answers questions on Swiss law with citations to classical legal scholarship.
- [sui-generis.ch](https://sui-generis.ch/) - Open-access law journal and non-profit publisher. Published Switzerland's first open-access law textbook "Introduction to Swiss Law" (2018).
- [ex/ante](https://www.ex-ante.ch/) - Open-access journal for (young) legal scholars. Publishes peer-reviewed articles, essays, and case comments in multiple languages.
- [Center for Legal Data Science (UZH)](https://www.clds.uzh.ch/en/knowledge/databases.html) - Data-driven legal research and dataset links.

## Miscellaneous

- [Open Access content collection University of Basel](https://ius.unibas.ch/de/bibliothek/recherche/open-access/) - List of repositories, collections, e-journals and blogs with open access content.
- [ejustice.ch](https://ejustice.ch) - Association connecting cantonal and federal legal authorities, practitioners, service providers, and stakeholders to promote digital innovation in Swiss justice administration.
- [Open Legal Lab](https://ejustice.ch/open-legal-lab/) - Free two-day event bringing together legal, tech, design, and data experts to develop innovative solutions for Swiss justice.
- [Awesome Legal Data](https://github.com/openlegaldata/awesome-legal-data) - Curated list of open legal data sources, tools, and resources worldwide.
