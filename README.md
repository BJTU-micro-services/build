## :ledger: Index

- [About](#beginner-about)
- [Usage](#zap-usage)
- [Development](#wrench-development)
  - [Pre-Requisites](#notebook-pre-requisites)
  - [Developmen Environment](#nut_and_bolt-development-environment)
  - [Build](#hammer-build)  

##  :beginner: About

A cloud native microservice system for ticket booking.

## :zap: Usage

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

##  :wrench: Development

### :notebook: Pre-Requisites

- docker
- docker-compose

###  :nut_and_bolt: Development Environment

- `git clone --recursive git@github.com:BJTU-micro-services/build.git`

###  :hammer: Build

- `docker-compose up`
