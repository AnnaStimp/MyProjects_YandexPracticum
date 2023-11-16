# Research into the causes of losses at Procrastinate Pro+


## Data

Structure *visits_info_short.csv*:

- ``User Id`` - unique user identifier,
- ``Region`` — user country,
- ``Device`` — user device type,
- ``Channel`` — transition source identifier,
- ``Session Start`` — date and time of the start of the session,
- ``Session End`` — date and time of the end of the session.

Structure *orders_info_short.csv*:
- ``User Id`` - unique user identifier,
- ``Event Dt`` — date and time of purchase,
- ``Revenue`` — order amount.

Structure *costs_info_short.csv*:
- ``dt`` — date of the advertising campaign,
- ``Channel`` — advertising source identifier,
- ``costs`` — expenses for this campaign.

## Task

There is an entertainment application Procrastinate Pro+. Huge investments have been made in advertising, but the company is still losing money. It is necessary to understand the reasons and help the company become profitable.

## Libraries used
*pandas*, *matplotlib*, *numpy*, *seaborn*, *datetime*