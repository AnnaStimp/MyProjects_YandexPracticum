# Testing hypotheses to increase revenue


## Data

*Hypothesis*
- ``Hypothesis`` - a brief description of the hypothesis;
- ``Reach`` — user coverage on a 10-point scale;
- ``Impact`` - influence on users on a 10-point scale;
- ``Confidence`` — confidence in the hypothesis on a 10-point scale;
- ``Efforts`` - resource costs for testing the hypothesis on a 10-point scale. The higher the Efforts value, the more expensive it is to test the hypothesis.

*Orders*
- ``transactionId`` — order identifier;
- ``visitorId`` — identifier of the user who made the order;
- ``date`` — the date when the order was made;
- ``revenue`` — order revenue;
- ``group`` — the A/B test group into which the order fell.

*Visitors*
- ``date`` — date;
- ``group`` — A/B test group;
- ``visitors`` — the number of users on the specified date in the specified A/B test group.

## Task

I am an analyst for a large online store. Together with the marketing department, a list of hypotheses was prepared to increase revenue. Need prioritize hypotheses, run an A/B test and analyze the results.

## Libraries used
*pandas*, *matplotlib*, *numpy*, *scipy*