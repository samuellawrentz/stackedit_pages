---


---

<h2 id="auth-frontend">auth-frontend</h2>
<ul>
<li>Vue JS</li>
<li>Vite</li>
<li>Yarn as package manager</li>
<li>Can we migrate to Bun? Yes</li>
<li>Was not able to move past <code>select-Integrations</code> screen</li>
</ul>
<h2 id="kamaji">kamaji</h2>
<ul>
<li>A pipeline for data</li>
<li>Is a service written in node</li>
<li>Built using tsc</li>
<li>Can be run as docker container</li>
<li>Functionality is to pull data from various sources and put it in the postgres db</li>
<li>Similar to our API integrations, but as a BE service</li>
</ul>
<h2 id="questions">Questions</h2>
<ol>
<li>How is FE connected to BE?
<ol>
<li>What API endpoints?</li>
<li>There is no login screen?
<ol start="3">
<li>Anyone can access?</li>
</ol>
</li>
</ol>
</li>
<li>How is historical data fetched?</li>
<li>How is live data fetched?</li>
<li>How is updates propagated?</li>
<li>What is FS and SSM Backend config</li>
<li>How are we streaming the data?</li>
<li>Why do we need knexJS, if we are just pouring data into the db from the sources?</li>
<li>What is the standard schema for data?
<ol>
<li>What tables do we have? Table names and column names</li>
<li>How many tables and for what?</li>
<li>How many DB?</li>
<li>Where can I see it? How to connect to table plus?</li>
</ol>
</li>
<li>How is random data from 3rd party APIs being mapped to the schema?</li>
<li>Does webhook come into picture?
<ol>
<li>For notifications? or for recieving incoming data?</li>
</ol>
</li>
<li>Why Postgres? If data is going to be huge, why not Elastic search?</li>
<li>Have to create a readme file, which will help other developers for onboarding.</li>
<li>Types, Interface and code is in same file, need to name it properly or move it to proper place
<ol>
<li>packages/kamaji/lib/IDestination.ts</li>
<li>Types, interfaces could’ve been in a separate folder, would make the folder more clean</li>
</ol>
</li>
</ol>
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>

