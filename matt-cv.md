# Matthew Bridges

## Contact Details

|          |                               |          |                                                                         |
| -------- | ----------------------------- | -------- | ----------------------------------------------------------------------- |
| Phone    | (+44) 7428124982              | Github   | [github.com/itsindigo](https://github.com/itsindigo)                    |
| Email    | mattbridgesbusiness@gmail.com | LinkedIn | [linkedin.com/matthew-bridges](https://linkedin.com/in/matthew-bridges) |
| Location | London                        |

## About

Software Engineer with ~5 years experience in the industry.

I've worked on products in Startups, Digital Agencies, and currently in the Energy sector where I'm working in Bulb's Smart Meter Installations team.

I'm a pragmatist, I always want to bring a positive attitude to the task at hand, and I love to speak up and drive ideas forward.

My aim as I progress through my career is to be a well-rounded senior technologist. To me that means broadening my knowledge with technologies I don't yet understand, being attentive to the ways in which I can help my team do better, and using my past experiences to inform a set of guiding principles that will help me build great products.

## Experience

### Bulb - March 2020 - Present

#### About

At Bulb I work in the Smart Installations team, our mission is to upgrade the nation's energy infrastructure through the installation of SMETS2 smart meters in order to support the next generation of Smart Homes.

#### Key Technologies

- Typescript, NodeJS (Koa, Highland for streaming, Knex), React, Jest.
- Python (Flask, Pydantic, Pandas, Apache Airflow, SQLAlchemy, PyTest).
- GCP (GCS, Pub/Sub, BigQuery, IAM).
- K8S (Deployments, Services, CronJobs, ConfigMaps).
- Terraform, Datadog, Sentry.
- Relational Databases (Postgres, MySQL).
- CircleCI, Github, Twilio, Mailchimp, Firebase.

#### Key Projects

_The Campaign Machine_ - Core contributor to design and implementations of architecture and features. _The Campaign Machine_ is responsible for scheduling and sending marketing campaigns to 1.2 million members, incentivising them to book a smart meter installation.

Over 18 months (during a pandemic) we were able to install 540,000 smart meters.

Features Included:

- Event Driven architecture to monitor change in member state over time.
- Support for 4 channels (Email, SMS, Letter, Push Notifications).
- Dynamic cool off periods to ensure timely intervals between communications.
- Opt out tracking.
- Machine learning components which clustered members into demographic buckets using open source data, allowing tailored communications.

_Comms Preferences Service_ - Designed a Microservice for centralised use within the company, the aim of the service was to decouple member's points of contact (email addresses, phone numbers etc) from their User IDs internal to the business. In this way members would be able to opt in or out of communications across multiple accounts or properties, and this information could be tracked from a single database.

Features Included:

- A customer could opt in or out of a group of communications (a campaign for example), including or excluding themselves via a contact address.
- Changes in subscription status relayed via Pub/Sub for consumption by other services.
- A query API that could be used to determine a member's subscription status to a given list.
- A single source of audit for GDPR queries.

<!-- Spacers to split PDF over two pages -->
<br>
<br>
<br>
<br>
<br>
<br>

### Hostmaker - July 2018 - Feb 2020

#### About

Hostmaker was a Series-B startup offering home management-as-a-service for Hosts on platforms such as Airbnb. During my time at Hostmaker I worked in the Guest Experience arm of the business, building services that managed communications between Hostmaker and Guests from the point of enquiry to the end of their stay.

#### Key Technologies

- NodeJS (Express, Sequelize), React, Mocha, Chai.
- AWS (SQS, S3, Rekognition, SES, EC2).
- NewRelic, Splunk
- CircleCI, Github, Mailchimp, Zendesk.

#### Key Projects

_Guest App_ - A Progressive Web App (PWA) that Guests could use to view their booking details and property information during their stay, we used at the time leading edge Service Worker features in order to cache member's booking details so that the app could be used without an internet connection.

Features Included:

- Use of service worker APIs to cache HTTP requests.
- User Identity Checker - Prior to arrival Guests were required to take a selfie, and a photo of their passport. We then validated the authenticity of the images using Amazon's Rekognition API. In doing this Hostmaker's exposure to misbehaving or fraudulent guests was reduced.

### Farm Digital - Jun 2016 - Jul 2018

#### About

Farm Digital (Since renamed to Giant Digital) is a digital agency targeting clients in the Third Sector. I joined Farm as a Junior Developer, helping them to deliver projects for a number of clients, operating within deadlines, and delivering features inline with pre-agreed specifications.

#### Key Technologies

- Python (Django, DjangoCRM), AngularJS.
- AWS (SES, Elastic Beanstalk, S3).
- Bitbucket.

## Education

### Makers Academy - Jan 2016 - April 2016

Attended Makers Academy Web Development Bootcamp where I wrote my first lines of code, I initially programmed in Ruby, learnt core programming principles such as TDD, SOLID, pair programming and Agile practices.
