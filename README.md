---
  tags: project, meta
  language: english, ruby
  resources: 2
---

# Web Development Project Mode Guideline

## Introduction and Objectives

The last few weeks of the Flatiron semester are called 'project mode.' You'll be building real applications. The goal of this period is to expose you to actual problems that arise when building and teach you how to manage a big project. The goal of the projects is not to launch a massively popular social network or startup, but rather, just to learn.

>Education is an admirable thing, but it is well to remember from time to time that nothing that is worth knowing can be taught.
>
> — Oscar Wilde

While we love teaching you all the things about programming, in the end, we're trying to build things, and that isn't something we believe can be taught, but rather, must be learned by trying and failing and exploring.

So make sure you are keeping your eye on learning, a constant balance between building and shipping and learning.

During project mode, our expectation of you is that you ship at least 2 small projects.

**TL;DR**
* Expose you to actual problems
* Learn to manage software projects
* Goal is to learn, not build a company
* Learn through building things
* Ship at least two small projects

## Working in Teams

During project mode we want you working in teams of 2 to 3 people. Do not work alone, that is absolutely not allowed. And do not work in teams bigger than 3, they are hard to manage and add a people layer of complexity to the project.

We believe that as professionals, you should be able to, in fact take pride in your ability to, work with anyone. Work with people more advanced and less advanced and figure out how to be productive in both situations. Work with people that share your interests and people with wildly diverse backgrounds and figure out how to leverage all perspectives.

So who you work with shouldn't matter, but it does. Try to pick people that share your goals of learning and your values as a developer, the pace and hours you want to keep and the technologies you want to learn, and the problem you are looking to solve. It should be fun.

**TL;DR**
* Teams of 2 - 3 only
* **Do not work alone!**
* Should be able to work with anyone
* Pick partners with varying backgrounds
* Work on your weaknesses
* Work with people interested in working on the same project
* Have fun

# Picking a Project

Building something usable is tremendously hard. There are a few things we've learned over the years about building.

1. Everything is harder than it sounds. You'd be surprised how quickly complexity grows. Be humble about your estimates and somewhat realistic about what you can accomplish.
2. Keep it simple! Seriously, embrace constraints. Make your project as small as possible while still capable of delivering the majority of the value. Maybe you don't need a User registration system that supports 10 external OAuth providers, maybe you don't need to allow them to reset their passwords (do you even have users complaining about this?), maybe exporting to PDF is enough and you don't need to support epub and kindle. Just keep it simple. 1 version of something is more than enough. Think Minimum Loveable Project.

Beginners have a tendency to choose very hard projects. Pick a project that you can imagine having a somewhat working version of after a day. Keep it simple and small.

**Check out this list of [project ideas](https://github.com/flatiron-school-curriculum/project-mode-ideas)**

And see past projects here:

- [Crowd Tangle](http://www.crowdtangle.com/map)
- [GameTable](http://gametable.co/)
- [Gitshoes](http://www.gitshoes.com/)
- [Kickammender](http://162.243.246.245/)
- [LocalList](http://localist.herokuapp.com/)
- [Looseleaf](http://looseleaf.me/)
- [MilkTrackr](http://www.milktrackr.com/)
- [Missql Command](http://missqlcommand.com/)
- [NBAStalk](http://162.243.240.32/)
- [OctoMaps](http://octomaps.com)
- [Pale Blue Dot](http://palebluedot.herokuapp.com/)
- [WhoWhatWhen](http://192.241.176.112/)
- [Wishgram](http://162.243.119.229/)

**TL;DR**
* Be humble about your estimates
* Keep it simple ( Minimum Lovable Product)
* Should have a working version after a day
* External APIs make projects more interesting
* Think about answering or automating a question

# Starting Your Project

* Install the Flatiron Rails Gem `gem install flatiron-rails`
  * Then Run `flatiron-rails new AppName`
* The template is just an empty rails project with basics like RSpec, Bootstrap and
  Google Analytics installed already.
* Setup external services (API's, etc.)
* Get a base layout done
* Deploy a homepage

# Planning and Working on Your Project

1. Iterate! Stay fast and small. Build things in small parts. You should be able to launch a new feature every day because you build in the smallest possible unit and are constantly driving toward deploying a new piece of code. Don't pile up requirements, look for shortcuts, look for ways of having a 'good enough' version of the feature and not all the bells and whistles.
2. Make videos. Every day you should make a short, less than 5 minute video that
demonstrates a feature you built today. The point of making the videos is to
keep you focused on delivering features, and prevent you from wasting time in the
wrong areas.
3. Dont' get bogged down by complexity. Focus on the the smallest unit of work,
and build up from there. Don't spend time planning
every detail of your project. Get an idea of what you want to build and start.
You shouldn't find yourself designing a schema with a dozen tables. You also
shouldn't find yourself mocking up all the pages of the app before you've written
a line of code.
4. Deploy! You should deploy something on the first day, and every day after that.

#####Frameworks and Huge gems
Don't use JS frameworks or big gems like:
* ActiveAdmin
* RefineryCMS
* Backbone
* Angular
* Ember

**TL;DR**
* Iterate!
* Launch a new feature every day
* Make it good enough, not perfect
* Make < 5 minute video every day to demonstrate a feature you built that day
* Deploy on day one

# Working with Your TAs
1. Work with one TA. Your project will get complex, so you'll be working
with the same TA until you're finished. This will make the TAs more familiar with
your project, and a lot more helpful.
2. Don't let yourself get stuck. Your TAs are here to help you. Use them when you
get stuck. You want to make consistent progress. Don't spend the day stuck on
something.
3. There will be a consistent, daily schedule of times when you and your TA will be able to work with one another for uninterrupted blocks of time.

**TL;DR**
* Work with one TA
* Don't get stuck
* Use your TA

# Daily Standups
Every morning meet with your group, stand up and have each person tell the group
what they worked on the previous day, what they had trouble with, and what they
are going to work on today. Keep it short and focused.

**TL;DR**
* Have a daily standup

# Retro
Every day between 5:30 and 6:00pm, four groups will give five minute recaps about their progress on their projects. These will be short and sweet, and keep us all on our toes.

**TL;DR**
* Retros at the end of every day

# Schedule During Project Mode
You'll have a lot of free time during project mode to work on your projects. Most
days, the schedule will look like this:

Time          | Objective
--------------|-----------------------------------
9:00  - 10:00 | Standups
10:00 - 12:00 | Working on projects
12:00 - 1:00  | Lunch
1:00  - 5:00  | Working on projects
5:00  - 5:30  | Prep for Retro
5:30  - 6:00  | Retro (4 groups, 5 minutes each)

## Resources
* [ThoughtBot Playbook](http://thoughtbot.com/) - [ThoughtBot Playbook](http://playbook.thoughtbot.com/)
* [The Twelve Factor App](http://12factor.net/) - [The Twelve Factor App](http://12factor.net/)
