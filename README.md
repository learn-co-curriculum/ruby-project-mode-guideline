---
  tags: project, meta
  language: english, ruby
  resources: 2
---

# Web Development Project Mode Guideline

## Contents
|Section|
|-------|
|[Introduction and Objectives](#introduction-and-objectives)|
|[Working in Teams](#working-in-teams)|
|[Picking a Project](#picking-a-project)|
|[Starting Your Project](#starting-your-project)
|[Planning and Working on Your Project](#planning-and-working-on-your-project)
|[Working with Your TAs](#working-with-your-tas)|
|[Schedule During Project Mode](#schedule-during-project-mode)|
|[Resources](#resources)

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

During project mode you will be working in teams of 2 to 3 people. Do not work alone, that is absolutely not allowed.

We believe that as professionals, you should be able to, in fact take pride in your ability to, work with anyone. Work with people more advanced and less advanced and figure out how to be productive in both situations.

Project mode is a perfect time to get comfy with concepts you feel iffy about. If you're not a strong JavaScripter but your partners are, your first instinct might be for them to go ahead and write JavaScript while you watch passively. Resist this instinct! Instead, take on that JavaScript and let them take on other areas that they might feel less confident with.

Finally, while project mode may be less structured than earlier in the semester, it is nevertheless a time to learn. Have a sense of humor when a bug ghost comes back to haunt you, rejoice when you conquer it, and encourage not just your teammates, but also other teams. Remember to have fun.

**TL;DR**
* Should be able to work with anyone
* Work on your weaknesses
* Have fun

## Picking a Project

Building something usable is tremendously hard. There are a few things we've learned over the years about building.

1. Everything is harder than it sounds. You'd be surprised how quickly complexity grows. Be humble about your estimates and somewhat realistic about what you can accomplish.
2. Keep it simple! Seriously, embrace constraints. Make your project as small as possible while still capable of delivering the majority of the value. Maybe you don't need a User registration system that supports 10 external OAuth providers, maybe you don't need to allow them to reset their passwords (do you even have users complaining about this?), maybe exporting to PDF is enough and you don't need to support EPUB and Kindle. Just keep it simple. One version of something is more than enough. Think Minimum Lovable Product.

Beginners have a tendency to choose very hard projects. Pick a project that you can imagine having a somewhat working version of after a day. Keep it simple and small.

**Take a look at the next lesson for project ideas**

**TL;DR**
* Be humble about your estimates
* Keep it simple (Minimum Lovable Product)
* Should have a working version after a day
* External APIs make projects more interesting
* Think about answering or automating a question
* Keep in mind that Heroku allows for one free rake task through [their scheduler](https://devcenter.heroku.com/articles/scheduler). Make sure your project idea will not require multiple rake tasks or require a rake task that runs at an interval other than hourly, weekly, or monthly.

## Starting Your Project

* Install the Flatiron Rails Gem `gem install flatiron-rails`
  * Then Run `flatiron-rails new AppName`
  * If you'd like to enable Google Analytics, get a Google Analytics code and add it to `config/secrets.yml`.
  * Type `n` or `no` to every prompt. You can add Devise and all the other add-ons later.
  * Add `ruby '2.1.2'` or whatever Ruby version you'd like to use to the top of your Gemfile
  * To deploy to Heroku, you'll run `bin/setup [<app_name>]`, where `app_name` is optional. Then run `bin/deploy`.
  * For more information on the gem, cd in to a Rails app that it created and look at the file `STACK.md`
* The template is just an empty rails project with basics like RSpec, Bootstrap and
  Google Analytics installed already.
* Setup external services (API's, etc.)
* Get a base layout done
* Deploy a homepage

## Planning and Working on Your Project

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

##### Frameworks and Huge gems

Don't use JS frameworks like:
* Backbone
* Angular
* Ember

Or big gems like:
* ActiveAdmin
* RefineryCMS

**TL;DR**
* Iterate!
* Launch a new feature every day
* Make it good enough, not perfect
* Make 1 minute video every day to demonstrate a feature you built that day
* Deploy on day one
* Don't use huge JS frameworks or gems

## Working with Your TAs

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

## Schedule During Project Mode

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

### Daily Standups

Every morning meet with your group, stand up and have each person tell the group
what they worked on the previous day, what they had trouble with, and what they
are going to work on today. Keep it short and focused.

**TL;DR**
* Have a daily standup

### Retro

Every day between 5:30 and 6:00pm, four groups will give five minute recaps about their progress on their projects. These will be short and sweet, and keep us all on our toes.

**TL;DR**
* Retros at the end of every day

## Resources
* [ThoughtBot](http://thoughtbot.com/) - [ThoughtBot Playbook](http://playbook.thoughtbot.com/)
* [The Twelve Factor App](http://12factor.net/) - [The Twelve Factor App](http://12factor.net/)
