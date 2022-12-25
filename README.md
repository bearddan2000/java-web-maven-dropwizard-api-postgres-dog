# java-web-maven-dropwizard-api-postgres-dog

## Description
A POC for dropwizard api using hibernate to connect to postgres.

## Tech stack
- java
- maven
  - dropwizard
  - hibernate
  - postgres drivers

## Docker stack
- maven:3-openjdk-17
- postgresql:alpine

## To run
`sudo ./install.sh -u`
[Endpoint](http://localhost/dogs)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Offical tutorial](rd.io/en/latest/manual/hibernate.DropWizardHibernateExample)
