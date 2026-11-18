# DDF Funders Network

An interactive map of the grant programs the **Doris Duke Foundation (DDF)** funds together with other philanthropies, and the funders behind them.

**Live page:** https://bombaywalli.github.io/ddf-funders-network/

## What it shows

- **15 programs** where DDF is a named funder, across Arts, Child Well-being, Environment and Medical Research, plus one cross-program fund
- **95 co-funders**, with endowment size and website where found
- Which partners recur most (Ford and Mellon, 6 programs each) and which funders bridge DDF program areas (Hewlett and Packard)
- Whether each program is a pooled fund, a joint initiative or co-funded grants

## How to use it

- **Network:** squares are programs (sized by amount), dots are funders (sized by endowment). A line means the funder backs that program. Hover for details, click for the full card, scroll to zoom.
- **Co-funders table:** sortable list of every funder; copy it as CSV.
- **Programs timeline:** programs by year and size, 2008 to 2026.
- Filter by program area or year range, search by name, or press Play to watch the network grow over time.

## Data and limits

Built from public announcements, press releases and tax filings; research as of November 18, 2026. Each program card links to its source. Amounts mean different things by program (a pledge, a goal, a first round, a cumulative total), and endowments were found for only some funders. The list covers programs where DDF is a named funder, not each funder's full portfolio, and DDF's full grants database was not searched, so some programs may be missing. Check the source before citing any figure.

## Built with

A single `index.html` file using [D3.js](https://d3js.org). Built with Claude, starting from the prompts behind the [original DDF Funders Network](https://ddf-constellation.vercel.app/).
