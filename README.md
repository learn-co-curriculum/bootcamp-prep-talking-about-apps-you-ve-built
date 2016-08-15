# How to Talk About Apps You’ve Built

Okay, here comes the fun part.

If you’ve built an app that fulfills a personal need or collaborated with a team to build something cool then talking about it in an interview should be an enjoyable experience. This is where you get to express all the joys and frustrations you encountered while creating your app. 

## What to Think About

There are dozens of ways to talk about your app but at the end of this lab, you’ll be able to cover these 5 major points:

1. What problem does the app solve?
2. How did you go about architecting it?
3. What are all of its features (including the ones your classmates built)?
4. What challenges did you overcome while building it?
5. Are there any plans for the future of the app (what would you add to it next)?

## You Got 99 Problems and You Just Solved One

At the end of the day, you are a problem solver. You noticed a need in the world and your app helped to address it. What was that need?

Maybe you needed to [find all the best restaurants in the area](https://www.yelp.com). Or you wanted to easily [buy and sell concert tickets](https://www.stubhub.com/). Or you just wanted to [rent out a free bedroom in your house](https://www.airbnb.com/).

App development is about solving problems and the most important question to answer is why you built the app in the first place. This should be your starting point when it comes to discussing your app in an interview.

Keep this limited to only 1-2 sentences. Don’t get yourself down a rabbit hole where you’re spending five minutes talking about a nightmare roommate experience. 

## Architecture

So we’ve  addressed the *why*. This section addresses the *how*. As in, how did you get this app off the ground? What were all the components you and your team used to bring your app to life?

**This is where you get technical**.

- Did you use Bootstrap for the front end? jQuery for a dynamic UI? Maybe Angular because you wanted a single page app?
- Did you use Node/Express or Rack/Rails as your framework?
- What database did you use? Postgres, Mongo, SQLite?
- How did deploy the app? Heroku? Meteor?

Remember the `Technical Experience/Applications Built` portion of your resume? You’ll want to summarize those bullet points with a high-level outline of the project without getting too fine-grain during this part of the conversation. That way, you leave room for questions when you ultimately dive deeper into all of your app’s features.

## Features 

You’ve just covered the why and the how. Time for the **what**!

What can your app do? What makes it cool or unique? Be sure to elaborate on all the features that address your earlier problem statement but remember to keep your explanations simple and clear. Don’t get lost in the details if it doesn’t pertain to the conversation or directly answer the interviewer’s question.

#### Examples:

> Our app uses Nokogiri to scrape major news sites and aggregates the most popular titles.

> Our app connects to all the major social networking APIs like Twitter and Pinterest to create a holistic profile of each user.

> Our app uses ActionMailer to send emails every time a user subscribes.

If you collaborated on a team project, make sure you fully understand what features your partners built. Interviewers won’t always know what components you were responsible for so you want to be prepared for everything.

> Quick tip: think about how you’ll speak about your app and how that differs from the bullet points written on your resume. Write down those differences!

## Obstacles

One of the greatest joys of app development is taking an idea and turning it into a reality. It is extremely satisfying when things work. It’s also downright frustrating when things don’t.

This is often the most interesting part of an interview. Interviewers, especially technical ones, will be curious to hear about the problems you encountered and how you solved them.

#### Examples

> Everything was going fine until we tried to load a 2GB file into the database. That’s when we realized SQLite couldn't handle the size and we had to migrate to AWS S3.

> We connected to Instagram’s API but noticed our app started freezing whenever we would listen for hashtag updates. Then we realized we were tracking worldwide hashtags and our app was getting pummeled with hundreds of messages each second. Thin, the default server for Rails is single-threaded and wasn’t able to handle the load. Thankfully we switched to Unicorn and overcame the concurrency issues.

A few things to remember here:
- Make sure to talk about actual **solutions**. Don’t bring up any hacks/workarounds that you know will ultimately break later. Make sure your solutions were thoughtful and airtight.
- Be mindful of your tone during the conversation. Don’t come across as whiny or as a complainer. Instead, let your passion shine when you describe how fantastic it was to find a working solution to your problem.

## Future Plans?

Another joy to building apps is that the work is never done. You can always do more! Maybe you addressed your original need but quickly realized that there were a dozen new possibilities. 

Facebook started as a profile page for college students. Now you can send instant messages, have group chats, coordinate events, and a million more things.

Google Maps started with simply finding the best directions. Now we have traffic patterns, accident reports, cop car sightings, etc.

What else can you add to your app?

## End Result

You now have a framework for talking about your app(s) during interviews. If you can cover the five points listed in the objective then you can essentially discuss the full cycle of software development - from ideation to completion. This is relevant because this is the cycle of professional software development:

    Idea -> Design -> Implement -> Test -> Iterate

<p class='util--hide'>View <a href='https://learn.co/lessons/bootcamp-prep-talking-about-apps-you-ve-built'>Bootcamp Prep: Talking About Apps You've Built </a> on Learn.co and start learning to code for free.</p>
