# Assist Health – Infrastructure Repository

This repository contains ONLY infrastructure configuration.

## What is included
- docker-compose files
- nginx reverse proxy configuration
- domain routing setup

## What is NOT included
- Application source code
- CI/CD workflows
- Secrets or environment files

## How this repo is used
- This repo is cloned ONCE to:
  /home/ec2-user/assist-health/

- Application repositories deploy their code into folders
  beside these files using GitHub Actions.

## Deployment philosophy
- Application repos change frequently
- Infrastructure changes rarely
- Infrastructure updates are manual and reviewed
