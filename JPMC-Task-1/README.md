<h1>Task Objectives</h1>
<ol>
    <li>Set up your local dev environment by downloading the necessary files, tools and dependencies.</li>
    <li>Fix the broken client datafeed script in the repository by making the required adjustments to it.</li>
    <li>Add unit tests in the test script in the repository.</li>
    <li>Generate a patch file of the changes you made.</li>
</ol>

<h1>Engineering Ticket</h1>
<h2>Purpose</h2>
We want to process the data feed of stock A and stock B's price to enable us to analyse when trading for the stock should occur.

<h2>Acceptance Criteria</h1>
<ul>
    <li>getDataPoint function should return correct tuple of stock name, bid_price, ask_price and price. Note: price of a stock = average of bid and ask</li>
    <li>getRatio function should return the ratio of the two stock prices</li>
    <li>main function should output correct stock info, prices and ratio</li>
</ul>