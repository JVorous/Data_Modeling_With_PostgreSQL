# Data_Modeling_With_Postgres
<h1>Required libraries</h1>
<ul><li>pandas</li><li>psycopg2</li><li>sql_queries</li></ul>

<h1>Project</h1>
Create normalized fact and dimension tables in postgreSQL from json files to support a startup music streaming app, Sparkify
Goal is to create a relational database that can be queries for song-play analysis.

<h1>Steps</h1>
<ol>
  <li>Run create_tables.py -- will use statments from sql_queries.py to create appropriate tables</li>
  <li>run etl.py -- imports data from json files into sparkifydb for analysis</li>
</ol>

<h1>Notes</h1>
<ul>
  <li>Data files are expected to be in a /data/ subfolder</li>
  <li>Make appropriate changes to connection in order to run these files</li>
</ul>
