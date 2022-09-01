# OPEN SOCIETY
<!-- ## **-- A Public/Private Sector Observability Platform --** -->
<!-- Table of Contents (This shit's gonna be long until it's organized and put into different folders... if that's needed. -->
*\*This page is a major, major work in progress. If you have any thoughts or questions, chances are you know me very well, so just reach out. If not, fine the nearest konk shell and blow.*

## About
It's essentially a semantic search engine and research tool for massive amounts of otherwise silo'd and heterogeneous data aimed at public and private sector domains. More on this below. 

## Requirements
### User Requirements Specification
#### User Archetypes
- Private Citizen
  - Citizen Journalist
  - Investigative Journalist
  - Data Scientist
  - Data Engineer
  - Data Professional
  - Organization
#### User Stories
##### As a _ user... 
<!--- https://docs.google.com/document/d/1fNbXKb1EVygJ3O6lIzXXfS8r12xxaPbSys4P-IbUlcc/edit -- for an old scratch list --->
<!--- would like to keep these lines from wrapping for readability. Not a priority at the moment, but something to think about. --->
- I want to know what company owns a given company and which companies a given company owns. 
- I want to learn more about the corporate network of private prison systems. 
- I would like to search through public and corporate ongoings spanning specifically in the time of a given "news cycle". 
- I want to be able to collaborate on group efforts to discover and uncover data. 
- I want to be able to create a data sandbox for the purposes of teaching, sharing it among students. 
- I want to be able to create a data sandbox for the purposes of supporting an article I am writing. 
- I want to be able to create a data sandbox and embed it, or a visualization, linking back to reproducible data, into an article. 
- I want to feed an article or paper into the platform and have a starter graph full of relevant keys, tokens, and words generated.
- I want to be able to check the lineage of all data to its source, whether primary or not. 
- I want to be able to look at the actions taken on someones shared sandbox. 
- I would like to export RDF data for my own purposes. 
- I would like to learn more about corporate grouping infrastructures. 

## Tech & Companies
- TerminusDB
- Cayley
- Akutan
- DuckDB

<!-- 
## Background
Data monopolies, big tech tools for specialists and for large institutions. Time to better educate people on big tech. Allows for proofing and supporting articles through embedding. 
-->

<!-- 
## Features
- Can feed in an article you want proofed.. Hopefully you get something out of it? 
  - Proofing can go fetch sited articles... or try?

## General ETL
Data provider -tabular-data-> RDF Mapping -> Bunch of other stuff -> Presentation and Query Layer

## General Questions
### Why Reinvent the Wheel?
- 

### Compliance

## Code Base

### Main Ideas

### React vs not-React
### Requirements
- DHT for inferred RDF updates and commits. 

### Why Go?
- Simple, fast, accessible. Easy for open source community to open any part of the code base and understand what's going on.

### Misc

## Research:

## Impl
### DB
**Overview**. In general, two modules exist outside the
database engine to handle RDF data and queries: (1) an RDF
import module, and (2) an RDF query module. Our proposed
data-centric schema creation technique exists inside the RDF
import module. The schema creation process takes as input an
RDF data set. The output of our technique is a schema (i.e., a
set of relational tables) used to store the imported RDF data
in the underlying DBMS.  
**Problem Definition**. Given a data set of RDF triples,
generate a relational table schema that achieves the following
criteria. (1) Maximize the likelihood that queries will access
properties in the same table without causing a join and
(2) Minimize the amount of unnecessary data processing by
reducing extra data storage (e.g., null storage).  

#### KV Stores
- Badger
- Bolt
- BitCask
- Pebble

- gStore vs Jena
-->

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
  
## [Core](#core)
#### [1. Docs](github.com/OpenSocietyPlatform/docs)  
#### [2. Resources](github.com/OpenSocietyPlatform/resources)
#### [3. External Clients](github.com/OpenSocietyPlatform/resources)
  
## [Tools](#tools)
#### [Lemon](github.com/OpenSocietyPlatform/lemon)
#### [Snafu](github.com/OpenSocietyPlatform/snafu)
#### [SvelteGraph](github.com/OpenSocietyPlatform/sveltegraph)
  
## [Libraries](#libraries)
#### [go-httpclient](github.com/OpenSocietyPlatform/go-httpclient)
#### [go-alog](github.com/OpenSocietyPlatform/go-alog)
