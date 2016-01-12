# Project Name: Rappo.rt

> Let Rappo.rt help you build meaninful relationships with your clients by keeping you up to date on news and events that your clients are interested in. Rappo.rt doubles as a one stop shop for content curated based on your clients interests, as well as a personal assistent that will push messages to you as events important to your client approach. 

## Team

  - __Product Owner__: Rebecca Yang
  - __Scrum Master__: Stephen Saunders
  - __Development Team Members__: Alan Fu, Shafique Rashid

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Tasks](#tasks)
1. [Team](#team)
1. [Contributing](#contributing)

## Usage

> Some usage instructions

Navigate to http://friend-ly.herokuapp.com/ to see a summary dashboard containing all of your clients!

Click on any client to drill down on the Client's information. You will see bio data as well as curated content based on the Client's interests. 

If you are not seeing a client that you would expect to see on the dashboard, you can click on the '+' sign at the bottom and fill out the subsequent form.

Moving forward you will recieve text notifications as events important to your client approach, such as birthdays or gameday for their favorite team.

Let Rappo.rt help you build a fruitful relationship with all your clients!


## Requirements

- Node 0.10.x
- Express 4.x
- Postgresql 9.1.x
- Angular 1.x

## Development

### Installing Dependencies

From within the root directory:

```sh
npm install
```

### Roadmap

View detailed project roadmap [here](/issues)


 - Broad roadmap
       - More API modules to inform client feed
       - Additional event driven push notifications based on client information via twilio - currently only sending messages upon adding a client
       - Allow salesperson to log notes on client
       - Sigunup/login Authentication for Sales users (currently app hardcodes to salesperson with id 1)
       - Responsive Design - potentially make work for mobile
       - Merge methods betweem user/client controller/model, as both interact with the same client table
       - Allow deletion of clients
       - Track interactions between client/sales
       - Allow salespeople to load in their own interests, and create algo to match salespeople to clients
       - Issues


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.