#snapshotalyzer-3000
Demo project to manage AWS EC2 instances snapshots

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty uses the configuration file created by the AWS cli e.g

`aws configure --profile shotty`

## Runnig

`pipenv run "python shotty/shotty.py <command> <subcommand> <--project=PROJECT>
"`

*command* is instances, volumes, snapshots
*subcommand* - depends on command
*project* is optional
