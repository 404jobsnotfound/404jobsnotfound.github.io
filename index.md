<img src="docs/clublogo.png" width="250" height="250" alt="Club Pub Logo" title="Club Pub Logo">
# 404: Jobs Not Found

## Table of Contents
* [Overview](#overview)
    * [Goals](#goals)
* [Team Contract](#team-contract)
    * [Live Link](#live-link)
    * [PDF Link](#pdf-link)
* [Deployment](#deployment)
* [Images](#images)
* [Milestones](#milestones)
* [User Guide](#user-guide)
* [Developer Guide](#developer-guide)
* [Community Feedback](#comunity-feedback)
* [Contact Us](#contact-us)

### Overview

The Club Pub is a centralized, interactive platform designed to help students at UH Manoa discover, explore, and engage with a wide variety of student clubs and organizations—both official and unofficial. With over 200 Registered Independent Organizations and many more student-led groups, the challenge has been to create an easy-to-navigate, comprehensive directory that allows students to learn about clubs, what they do, and how to get involved. The Club Pub aims to solve this problem by providing a user-friendly and dynamic hub for all student organizations at UH Manoa.

## Goals

* To bring students together across campus
* Offer an all-in-one application to browse and join clubs
* Partner with campus clubs to provide an easy application option
* Bring more attention to smaller clubs

## Team Contract
The team has agreed upon these terms. Violation of set terms can and will result in disciplinary action and/or dismissal from the project. The contract has been electronically signed by each team member and is binding.

### Live Link
* [404 Contract](https://docs.google.com/document/d/1TxXB5bdOpOYseks1Diq53jgWq90syPOHFUVGKT9IJ6M/edit?usp=sharing)

### PDF Link
* [contract.pdf](/docs/Team Bonding.pdf)

## Deployment
Click [here](https://the-club-pub-git-test1-patricks-projects-491ced00.vercel.app/?_vercel_share=kx7zbHtZDkfMgfq28ZHsXK136z98NvUM) to access our application deployed using Vercel.

## Images
![Landing Page](docs/landingPage.png)
![Welcome Screen](docs/welcome.png)
![Browse Clubs](docs/browseClub.png)

## Milestones
* [Issues for Milestone 1](https://github.com/orgs/404jobsnotfound/projects/1)
* [Issues for Milestone 2](https://github.com/orgs/404jobsnotfound/projects/2)
* [Issues for Milestone 3](https://github.com/orgs/404jobsnotfound/projects/5)

## User Guide
1. Access the site by clicking the link in [Deployment](#deployment), which should take you to the deployed Vercel app
2. Log in to your account, or sign up for an account if you don't have one
3. Explore the Club Pub!

### For Users
All users have access to the following permissions:
- Browse all available clubs
- Search clubs according to interest areas
- View details about specific clubs

### For Club Admins
As a club admin, you gain access to the following permissions:
- Create a new club
- Edit club details, including name, description, and setting other admins
<br /><img src="docs/addClub.png" width="250" height="300" alt="Add club option" title="Add Club Screen" />

### For Site Admins
As a site admin, you gain access to the following permissions:
- Option to delete any club in edit menu
<br /><img src="docs/deleteClub.png" width="260" height="250" alt="Delete club option" title="Delete Club option when editing club details" />

## Developer Guide
Viewing the Site
1. Go to the [project respository](https://github.com/404jobsnotfound/the-club-pub) and clone the respository. 
2. Open the terminal and use `npm install` to install all dependencies.
3. Use `npm run dev` to view the site locally at http://localhost:3000

Modifying Data
1. To initialize the database for the site, first start a new Postgres database.
2. Copy the `sample.env` file and create a new file `.env`.
3. In the `.env` file, modify the `DATABASE_URL` variable such that `user` is the database username, `password` is the database password, and `mydb` is the name of your database.
4. Run `npx prisma migrate dev` to create tables in the database.
5. Run `npx prisma db seed` to populate the database with sample data.

## Comunity Feedback
In order to ensure our site is user-friendly, we gathered thoughts feedback from members of our community. 

Most of them liked the usability of the site, specifically the ease of use to regular site users. A few people noted that the button to delete a club was hard to find because you had to click on the Admin button in the header and then click the edit club button to see the option. 

Some people also mentioned the long loading times between pages, thinking that somehow broke the site when they wanted to browse clubs but nothing on the page had loaded for a few seconds. 

One member suggested for an option to add more images when adding a club to showcase club events, activities, and board members. 

## Contact Us

The Club Pub is designed, implemented, and maintained by 404jobsnotfound, a group comprised of <a href="https://yilamulafeier.github.io">Yilamu Lafeier</a>, <a href="https://andrelmiller.github.io/">Andre Miller</a>, <a href="https://andrewhe6.github.io">Andrew He</a>, <a href="https://patrickariola.github.io">Patrick Ariola</a>, and <a href="https://hovomuradyan.github.io/portfolio/">Hovhannes Muradyan</a>
