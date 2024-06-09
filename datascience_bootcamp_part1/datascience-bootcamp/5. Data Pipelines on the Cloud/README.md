## Project 5

- 📊 **5. Data Pipelines on the Cloud**: A project involving data engineering Python, SQL, GCP.
    
- 📑 **Case Study to Data Engineering**:

    Gans is a startup developing an e-scooter-sharing system. It aspires to operate in the most populous cities all around the world. In each city, the company will have hundreds of e-scooters parked in the streets and allow users to rent them by the minute.
    Gans has seen that its operational success depends on something more mundane: having its scooters parked where users need them.

Ideally, scooters get rearranged organically by having certain users moving from point A to point B, and then an even number of users moving from point B to point A. However, some elements create asymmetries. Here are some of them:

In hilly cities, users tend to use scooters to go uphill and then walk downhill.
In the morning, there is a general movement from residential neighbourhoods towards the city centre.
Whenever it starts raining, e-scooter usage decreases drastically.
Young tourists travelling with cheap flights are a big potential group of users, but they need to find scooters downtown or nearby touristic landmarks.
There are some actions that the company can perform to solve these asymmetries, namely:

Use a truck to move scooters around.
Create economic incentives for users to pick up or leave scooters in certain areas, as the image below shows.

Either way, the company wants to anticipate as much as possible scooter movements. Predictive modelling is certainly on the roadmap, but the first step is to collect more data, transform it and store it appropriately.

- 🎯 **Project Goal**:
    
 Since data is needed every day, in real-time and accessible by everyone in the company, the challenge is going to be to assemble and automate a data pipeline in the cloud.

#### Local pipeline
create a data pipeline locally, which involves collecting data from external sources, transforming it, and storing it in a SQL database. This will provide a foundation for building a scalable and automated pipeline in the cloud

#### Data Collection
1. Scrape data from the wikipedia.(webscraping library: beautifulsoup)

2. Collect data with APIs.

#### Data Storage
1. Create a database model.

2. Store data on a local MySQL instance.

#### Cloud pipeline
1. Set up a cloud database(Googloe Cloud Platform (GCP), to set up MySQL database)

#### Automate the pipeline
-used CloudWatch Events / EventBridge 

##### API's
APIs 1: Collect weather data (https://openweathermap.org/api)

APIs 2: Collect airports data (https://rapidapi.com/hub)

APIs 3: Collect flights data (https://rapidapi.com/aedbx-aedbx/api/aerodatabox)

### Medium article
the project is described in the following medium article ([Medium article](https://medium.com/@soniamayel/scooting-into-the-cloud-building-an-automated-data-pipeline-for-e-scooter-sharing-using-gcp-330a4eda2bd4))