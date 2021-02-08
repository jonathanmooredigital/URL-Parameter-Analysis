<h1>URL Parameter Analysis</h1>

<h2>About</h2>

<p>Made by <a href="https://jonathanmoore.digital/">Jonathan Moore</a>. Get in touch via <a href="https://twitter.com/nathanless">Twitter</a> if you have any questions.</p>

<h2>Description</h2>

<p>This is a sample workbook to give you some ideas on how to analyse URL parameters.</p>

<h2>Use Cases</h2>
<p>These are just a couple of examples:</p>

<ul>
	<li>Understanding in more detail the types of URL parameters that are present in your data</li>
	<li>Finding URL parameters to remove from datasets, to make it easy to see the wood from the trees</li>
	<li>For expample Google Analytics (GA)</li>
	<ul>
		<li>GA has a table limit of 50,000 rows</li>
		<li>And for some reason fbclid is never excluded from reports</li>
	</ul>
	<li>Identifing UTM campgain tracking parameters in internal links</li>
	<ul>
		<li>This screws up GA, becuase it creates a new session :(</li>
	</ul>
	<li>Spot checking parameters in large datasets</li>
	<li>Good luck doing this in Excel or Google Sheets</li>
</ul>
