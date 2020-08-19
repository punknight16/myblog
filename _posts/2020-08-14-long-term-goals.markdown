---
layout: "post"
title:  "Long Term Goals"
date:   2020-08-14 15:40:24 -0700
categories: general
---

I've been looking for a long-term blogging solution for a year now, and I think Jekyll might be the answer. The purpose of the long-term blogging solution is to create a repository for my thoughts and research that is somewhat searchable. I constantly have ideas for businesses or thoughts on a model of the way things work. I want to follow up on these thoughts and ideas, but I rarely do. 

## What I have already tried:

I started this journey with a Wordpress blog, but it fell out of use time and time again. Maintaining a Wordpress blog is just annoying because of needing to login to a server, and update plugins, and so on. I have also recently tried using Facebook, but that solution is actually pretty bad for searching. They only really provide a history of your posts, so there is no good way to link people to your previous ideas. The purpose of facebook isn't really to host a blog either, so the features will always be geared towards one-off posts that generate ephemeral interest from friends and family. The content that I want to generate doesn't line up well with the platform.

## Potential Pitfalls and Benefits of Jekyll

Jekyll is written in Ruby, and is closely tied to the Github ecosystem. I don't know Ruby that well, and Github has the potential to try to monetize because it was purchased by Microsoft. Another small problem is the language that you write blog posts in, markdown, is not that intuitive. However, that being said Jekyll is written as a blogging software for programmers. I overwhelmingly identify as a programmer first and foremost, and I think my content is for programmers, so this seems like a good community to become a part of. Additionally, Jekyll is open source and free. You can host on Github Pages or an AWS S3 bucket for practically free. I really want to setup a localhost Rasberry PI for dev to host my private Jekyll and then either an S3 bucket or Github pages for a prod deployment.

## Current Software Projects in need of Proposals

#### 1) Python Chess App

Lately, I have been wanting to develop a Python Chess App that uses machine learning in two ways. First, it uses it in the normal way to win games. Second, it asks questions of the user, as a way of understanding and helping the user understand their mistakes. So if you get forked, it will not know the definition of the word fork at first, but it will ask you about a certain position, and you will call it a fork, then it will tell you about forks in the future.

#### 2) Open Source ETL Tool

Another projects that has a deep interest to me is an open source ETL platform. I've broken down ETL into 7 parts:

a) Extract   
b) Load   
c) Storage   
d) Transform   
e) Visualization   
f) Schedule   
g) Dev Ops -  for version control and testing new models  
h) Prod Ops - for monitoring and triggering warnings when a scheduled job fails  

The idea here isn't necessarily to make something that's better than anything that currently exists, but I think I can make a framework that is extensible, so my "dumb" extractor can act as an interface/adapter for third party extractors like Fivetran for StitchData.

#### 3) COVID-19 

Another cool project is making an ops model for COVID-19. This would be similar to a system that China has already implemented. Tracking the R0 (communicability coefficient) of a disease, the mean travel distance of a person in an area, the population density of that area, and the current % of population infected in that area. Then telling people in that area the best practices to avoid getting sick to a certain degree of certainty, and running and visualizing models to prove how the virus will spread with changing coefficients.

Another project is just a review of calc 1, 2, 3, and various science and engineering classes that I took while at Georgia Tech. My skills for a bunch of these classes has greatly deteriorated over time. I guess the lack of use for knowledge results in it being lost, but I like the idea of having some key algorithms, principles, and experiments that I can use to inform other projects that I take on. For example, a simple cell battery is a fun experiment and using a multimeter (ohms, voltage, current) to show the output could be used to explain some electrical properties of materials. This past week, I talked about thermal runaway. I understood how it applied in semi-conductors, but I didn't know how it applied to batteries. A few principles and experimental setups would have been nice to use for reference.

#### 4) Review of Apache Projects which may lead to future Contrubutions

I've been dealing with a lot of tools put out by big companies recently. The tools that are put out by Google or Amazon are useful, but they are only free for certain use cases, and then they start to incur a cost. These are for profit companies that benefit from the free use of their ecosystem or they wouldn't offer it. Apache on the other hand is a completely free and open source community for putting out useful software.

I have been looking for a hacker/programmer/entrepreneur community that lines up with my values, and haven't had much success. Apache has some good hard tech, but the website and forums look pretty dated. I think just getting involved would be good for me, and hopefully prevent me from my current path of just building stuff that only interests me.

#### 5) Rebuild the 4 Microsoft Projects from scratch

Outlook (calendar, email), PowerPoint (presentations), Word (document editor), and Excel (spreadsheets, charts) are extremely powerful, but Microsoft has closed off its ecosystem so these programs aren't great with third party software. I think having the basics built out could be extremely useful, especially for building out more advance usecases on top. For example, pushing spreadsheet data to a database, and having the database data visualized with power point. Seems obvious, but it just isn't done automatically right now. Instead there are a bunch of third party tools built to pass data from one app to the next like Zapier.

Their could be a few tools built on top of these tools like a todo list app or a messenging app. Microsoft currently has Teams and One Note, but I think these tools makes more sense as plugins to a single overarching app. Like I can use messenger within my document or I can create a todo list in my calendar. It's just obvious right?

## Current Hard Tech Projects in need of Proposals

#### 1) Make a battery from scratch

Making a battery from scracth involves using a copper penny, aluminum foil,  vinegar and some paper towel to create a cell. I hope this battery can be used along with a magnet and paper clip to make a motor. Then maybe even build some sort of generator. This hard tech would be really easy to build and kind of fun for people to better understand the real world. 

#### 2) Go through some of my old Georgia Tech Textbooks 

I want to try to relearn some of the basic principles of math and science that I supposably learned 10 years ago. I made a toothpick bridge for three classes growing up, and not once did my teacher show us statics before hand. Deformation of materials is a major course in material science, and I am not able to use home materials to demonstrate the concepts I learned back then. I learned a lot of math involving matrices and eigen values, and all of that is mostly gone. I also would like to relearn the wave equation and how it can be used to explain quantum effects. I have a brother in law that is a physics professor, and I should be able to talk to him about his work.

#### 3) Arduino and Leap Motion projects

I bought some of this stuff thinking that I would at least get into a little bit of electrical engineering, but nothing every came out of it. Would love to be able to fabricate something useful in the future.

## Some possible paths moving forward

I have two ideas moving forward. One is to create a proposal for a project, and execute the project over the course of three months. Something along the lines of 1 month of research building a proposal, creating mockups, and writing out acceptance criteria, 1 month of building, and 1 month of testing/publishing before breaking down the project and starting on a new one.  

Another possible strategy is to create some sort of schedule similar to when I was in school. This would look like 4-6 classes scheduled throughout the week. A schedule like this could be useful for extremely longterm goals like learning a language or practicing a musical instrument. It kind of goes against the Silicon Valley way though. Most people here say something like, "Will it take you 10 years? Why can't you do it in 6 months?"