## :ledger: Index

- [About](#beginner-about)
- [Usage](#zap-usage)
- [Development](#wrench-development)
  - [Pre-Requisites](#notebook-pre-requisites)
  - [Development Environment](#nut_and_bolt-development-environment)
  - [Build](#hammer-build)

##  :beginner: About

A cloud native microservice system for ticket booking.

## :zap: Usage

Access the API at: http://82.253.141.50/

##  :wrench: Development

### :notebook: Pre-Requisites

- docker
- docker-compose

###  :nut_and_bolt: Development Environment

`git clone --recursive git@github.com:BJTU-micro-services/build.git`

To update the submodules you need to use this command:

`git submodule foreach git pull origin master`

OR

```
# Change to the submodule directory
cd submodule_dir

# Checkout desired branch
git checkout master

# Update
git pull
```

###  :hammer: Build

- `docker-compose -f docker-compose-kafka.yml up -d`
- `docker-compose up`
