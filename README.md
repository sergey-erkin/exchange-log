# exchange-log
Exchange Log is a converter for Telegram Change Bot reports.

**Motivation**.
Change Bot produces a report with history of exchanges.
The report has simple csv format, which is not good enough to collect some usefull statistics: exchange amount per day, average exchange rate, etc
. Exchange log updates the report with several enhancements:
1. It converts report to xlsx (modern ms excel format).
2. It removes canceled trades.
2. It splits solid history to one-day groups.
3. It sums fiat for every one-day group.

**How to use**.
todo
