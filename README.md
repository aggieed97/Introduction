# Introduction

## April 24, 2021 Update

Nearly 18 months later.  Yikes!  Well, last I was here, I mentioned getting a job.  Unfortunately it was not in Data Analytics/Science.  It was going back to doing what I have been doing since 1998.  I needed the health insurance.  Since last August, I've been back to heavily applying to data analyst/scientist jobs, but with COVID having taken out scores of experienced professionals, the interviews have been pretty rare.  I've managed 3 interviews since January 1, 2021, but nothing really concrete has come out of them.  I'm still waiting for one company to open up a Data Science position they said would be open sometime in 2021.  I did an interview with the hiring manager's manager back in November that I thought went pretty well.  So I wait.

In the meantime, they started letting us use Streamlit at work to create Web Apps.  I've created three, so far, in the last couple of months with ideas for more.  Unfortunately can't share any of those publicly so I'm working to translate some of my older material for public consumption.  Anyway, hopefully it's not another 18 months before I update again.  I really need to start sharing projects publicly on here even if only 4 companies out of the several hundred I've applied to in the last three years have asked me for it.

## October 18, 2019 Update

Whoa!  It's been a long time.  I completed many projects, and I learned quite a bit on how to use GCP's AI Platform to spin up a VM that can run a whole bunch of different sports probability code I created.  I also did some more Drum Corps International predicting throughout the 2019 summer season that was fun.

And the big news:  I finally managed to get a full time job!  Yup!  More I can not say until I update my LinkedIn profile probably after the 1st of the year, but that was definitely the highlight of the last month or so.

## May 18, 2019 Update

I ended up nixing the daily MLB predictions for a little while.  I was able to attend my first game of the season a few weeks ago in Arlington to see the Astros pummel the Rangers, though.  That was fun!

While finishing up my taxes shortly after the last update, I procrastinated a bit by working on using FiveThirtyEight's NBA dataset to start making predictions on the NBA Playoffs.  A few weeks after that I used the Sports Reference API to run predictions on the NHL Playoffs.  I've become a regular (yet still amateur) sports prognosticator.

We're about a month away from the start of the 2019 Drum Corps International Summer tour.  Last August I used a very simple ARIMA model to make predictions on Championship Weekend.  You can visit my blog for more info on that from back then.  I took a quick look at the code that I wrote back then...and whew boy I was such a noob!! At the moment I'm thinking through how to make predictions for this summer.  The website I scraped last year only has data going back to 2014 so I might have to figure out how to scrape the DCI website or find another data source.

I also finally cracked how to use Triangular Distribution in Python!!  Only took me a few months.  It's not very intuitive...not like a normal or poisson distribution for sure.  I want to do a blog post on how to use it so hopefully I can get that going soon.  But first, my mid-term for the Supply Chain Design class I'm taking.

## April 12, 2019 Update

I ended up finishing in 103rd place in the Kaggle NCAA Men's competition this year.  That put me in the Top 12% which was a huge improvement from last year's competition.  I'm rather proud of that accomplishment, though!  As it turns out there weren't all that many upsets this year which may speak to the Selection Committee's job in picking the seeds.  I also used my predictions to put together a bracket for the one and only tournament pool I participate in with a good friend of mine.  He's been doing a pool for 16 years, and I've participated in 15 of them (missed out in 2017 because I forgot to submit in time).  This year was the closest I've come to winning.  The winner was based on a tie-breaker though which was determined by the number of total points scored in the Championship game.  Unfortunately, since the game went into overtime, I lost.  And actually my total points predicted was passed with about 2 minutes left in regulation for the game.

In other news, I started using FiveThirtyEight's MLB dataset to help make daily predictions on MLB games.  I was posting those on Twitter, but I've been a little bit disappointed that the model (as well as most other websites and Vegas-type sites) pretty much stick to between 40-60% win probabilities.  That, to me, is pretty darn boring.

## March 14, 2019 Update

Still been working on my College Basketball Predictions. We're less than a week away from the start of the 2019 NCAA Tournament, so I'm definitely excited about using my models for that.  This year I'm going to have a couple of different brackets with predictions.  The first will be based on the model I used last year with tweaks that I've made in the last year. The second will be based on the model I've been using for the last several weeks reporting out results via Twitter.  They are very different models.  Something I just recently thought of was trying to code out tournament simulations to determine winners.  Will see if I can get it done in less than 5 days with everything else going on.

I also recently scraped together Major League Baseball stats with the idea of doing daily predictions of baseball games throughout the 2019 season.  It will start out as a very rudimentary model, but like the basketball model, I'd like to add in more advanced statistics as time allows.

The other day I needed to test some SQL queries on some data I had.  I decided to use Google BigQuery to do that.  I looked up how to upload local files to play around with.  Even though it was something that was super simple, I may just do a blog post about it.  Especially given that my blog has not been updated in a long time.

## January 28, 2019 Update
Currently doing daily Men's College Basketball (Men's CBB) Predictions via Twitter (@danger009mouse) for Top 25 teams as well as local area (to me) teams like Texas, Texas A&M, and Baylor.  Just didn't make sense for me to do a blog post every day.  The predictions rely on data scraped daily.  Would be nice if I can figure out to create a table with predictions that dynamically changes say at 10 AM everyday.  That's something that I will certainly want to look into for the future.

Right now the CBB model is very simple and is currently not related in anyway to the models I had for last year's tournament.  I am currently looking to incorporate more variables, of course, as time goes on.

## December 30, 2018 Update
I haven't updated this particular repo in a couple of months, but that doesn't mean I haven't been working on projects.  I've spent the majority of the last few months working on NFL Fantasy Football Projections.  In the last month I've also started working on predicting who will win a football game based on various inputs.  You can read more about that and any other thoughts I have on various subjects at my website: https://salcorpenterprise.com

I do have several ideas on different projects I want to work on in the future.  Here are a few of those ideas in no particular order:

1.  Football Play-by-Play analysis - may end up putting this off until next summer
2.  Update WTI and Brent Crude Analysis based on Q4 data and project out through Q1 2019
3.  Update Avocado Price Analysis through end of 2018 - may be dependent on when that data is available
4.  Triangular Distribution Post - I'm taking a Supply Chain Analytics class from MIT on the eDX platform, and they introduced the concept of triangular distribution.  This was not something that was taught in my Data Science Bootcamp and not many people seem to be familiar with it in my circle.
5.  NCAA Basketball - All the football analysis, of course, is basically setting up my predictions for the NCAA Tournament in March...of course!
6.  Google Maps API - Been meaning to figure out how to use this and incorporate it into the basketball predictions
7.  Fitbit Data - I'd read a blog post on using Fitbit's API to access your data and analyze it, and I very much want to do the same with my data

That's a small handful of the projects that are currently on my wish list of things I'd like to accomplish in the next few weeks/months.
