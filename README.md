# ACS 3320 - Project Redesign

## Before
![Landing Page](https://imgur.com/uGqmvtj.png#gh-dark-mode-only)
![Results Page](https://imgur.com/7tj82Cy.png#gh-dark-mode-only)
![Details Page](https://imgur.com/ODLfZ3V.png#gh-dark-mode-only)
![Log in Page](https://imgur.com/KZdiPQP.png#gh-dark-mode-only)


## After
![Landing Page](https://imgur.com/rak3BRL.png#gh-dark-mode-only)
![Results Page](https://imgur.com/f1KUPzk.png#gh-dark-mode-only)
![Details Page](https://imgur.com/a1738gY.png#gh-dark-mode-only)
![Login Page](https://imgur.com/gMkjBmo.png#gh-dark-mode-only)

## Reflection

### Goals
The goal here for me was to completely redo the css from a previous project. The previous project was very bare bones and needed a lot of work. I started by removing most of the css and started from scratch. The main goal was to make the design modern and clean. I wanted the ux to be clear and concise using pleasing colors, typography, and responsive design.

### Problems
I did run into a couple small problems when trying to get my background color to animate using css animations. I also had trouble getting my nav bar to be sticky 100% of the time, but was able to solve that issue with the help of Mitchell's advice and making the header position fixed. Another problem I had was the number of pages that needed to be revamped. The project needed to have all of the following pages completely redone: landing page, log-in page, sign-up page, results page, details page, and also the my-events page. There was a lot to do!

### Self Assessment
I think the results were pretty good! There are certainly some small details that could use more attention, but overall I think the new design was a big upgrade. I learned a ton! If I had more time I would like to go back and make the site for accessible and easy to navigate using a keyboard or screen reader. The project is relatively responsive, but again there are some details that I could spend more time on like including more media queries. Overall I learned a lot and think the outcome was pretty solid. A big upgrade from what I had previously.


## How to run locally

To run this code, start by cloning this repository to your computer. Then in a terminal, navigate to the project folder.

To install dependencies, run:

```
pip3 install -r requirements.txt
```

Then rename the `.env.example` file as `.env`:

```
cp .env.example .env
```

Then you can run the server:

```
python3 app.py
```
