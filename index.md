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
Click [here](https://the-club-pub.vercel.app/) to access our application deployed using Vercel.

## Images
![Landing Page](docs/landingPage.png)

## Milestones
* [Issues for Milestone 1](https://github.com/orgs/404jobsnotfound/projects/1)
* [Issues for Milestone 2](https://github.com/orgs/404jobsnotfound/projects/2)
* [Issues for Milestone 3](https://github.com/orgs/404jobsnotfound/projects/5)

## User Guide
*Coming soon*

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

## Contact Us

The Club Pub is designed, implemented, and maintained by 404jobsnotfound, a group comprised of <a href="https://yilamulafeier.github.io">Yilamu Lafeier</a>, <a href="https://andrelmiller.github.io/">Andre Miller</a>, <a href="https://andrewhe6.github.io">Andrew He</a>, <a href="https://patrickariola.github.io">Patrick Ariola</a>, and <a href="https://hovomuradyan.github.io/portfolio/">Hovhannes Muradyan</a>
