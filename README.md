# Population-Modelling-Maps


## INSPIRATION

- Working as Research Assistants under professors with similar interests, my colleague and I noticed the large amount of overlap between our work. 
- We saw a huge potential among researchers to locate peers doing similar work and employing similar methodoligies and thus the opportunity to reuse work.


## ABOUT

- Today, many researchers are doing research of different types with overlapping methods. As such, there is a need to represent the field in a way that can help researchers locate and reuse similar work done by their peers.
- We narrow down on a dataset involving meta-data of authors and their papers in the field of population modeling and thus create a framework to help authors find related work and partners in the domain. 
- We create networks representing author-coauthor connections, networks showcasing their research methods and category and a dashboard to give an easy-to-view visual overview of the domain

## TOOLS USED
- Python
- PowerBI
- Microsoft Excel

## Data Visualization Framework

1. Insight Needs
  - Help researchers locate similar work and save time
  - Promote collaborations by building author connections
  - Provide interactivity

2. Stakeholder
  - Primarily, researchers in the field of population-based models
  - Industries and companies doing R&D in similar fields
  - Individuals getting into academia
  
3. Data Acquisition and Analysis
  - PDF Scraper using Python to extract research paper meta-data
  - Data cleaning (dates, words etc)
  - EDA to get summary statistics

4. Visualizations
  - Temporal
  - Geo-spatial
  - Topical
  - Network



## Category / Method based Relationship

- Here, we have created a Network Chart to show category/method based relationships
- The nodes represent the major keywords/categories which the research papers represent. 
- The size of the node tells the number of papers in that category while the edges to the smaller green nodes represent the authors associated with the category. 
- There is the option to filter and toggle as well and on hovering over the green nodes one can see the author name and their research papers.


    <img width="426" alt="Screenshot 2022-06-30 at 12 15 34 AM" src="https://user-images.githubusercontent.com/69982245/176598032-1aefa805-4887-402f-87cf-2c71131f000b.png">


## Author - Coauthor Relationship

- Here, we have created a Force Directed Network and a Tree View Network to highlight author-coauthor relationships
- The nodes represent the authors and are sized as per their number of contributions while the edges represent common connections between co-authors w.r.t methods used such as ‘optimization’, ‘simulation’ etc. 
- There is a filter which allows users to toggle and there is a tree view map at the bottom as well in order to convey further clarity


    <img width="426" alt="Screenshot 2022-06-30 at 12 16 24 AM" src="https://user-images.githubusercontent.com/69982245/176598115-1837f75d-0928-4ea1-98b6-5e54f197a5bc.png">


## Interactive Dashboard
- Here,  we have created an interactive dashboard on PowerBI
- The goal of the dashboard is to give an visual overview of the domain
- In order to do so we have used Funnel Charts, Donut Charts and Geospatial Maps
- The filters have a cascading effect. So if one selects bayesian models as the ‘method’, the filter for author adjusts accordingly to only show authors involved in that ‘method’
- As we apply filters, we also get meta-data about the author such as the title of his papers, the links to them and their abstracts


    <img width="292" alt="Screenshot 2022-06-30 at 12 17 35 AM" src="https://user-images.githubusercontent.com/69982245/176598262-dc672b25-16eb-41c7-8d61-fec489265419.png">



 
