# GSA-team-5 - Satisfaction Looker

## Hack Name
[PBS Tenant Satisfaction](http://open.gsa.gov/Digital-Innovation-Hackathon/)

[Satisfaction Looker mvp-0.1.0] (http://localhost:4000) - This is our v0.1.0 mvp and it is localhost so it will not run until you locally build the project.

## Primary Challenge
Are there relationships between tenant satisfaction and the cost of managing the tenant's building?  From this insight the goal is to help the government make better resourcing decisions that maximize value on each dollar spent and minimize waste.

## Secondary Challenge
Identifying other energy cost and consumption outliers.

## Team Vision
- Identify an initial algorithm that attempts to correlate various cost metrics to the various tenant satisfaction ratings.
- Identify the target users of the application to have a more personalized design approach.
- The team believes there is not a single view that answers the primary challenge succinctly (at least not known) so we want to build an intuitive user experience that allows the user to richly view the data and through various snapshots make better heuristical conclusion.

## Team
- Johnny Mohseni
- Brain DeRocher
- Stacy Surla
- Jolie Dobre
- Andrew Heekin
- John Cloutier

## Technologies
- [Jekyll](http://jekyllrb.com/) for quick static and live website
- GitHub
- Bootstrap integrated with Jekyll
- [xmind](http://www.xmind.net/) for creating a mind map to understand data better.
- [NVD3](http://nvd3.org/) and [D3](http://d3js.org/) visualization libraries
- [Python Pandas](http://pandas.pydata.org/) and [Tableau](http://www.tableau.com/) for data processing and preparation for visualization

## Installation
- clone this repo
- install Jekyll (`gem install jekyll`) - Ruby/RubyGem/Node dependencies
- start app (from your git directory type `jekyll serve`)
- view app in browser (`http://localhost:4000`)

## To-Do
- Need Granular data.  The high level measures are ok but will ultimately be misleading.
- More cost data tied to buildings.  Too many were missing
- Simply more data.  How easy is it to submit data and to make the data available for computer consumption.  Today the data is excel.
- Process to take take data and to convert to json for consumption and other transformations.
- Identify more 2-3 dimensional metrics to show data by building and region.
- Show more comparison overlays by building and region and other similar attributes.
- Personalization of the site for the Building and Regional Managers.  Seeing what matters to you eases the consumption of the information for you to act on.
