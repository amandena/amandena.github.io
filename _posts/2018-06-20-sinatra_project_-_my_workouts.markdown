---
layout: post
title:      "Sinatra Project - My Workouts"
date:       2018-06-20 13:59:52 +0000
permalink:  sinatra_project_-_my_workouts
---


Creating my first application for the web was very exciting, especially since I could see it in real time with the shotgun gem. I decided to make a simple app that I could use to track my workouts since I workout 4-5 times per week, so it would be a useful resource for me. It could also provide some inspiration and accountability since users are able to view each others workouts that are posted.

Once I had my file structure laid out and ran all the migrations, I got cracking on the project. I started working on the user controller and views first, which I learned was probably not the best place to start. I say that because I used shotgun throughout the coding process, so after creating each route I would test to make sure that it worked like any programmer would. However, its kind of hard to test whether both the sign up and login routes work when you can't logout since that route doesn't exist yet. Its also difficult to imagine what the workouts themselves would look like without starting on the workouts controller or views. Until I had a more concrete setup, it was like I was working blindly at times but I made it through.

I would say that the validations were the most problematic to get working. From a tip from a study group that I attended, I was shown that validators could be added to the models themselves instead of using endless "if" statements in the controllers. I was thrilled about that idea. Just one simple line of code to replace 4-5, talk about lazy! What I didn't know at the time though was that those validators needed both a gem and module to work and that took some time to figure out. The time that I thought I was saving went out the window at that point. But after some research, I finally got it working and was much happier with the way my code looked because it was easier to understand at a glance. 

I am happy with the way my project turned out and am even happier that I was able to finish it in about two weeks. Much faster than the CLI project. I feel like I am that much closer to becoming a programmer now that this milestone has been reached. Rails, here I come!
