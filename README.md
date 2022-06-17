# Hosting a Full-Stack Application - Udagram

<h1> Hosting Link   </h1>

- http://udagram-storage.s3-website-us-east-1.amazonaws.com

<h1> CircleCI Link </h1>

[![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://app.circleci.com/pipelines/github/Abdelrhmansakr/udagram-deploy/1/workflows/8c81cab5-7e66-465b-be61-4ea316ba3559/jobs/4)

<h1>  setup </h1>
create a `.env` file in udagram-api:

- AWS_ACCESS_KEY_ID
- AWS_DEFAULT_REGION
- AWS_SECRET_ACCESS_KEY
- POSTGRES_HOST
- POSTGRES_USERNAME
- POSTGRES_PASSWORD
- POSTGRES_DB
- POSTGRES_PORT
- PORT
- JWT_SECRET
- URL

run your database if work local

run terminal :
- npm backend:install
- npm frontend:install
- eb deploy udagram-api-dev
- important your values env in aws 

url
- http://udagram-storage.s3-website-us-east-1.amazonaws.com/
    