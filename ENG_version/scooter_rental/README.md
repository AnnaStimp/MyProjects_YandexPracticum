# Study of scooter rental service GoFast


## Data

*Users*
- ``user_id`` - unique user identifier
- ``name`` - user name
- ``age`` - age
- ``city`` - city
- ``subscription_type`` - subscription type (free, ultra)

*Trips*
- ``user_id`` - unique user identifier
- ``distance`` - the distance the user has traveled in the current session (in meters)
- ``duration`` - session duration (in minutes) - the time from the moment the user pressed the “Start trip” button until the moment he pressed the “End trip” button
- ``date`` - date of the trip

*Subscriptions*
- ``subscription_type`` - subscription type
- ``minute_price`` - the cost of one minute of travel for this subscription
- ``start_ride_price`` - cost of starting the trip
- ``subscription_fee`` - monthly payment cost

## Task

See the connection between the client’s marital status, the number of children and the fact of timely repayment of the loan. The results of the study will be taken into account when constructing a credit scoring model - a special system that assesses the ability of a potential borrower to repay a loan to the bank.

## Libraries used
*pandas*, *matplotlib*, *numpy*, *scipy*, *math*