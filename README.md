# How to Talk About Apps/Projects You’ve Built

Okay, here comes the fun part.

If you’ve built an app or project that fulfills a personal need or collaborated with a team to build something cool then talking about it in an interview should be an enjoyable experience. This is where you get to express all the joys and frustrations you encountered while creating it. 

## What to Think About

There are dozens of ways to talk about your app/project, but at the end of this lab you’ll be able to cover these 5 major points:

1. What problem does the app or project solve? (or, what were you looking to identify/measure/predict through the project?)
2. How did you go about architecting it?
3. What are all of its features (including the ones your classmates built)?
4. What challenges did you overcome while building it?
5. Are there any plans for the future of the app/project (what would you add to it next)?

## You Got 99 Problems and You Just Solved One

At the end of the day, you are a problem solver. You noticed a need in the world and your app/project helped to address it. What was that need?

Maybe you needed to [find all the best restaurants in the area](https://www.yelp.com). Or you wanted to easily [buy and sell concert tickets](https://www.stubhub.com/). Or you just wanted to [rent out a free bedroom in your house](https://www.airbnb.com/).

App/project development is about solving problems and the most important question to answer is why you built it in the first place. This should be your starting point when it comes to discussing it in an interview.

Keep this limited to only 1-2 sentences. Don’t get yourself down a rabbit hole where you’re spending five minutes talking about a nightmare roommate experience. 

## Architecture

So we’ve  addressed the *why*. This section addresses the *how*. As in, how did you get this app/project off the ground? What were all the components you and your team used to bring your app/project to life?

**This is where you get technical**.

Software Engineering:

- Did you use Bootstrap for the front end? jQuery for a dynamic UI? Maybe Angular because you wanted a single page app?
- Did you use Node/Express or Rack/Rails as your framework?
- What database did you use? Postgres, Mongo, SQLite?
- How did deploy the app? Heroku? Meteor?

Data Science:

- What methods did you use to collect the necessary data?
- Did you clean/manipulate data with Python for analysis or other means?
- What shallow- and deep-learning models did you use/train for additional analysis? 
- Did you build a web dashboard, using Dash and Flask, to display data visualizations and patterns?


Remember the `Technical Experience/Applications Built` portion of your resume? You’ll want to summarize those bullet points with a high-level outline of the app/project without getting too fine-grain during this part of the conversation. That way, you leave room for questions when you ultimately dive deeper into all of its features.

## Features 

You’ve just covered the why and the how. Time for the **what**!

What can your app/project do? What makes it cool or unique? Be sure to elaborate on all the features that address your earlier problem statement but remember to keep your explanations simple and clear. Don’t get lost in the details if it doesn’t pertain to the conversation or directly answer the interviewer’s question.

#### Examples:

> Our app uses Nokogiri to scrape major news sites and aggregates the most popular titles.

> Our app connects to all the major social networking APIs like Twitter and Pinterest to create a holistic profile of each user.

> Our project utilizes Sephora’s user rating and reviews to predict a product’s popularity.

> Our project diagnoses chest X-rays with deep learning models to automate accurate medical diagnoses.

If you collaborated on a team project, make sure you fully understand what features your partners built. Interviewers won’t always know what components you were responsible for so you want to be prepared for everything.

> Quick tip: think about how you’ll speak about your app/project and how that differs from the bullet points written on your resume. Write down those differences!

## Obstacles

One of the greatest joys of app or project development is taking an idea and turning it into a reality. It is extremely satisfying when things work. It’s also downright frustrating when things don’t.

This is often the most interesting part of an interview. Interviewers, especially technical ones, will be curious to hear about the problems you encountered and how you solved them.

#### Examples

> Everything was going fine until we tried to load a 2GB file into the database. That’s when we realized SQLite couldn't handle the size and we had to migrate to AWS S3.

> We connected to Instagram’s API but noticed our app started freezing whenever we would listen for hashtag updates. Then we realized we were tracking worldwide hashtags and our app was getting pummeled with hundreds of messages each second. Thin, the default server for Rails is single-threaded and wasn’t able to handle the load. Thankfully we switched to Unicorn and overcame the concurrency issues.

A few things to remember here:
- Make sure to talk about actual **solutions**. Don’t bring up any hacks/workarounds that you know will ultimately break later. Make sure your solutions were thoughtful and airtight.
- Be mindful of your tone during the conversation. Don’t come across as whiny or as a complainer. Instead, let your passion shine when you describe how fantastic it was to find a working solution to your problem.

## Future Plans?

Another joy to building apps or projects is that the work is never done. You can always do more! Maybe you addressed your original need but quickly realized that there were a dozen new possibilities. 

Facebook started as a profile page for college students. Now you can send instant messages, have group chats, coordinate events, and a million more things.

Google Maps started with simply finding the best directions. Now we have traffic patterns, accident reports, cop car sightings, etc.

What else can you add to your app or project?

## End Result

You now have a framework for talking about your apps/projects during interviews. If you can cover the five points listed in the objective then you can essentially discuss the full cycle of project development - from ideation to completion. This is relevant because this is the cycle of professional project development:

    Idea -> Design -> Implement -> Test -> Iterate
    
## Next Steps

Take some time to reflect on the last application or project you built. Ask yourself the questions posed earlier:

- What problem does the app or project solve? (or what does it measure/identify?)
- How did you go about architecting it?
- What are all of its features (including the ones your classmates built)?
- What challenges did you overcome while building it?
- Are there any plans for the future of the app or project (what would you add to it next)?

If you worked on a team project, interview your partners for the answers to “What are all of its features?”. Listen to how they describe the app/project and work together to sharpen your responses. Make sure to go over these responses with your Career Coach.
