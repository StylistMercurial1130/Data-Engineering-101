
## 1.1 key responsibilities of a data engineering

the 6 key responsibilities of a data engineering are

1. Move data between systems
2. Managed data warehouses
3. Schedule, execute and Monitor data pipelines
4. Serve data to end users
5. Data strategy for the company
6. Deploy ML Models for production

> [!NOTE] 
> #### enabling data analytics
> 
> Now given a scenario where I am hired to to enable data analytics, I would start with data part of it. To enable data analytics, we must first have an idea of what data are we trying to analyse here and how do we got about getting it.
> 
> I would break down this task into 2 distinct parts
> 
> 1. Data collection
> 2. Data Storage 
> 
> >#### Data Collection
> >
> > The Main questions to answer here would be what data would I be collecting and from where, so the main requirements I would need to gather is what is the nature of this data ? is this is data from a rest api ? or is this data of some other format ? maybe from an iot sensor ?. These questions require investigation and active collaboration with my employer who wants to enable data analytics.
> > 
> > When the nature of the data is established, a clear understanding of where the data is coming from needs to established  if its a rest api then I must setup a proper system to communicate with this rest api and transform it into a format that is suitable to how I want to store it.
>
> >#### Data Storage
> >
> >For Data storage a few decisions would be need to made on how am I modelling the data that is going to be stored and where I am going to store this data. 
> >
> >This would involve setting up our very own data warehouse and modelling our data warehouse for loading our data and ensuing the quality of the data and efficiency of the data warehouse in terms of performance when querying the data. 
> 
> Once the investigation of the source and nature of the data and model of our storage, I would create a ETL pipeline to extract data from our source location, transform into suitable form and load it into our data warehouse. This data warehouse. can be queried from in a BI application to get data analytics.
