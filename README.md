<p align="center">
<a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience" target="_blank">
<img src="https://insidesherpa-assets.s3-ap-southeast-2.amazonaws.com/icons/jpmorgan/github+repo+images/jpmc+github+img.png">
	</a>
</p>
<img src="https://imgur.com/ezovmfy.png" />
<p align="center"> 
	<b><a href="#task">Task Overview</a></b>
	|
	<b><a href="#installation">Installation Instructions</a></b>
	| 
	<b><a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/88AisH7iuw3L5N5ig" target="_blank">Link to Module 2</a></b>

<h1> Introduction</h1> 
<b> Experience Technology at JP Morgan Chase </b>
<p>Try out what real work is like in the technology team JP Morgan Chase. Fast track to the tech team with your work.</p>

<hd id="task">How to Run the Finished App</h2>

`npm start` within the root directory. 
`python3 datafeed/server3.py` within another bash profile in the root directory. 

Navigate to your browser. 

To get the results above, select the following options: 
<img src="https://imgur.com/OjYXk4f.png" />

Then you will see the following graph with the two stocks mapped out: 
<img src="https://imgur.com/ezovmfy.png" />

<h2 id="task"> Module 2 Task Overview </h2>
Implemented JP Morgan Chase’s Perspective open source code in preparation for data visualization</p>
<p> 
	<b>Aim:</b>Took an incomplete setup of Perspective, i.e. a graph that updates manually, and made it work with the code from Task 1 such that it now updates automatically by continuously requesting from the server application</p>

<ol>	<li>[goal-a] In the client application, observe that when new data feed is retrieved whenever you click the 'Start Streaming Data' button, the previous entry is re-entered into the table. Update the application so that the table does not have duplicated entries</li>
	<li>[goal-b] We also want the react app to keep continuosly requesting data from the python server. Changed the application to continuously query the datafeed every 10ms when the 'Start Streaming' is clicked.</li>
	<li>[goal-c] Currently, the Perspective element only shows the data in table view after the data loads. Add Perspective configurations so that when the data is loaded, it shows the historical data of ask_price ABC in the Y line chart.</li>
	<li>Upload a git patch file as the submission to this task</li>	
</ol>

If you encounter an issue with `datautil.parser`, run this command: 

	pip install python-dateutil

If you don't have pip, you can install it from: https://pip.pypa.io/en/stable/installing/

Run <code>npm install && npm start</code> to start the React application.

It's okay to have audit warnings when installing/running the app.

If you don't have `npm` (although you should if you followed the set up / installation part), you can install the recommended version alongside NodeJS from: https://nodejs.org/en/

The recommended version are node v11.0.0 and npm v6.4.1

Open http://localhost:3000 to view the app in the browser. The page will reload if you make edits.
