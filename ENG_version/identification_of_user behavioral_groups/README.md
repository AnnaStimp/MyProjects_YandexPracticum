# Mobile application “Unnecessary things” - Identification of user groups based on behavior

## Data

*mobile_sources.csv:*
- ``userId`` — user identifier,
- ``source`` — the source from which the user installed the application.

*mobile_dataset.csv:*
- ``event.time`` — time of occurrence,
- ``user.id`` — user identifier,
- ``event.name`` - user action.

*Possible event.name:*
- ``advert_open`` — opened ad cards,
- ``photos_show`` — looked at the photos in the ad,
- ``tips_show`` — saw recommended ads,
- ``tips_click`` - clicked on the recommended ad,
- ``contacts_show and show_contacts`` - looked at the phone number,
- ``contacts_call`` — called the number from the ad,
- ``map`` — opened the ad map,
- ``search_1 - search_7`` - various actions related to site search,
- ``favorites_add`` - added the ad to favorites.

## Task

There is a mobile application where people sell their unwanted items. There is data from users who performed actions in the application for the first time after October 7, 2019. It is necessary to divide users into groups (segments) according to various metrics and determine which users are the most *productive*.

## Libraries used
*pandas*, *matplotlib*, *numpy*, *plotly.express*, *seaborn*, *statsmodels.stats*