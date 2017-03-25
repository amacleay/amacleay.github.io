---
layout: post
title: What does it mean to be on a DevOps team?
---

I'm starting to read _The Practice of Cloud
System Administration: Volume 2_ for a book club at
work.  It is, roughly, about modern distributed
software design and operations.  I think it's a
great idea to get a bunch of people together to
read this book at my company now, and incidentally
it's great timing for me in particular.

We're working on a brand new project, and I have a
new team at work, which we consider the
"infrastructure" team within that project.  We
have two broad responsibilities.  First, we own
the "hub" components of our web site code, and
we're responsible for making sure that hub enables
the application teams to effectively develop
features.  Second, we are responsible for making
sure that we have working development, testing,
and production environments, and that our teams'
code and services get deployed to those
environments.  However, we're far from the only
ones concerned with the pipeline from development
to production: there are teams all over the
organization, from traditional sysadmins through
release engineering, concerned with the same exact
things -- we just happen to be the most closely
tied in with development of our particular new
application.  When we talk about what to put on
job postings for our new team, we often use the
term "DevOps Engineer", which has made me just a
bit uncomfortable -- what exactly does that mean?

Thankfully, the authors of _The Practice of System
Administration_ assure me, it means _absolutely
nothing_:

<blockquote>

  DevOps is a combination of culture and practices
  -- system administration, software developers,
  and web operations staff all contribute to the
  DevOps environment ... DevOps is not a job
  title; you cannot hire a "DevOp".

</blockquote>

Woops!

So this raises a reasonable question.  Why are we
talking about hiring a DevOps engineer when,
evidently, no such thing exists?  What is our team
doing if one of our principal responsibilities is
described not as a technology to build but "a
combination of culture and practices"?

To me it looks like there are a few plausible ways
to make this all make sense:

* I disagree with the authors of the book on
  whether DevOps is actually a role you can hire
  into;
* My role and that of my teammates is just a relic
  of an old-school anti-DevOps culture, and in
  fact by having a team dedicated to shouldering
  the responsibility of working with the
  infrastructure and operations teams we are
  dooming our whole project to a future of
  fragmented infrastructure, insufficient
  communication between development and
  operations, and software designed without the
  goals of resilience and scalability in mind; or
* We're just using the term "DevOps" in a nonsense
  way in our job description discussions.

I'm coming to think that there is a real danger of
this second possibility becoming the case.  We
need to recognize that there are risks and
drawbacks to centralizing knowledge about how the
software _actually_ works, how it _actually_ does
stuff in the real world.

Instead of thinking of ourselves as the team who
_owns_ infrastructure and deployment, we should
think of ourselves as the team whose job it is to
first learn, and then teach, and then stop
directly handling, the various tools,
technologies, and relationships that make up the
interface between development and operations.
After the old adage, we're not giving a man a
fish.  We should be learning to fish, teaching
others to fish, and then moving on to learning and
teaching agriculture, then government, then
performance art.

If that's the case, and each of our projects is
ultimately a short-term project, our charter will
run out, and we'll have to think of something more
valuable to do with our time.  That doesn't seem
so bad.

We'll see how that goes on Monday.


[modeline]: # ( vim: set spell formatoptions+=a textwidth=50 : )
