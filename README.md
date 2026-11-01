# PROCESS Replication Dashboard (web copy)

**Open it: https://suppanut.github.io/process-replication-dashboard/**

An interactive dashboard from a project that tried to replicate analyses done with the PROCESS macro
(mediation, moderation and conditional process models) in 2025 psychology papers from Frontiers in Psychology,
BMC Psychology and PLOS ONE. For the 120 papers whose authors shared raw data, the analyses were re-run in R with
PROCESS v5.0 and compared with the published estimates.

The dashboard has seven pages: papers identified, raw-data availability, replication results and hypotheses, a
paper-by-paper table, the PROCESS output and R script of each replication, the data behind each run, and how each
paper reported its PROCESS results (tables, figures and Results text).

## What is in this repository
`index.html` is the whole dashboard in one self-contained file (about 0.8 MB). Its data are compressed inside it, so
it looks like a binary file on GitHub. It needs no server and no internet connection once loaded.

## About the data
- **Respondent-level data are not included.** The data tables show only their header and first 10 rows, to show
  their layout. The data belong to the original authors: each paper's page in the dashboard links to its data
  source (under "Original data"), and its data statement gives the licence.
- **Quoted article text and tables** (the Results text and the PROCESS tables on the Reporting page) are reproduced
  unchanged from the open-access articles, under their CC BY 4.0 or CC BY-NC-ND 4.0 licences. The source, authors
  and licence of each paper are shown with it.
- Everything else (verdicts, hypothesis summaries, outputs, scripts) is the result of this project's analysis.

The page asks search engines not to index it. It is public: anyone with the link can open it.
