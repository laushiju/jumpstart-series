this project is for learning how to connect to MongoDB using compass GUI and URI

Also enter '$env:NODE_OPTIONS = "--openssl-legacy-provider"' in the cli in case of the 'Error: error:0308010C:digital envelope routines::unsupported'

Zoom in @ 50%
![github image](https://github.com/laushiju/jumpstart-series/blob/master/public/screenshots/view1.PNG)

# Jumpstart Series

This repository is part of the MongoDB [Jumpstart](https://www.youtube.com/playlist?list=PL4RCxklHWZ9v2lcat4oEVGQhZg6r4IQGV) series on YouTube. Each branch corresponds to an episode.

## Instructions

### Connect to your MongoDB Atlas Cluster

- Be sure to sign up for a [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register) account
- After cloning this repo, from the terminal run: `npm install`
- Rename `.env.local.example` to `.env.local`
- Enter your MONGODB_URI in `.env.local`
  - From your Atlas Dashboard under Databases, click "Connect"
    ![Step 1](/readme_img/1.png)
  - Then select "Connect your application"
    ![Step 2](/readme_img/2.png)
  - Now copy your connection string. This is the MONGODB_URI
    ![Step 3](/readme_img/3.png)
- Run `npm run dev`

## Questions?

Questions about this repo or how to use MongoDB Atlas? Ask them in the [MongoDB Community](https://community.mongodb.com).
