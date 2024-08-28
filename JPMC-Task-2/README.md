<h1>Task Objectives</h1>
<ol>
    <li>Set up your local dev environment by downloading the necessary files, tools and dependencies.</li>
    <li>Fix the broken typescript files in repository to make the web application output correctly</li>
    <li>Generate a patch file of the changes you made.</li>
</ol>

<h1>Engineering Ticket</h1>
<h2>Purpose</h2>
The objective of this task will be for you to fix the client-side web application so that it displays a graph that automatically updates as it gets data from the server application (see Before and After images below). Currently, the web application only gets data every time you click on the 'Start Streaming Data' button and does not aggregate duplicated data.

<h2>Acceptance Criteria</h1>
<ul>
    <li>This ticket is done when the graph displayed in the client-side web application is a continuously updating line graph whose y-axis is the stock’s top_ask_price and the x-axis is the timestamp of the stock. The continuous updates to the graph should be the result of continuous requests and responses to and from the server for the stock data.</li>
    <li>This ticket is done when the graph is also able to aggregate duplicated data retrieved from the server.</li>
</ul>