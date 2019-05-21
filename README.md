<h1>Overview</h1>
Each script named state_issues_year_2019_ followed by the state abbreviation creates a .csv file of the number of digitized issues available in Chronicling America, the Library of Congress’ database of historic American newspapers, for each year digitized content from state partners is available.  Please visit https://chroniclingamerica.loc.gov/about/api/  for background information about the various views of data available from Chronicling America. The combine script will combine all the files in a directory into one .csv file.

<h1>Output</h1>
<b>state_issues_year_2019_DC.py or other files with state/territory abbreviations</b>
The output from this script is one .csv file named ‘District of Columbia_total.csv’. Each row in the .csv contains the state name, year, and number of issues available in Chronicling America.

<b>state_issues_year_2019_NOSTATE</b>
Use find and replace for "STATE_NAME" with the state or territory name you want the script run for. The output from this script is one .csv file named ‘STATE_NAME_total.csv’. Each row in the .csv contains the state name, year, and number of issues available in Chronicling America.

<h1>Dependencies</h1>
To run this script, you'll need to have Python 3 installed. You will also need access to a command line interface such as Terminal on OS X, Anaconda on Windows, or other.

<h1>Instructions</h1>
Save the state_issues_year_2019_ followed by the state abbreviation file to a folder where you want the results file saved.  Using the command line interface, navigate to the folder.

Run the script by typing: python state_issues_year_2019_ followed by the state abbreviation
</br>
Ex: python state_issues_year_2019_DC.py


<h1>Customizations</h1>
The scripts can be changed to run for any state. The template file is state_issues_year_2019_NOSTATE.py. To change the states issues being counted, use find for "NO STATE" and replace for the state or territory name you would like the script run on.  There is an issue count script for each state and territory available in Chronicling America as of May 2019. As additional content from new state partners is added to Chronicling America, the state_issues_year_2019_NOSTATE.py file can be updated to add the state information by using find "STATE_NAME" and replace with the state/territory you would like a count made for.

<h1>Implementation</h1>
We used this script to pull data from Chronicling America to create data visualizations available at http://www.loc.gov/ndnp/data-visualizations/. 

<h1>Next Steps</h1>
Please provide any feedback you may have by filing an issue.

If you use this script, please let us know at <a href="https://twitter.com/LC_Labs">LC Labs</a> or <a href="mailto:ndnptech@loc.gov">ndnptech@loc.gov</a>.

For additional information about accessing the Library of Congress’ collections programmatically please visit <a href="https://labs.loc.gov/lc-for-robots/">LC for Robots</a>.

<h1>Rights Statement</h1>
Script is free to use and reuse without restriction.
