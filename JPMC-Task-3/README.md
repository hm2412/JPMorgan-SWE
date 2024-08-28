<h1>Task Objectives</h1>
<ol>
    <li>Set up your system by downloading the necessary files, tools and dependencies.</li>
    <li>Modify the typescript files in the project repo to make the web application behave in the expected manner.</li>
    <li>Generate a patch file of the changes you made.</li>
</ol>

<h1>Engineering Ticket</h1>
<h2>Purpose</h2>
You will use perspective to generate a live graph that displays the data feed in a clear and visually appealing way for traders to monitor.

Recall that the purpose of this graph is to monitor and determine when a trading opportunity may arise as a result of the temporary weakening of a correlation between two stock prices. Given this graph, the trader should be able to quickly and easily notice when the ratio moves too far from the average historical correlation. In the first instance, we'll assume that threshold is +/-10% of the 12-month historical average ratio.

<h2>Acceptance Criteria</h1>
<ul>
    <li>This ticket is done when the numbers from the python script render properly in the live perspective graph. That means the ratio between the two stock prices is tracked and displayed, the upper and lower bounds are shown on the graph, and an alert is shown whenever the bounds are crossed.</li>
</ul>
