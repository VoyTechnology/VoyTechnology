---
title: Future of Netsocs
date: "2018-03-15T18:14:00Z"
type: "blog"
---

Networking Societies. If you have been studying computer science in an
university, you might have been or heard of one. But are they still relevant
in today's world of instant communication and common internet access?

<!--more-->

On DCU Open Day a particular society got me interested. Redbrick. They had
servers, cool terminals and everything that a younger me would want. Who
doesn't like to look at htop of a 16-core server? I was hooked from that day,
knowing that if I get into the university I will join the society. And I did.
At the first EGM the webmaster moved to admin position, the slot was available,
so I went for it. Over the 4 years in college I was webmaster, admin, and
finally secretary for a few months. I know how they run from technical side
and administrative. As good as they look on CV, less and less people overall
seem to be interested in them.

In my opinion the main problems that netsocs face is their inability to progress
onwards. Redbrick exists for over 20 years now. Used to be the only email
server for all available on campus, and the main way of communication through
IRC. But now? We have too many mail boxes, Messenger, Viber, WhatsApp, Slack..
you name it. I guess the dilema is: should we let them die? Accept that they
were the things of the past? Or make them adapt and move onwards like the rest
of the society does.

I realise some of the problems might be Redbrick specific, but from what I can
see a few netsocs are essentially dead already, or about to die. And its sad.
But I believe here are a few steps and suggestions that societies can take to
ensure they live on:

## Focus on the student

Its a student society. Ran by students, for students. What are the technologies
used and companies would expect from students? The courses cover how to write
in language X, how to solve concurrency, or what data structure to use to
optimise it. Its great, but how good is your application if you have no way
of deploying it? We can't expect the colleges to teach you everything, but this
is a perfect opportunity for netsocs.

Looks like docker is the new hipster thing on the block, forget VMs. Your
application has to leave your dev machine somehow, show the students how to use
docker for that. Host the docker images, use the machines to do some work. Its
a perfect idea - students learn something, and there is a "physical" proof the
society is doing something.

The main services a society offers need to advance. As much as I personally
love IRC, it is awkward to use. There are other alternatives, such as
[matrix.org][1], which can live in harmony with IRC and connect to it. They
are much more user friendly to use than SSH+Weechat, or mobile Weechat and
proxy. All those walled gardens are taking people away from the open source
foundations that netsocs are build on - show that these are still viable and
good options.

## Show your workings

Day to day running of technical infrastructure is a black box to most. There
are many people interested in how specific aspects work. Maybe more will get
interested if they see how cool it is (and it is __cool__). As a past admin
myself, I had no idea how any of it worked. Thankfully my position as webmaster
allowed me to dive in a bit and see the server room, and how its running behind
the scenes. But it was still hard. I had (and still have) no clue how DNS zones
are configured, how to operate the switches. It was just a thing some admin
was good at, and that was because they had previous experience. I don't need
to configure DNS zones, I have CloudFlare for that. And yet admins are required
to know it. How are you supposed to if you have no infrastructure to run
personally and the only one you can is sealed off and invisible? Perhaps run a
small admin blog, showing what admins have been working on - moving servers,
running updates, or labelling cables.

Nearly everything should be open sourced. Configs, binaries, scripts. Of course
there are things that should remain private, however anything that does not,
show it. Some benefits include:

1. People who are thinking of running for admin can see what they need to learn.
2. People can chip in and help with a problem in their spare time.
3. You have a centralised, reviewed place to host your infrastructure.

This has been a big focus of Redbrick recently - a lot has been done, but even
more is left to do. While website is now open, admin stuff still remains a
mystery.

## Company Contacts

Get companies in. Everybody wants the same thing. Students want jobs, companies
want talent. Let them do a talk about a cool thing they
are working on. Let students know they are open for interns, or are looking
for full time hires. Loads of associates are working in companies big and small,
they all have their own unique problems, which may or may not be of interest
to some. There should be at least one company a event a week, maybe two.

## Cooperate with other societies

In case of DCU, most society websites are hosted by Redbrick. They have people
who are not tech savvy, and there are a lot of things which apply from computer
world in "the real world". Redbrick is the only society to take signups using
a barcode scanner. I was really impressed by it when I joined. Why not extend
the ability to other societies\*? Use NFC in the student card or also scan the
barcode. Find out what would help other societies, with managing their users,
weekly emails, or general communication. How about having a `#society_name`
channel in IRC/Matrix/whatever?

\**Terms and Conditions apply. Its handing personal student data so there
probably would have to be an oversight from college.*

## Plan Ahead

Committees change often. People stay for duration of their college, some only
stay one term, some quit half way through. Having a long time plan, and seeing
the direction the society is heading would help to better align goals. Have an
official way to allow members propose ideas. Its fine if if only some (or none)
of the points on the plan came into existence. Having a written down plan also
preserves the ideas and reasons (possibly letting older committee say "told you
so").

I really hope this article isn't insulting anybody. I was in committee myself,
and I wish I could have done some of the points, so I take the blame too.
I hope this is helpful to any existing or future committee planning to make
their Netsoc better, or at least keeping it alive.

[1]: https://matrix.org
