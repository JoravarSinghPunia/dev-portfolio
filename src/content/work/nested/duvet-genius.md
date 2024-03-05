---
title: Backend RESTful API
publishDate: 2020-03-04 00:00:00
img: /assets/image.jpg
img_alt: Thumbnail of repository
description: |
  Built for the purpose of accessing application data programmatically.
tags:
  - PSQL/Express
  - JEST
  - TDD
---

You can access the live version of this API [here](https://backend-news-api-rzxs.onrender.com/api),
or the source code (GitHub) [here](https://github.com/JoravarSinghPunia/BACKEND-NEWS-API). Please bare in mind
that the live version may take a while to load as it is hosted on Render, and loading times are decided by when the link was last opened.

The backend news API is a service built for the purpose of accessing application data programmatically. Modelled after real world backend services, such as Reddit, this api will deliver information to the front end architecture.
The project uses [PSQL](https://www.postgresql.org/) to setup the database of articles, and HTTP endpoints using [express](https://expressjs.com/). This is now live and being hosted on [ElephantSQL](https://www.elephantsql.com/) with deployment on [Render](https://render.com/).

This api was completed using Test Driven Development (TDD) principles, with use of both Jest and Supertest. Each endpoint was created with its own ticket, with frequent code reviews from Senior Software Engineers.
