So I decided to take 2 months off this summer, quite on short notice so I would like to thank the Liip management to be so flexible on this.
Of course I don't really ever take off from open source, so I have spent a fair bit of time working on the [Symfony CMF](http://cmf.symfony.com).
Gathering feedback from the community via [multiple](http://pooteeweet.org/blog/2123) [blog](http://pooteeweet.org/blog/2129) [posts](http://pooteeweet.org/blog/2146), which [taught me some things about OSS](http://pooteeweet.org/blog/2151) and then doing something with it like [starting documentation](http://symfony-cmf.readthedocs.org/en/latest/index.html), a [simpler initial setup](https://github.com/symfony-cmf/symfony-cmf-standard) and adding some missing features.
I also gave talks about Symfony2 at user groups in [Vienna](http://www.meetup.com/sfugvienna/events/69963632/), [Odessa](http://www.ciklum.com/join/community/explore-symfony2-code-odessa/) and [Kiev](http://www.ciklum.com/join/community/explore-symfony2-code/) and attended [DrupalCon in Munich](http://munich2012.drupal.org).
Oh and I gave another talk at [Centralway](http://centralway.ch) as they seem to also be diving into the world of Symfony2.
During my time off I also spent a bit of time tweaking the integration example we have with Magnolia ahead of my presentation at the [Magnolia Conference](http://www.magnolia-cms.com/community/magnolia-conference.html) on PHPCR on the second day back from "vacation".
It seems like just as my "vacation" contained what others would consider work, my week back at "work" contained what others would call "vacation", i.e. I traveled to the Croatian island of Bol to attend [ezSummerCamp](http://ezsummercamp.com) to teach about Symfony and help interface the ezPublish community with that of Symfony2.
Finally I attended the [Symfony2 CMF hackday](http://rocketlab.liip.ch/event/symfony_cmf_hackday_september) in Fribourg.
What follows are some more details on what I learned along the way of all these trips and the things I worked on in between.

Vienna
======

So I was approached by Julian at Symfony Live in Paris if I would be willing to come by and help energize the local Symfony2 user group with a talk.
As I was planning a trip to the Ukraine and Russia, I noticed that there would be cheap options to fly via Vienna so I contacted Julian who made it all happen quickly and was kind enough to host me.
What is great is that several Drupal core developers also came by to my talk and it seems like there is now more and more [Symfony2 - Drupal collaboration](http://groups.drupal.org/node/243968) going on between the user groups in Vienna.
Speaking of user groups, there is a [new section for events](http://symfony.com/events/) on the Symfony2 websites listing meetings around the world.

Ukraine and Russia
==================

I then went on to Odessa to play at the Ukrainian Beach Ultimate Frisbee Championships where I placed 3rd playing with the team from Odessa.
However I also did a presentation on Symfony2 at the [Ciklum](http://ciklum.com) offices to a crowd of about 20 developers from the region.
After Odessa I went on to Kiev where I did another talk, this time to about 130 people in a panoramic room overviewing Kiev, at a Ciklum office.
I have met some developers from Ciklum through the projects we did for NZZ, who had invited me to come speak, so I was very happy I could make it happen.
Ciklum on the other hand took care of airport pickup, a place to stay in Kiev and a full day personal tour of Kiev.
What stood out from these talks was that there were a huge number of developers with really cool ideas and projects that somehow do not yet feel connected enough with the rest of the community.
So I was happy to do some tweets and email forwarding for them to get their voices heard.
For example one developer was having performance issues with Symfony2 forms so I suggested that he would create a test project on github and mail me the url which led to some major work by Bernhard to [address form performance issues](http://symfony.com/blog/symfony-2-1-0-beta4-released).
I went on to also travel to Moscow and Nishny Novgogrod to also play the Russian Championships, finishing 3rd and 4th in the open and mixed divisions and winning the [spirit prize](http://en.wikipedia.org/wiki/Ultimate_frisbee#Spirit_of_the_Game).
Unfortunately I didn't manage to organize any talks while I was there, but I hear some people from Moscow attended my talk in Kiev.
Also it seems like some Magento developers were at my talk, but when I poked them about it I couldn't get confirmation if using Symfony2 is on their radar.
Seems to me like its more likely they will adopt Zend Framework 2.

Working on the CMF
==================

On my return I began focusing on the CMF.
The main feedback lesson I got was that while people were telling me that "PHPCR is too complex" in fact what they were saying was that "they don't know enough people that know PHPCR yet" in order to trust it works and more importantly to trust that they can get help if necessary.
As such I realized that I needed to make it even easier for people to try it out, so I created the Symfony2 CMF standard edition and updated the homepage with lots of content.
Especially I finally setup rendering of the rST formatted documentation on [readthedocs.org](http://readthedocs.org) and did a first round of updates.
However there is still [work to do there](https://github.com/symfony-cmf/symfony-cmf-docs/issues).
I also proposed an [update to the roadmap](https://groups.google.com/forum/?fromgroups=#!topic/symfony-cmf-devs/XwaDeFam79I).
Overall I think currently we have quite a momentum going with many people asking questions but more importantly also contributing here and there.
Actually we have always had a healthy stream of contributions to PHPCR, but now we are also seeing more people helping on Symfony2 Bundles for the CMF.
I also finally put together a [website for the DecoupledCMS](http://decoupledcms.org) vision that [Henri](http://bergie.iki.fi) and I have been pushing at various conferences using the great logo designs [Noora](http://www.noppes.fi) had created for us thanks to Liip sponsoring.

DrupalCon Munich
================

Next stop was DrupalCon in Munich.
Was great to catch up with many of the people I had met personally for the first time at DrupalCon Denver and of course also meeting many new people.
I didn't attend talks, but there was plenty of hallway discussions and hacking where I could help with some insights on Symfony2, REST and so on.
The excitement about the Symfony2 adoption was still all around and since Denver many things have become clearer, but there still remains a lot of work and the [time until the code freeze](http://buytaert.net/updated-drupal-8-release-schedule) is running shorter and shorter.
One big todo that came up there was that we need to work together with Drupal and other big Symfony2 adopters on creating some governance for security and release management coordination.

Visiting Centralway
===================

Just as my last week was starting [Walid](http://twitter.com/lido_lee), who I met during a project at [Joiz](http://joiz.ch), contacted me that Centralway would love to get a short introduction into Symfony2.
So I went over to their offices in Winterthur giving a one hour code walk through to their developer team.
I was surprised to meet [Hugo](http://twitter.com/hschot) there, who I had originally met while working for Optaros and who I last talked to while he was working for Local.ch.
At any rate looks like Centralway is going to jump in with both feet into the Symfony2.

Vagrant at Liip
===============

So my first day back, I spend one day at the office catching up with different discussions.
What I loved most about getting back is that Liip has now adopted [Vagrant](http://vagrantup.com) for project setup.
So getting the new project installed consisted of installing [VirtalBox](http://virtualbox.com), calling "git clone" followed by "cd ..; vagrant up".
How sweet is that? All members of the team have the same setup, no fuss.
It looks like Liip will bring [all this goodness](http://twitter.com/chregu/status/243768581773479936) to the general Symfony2 world, with [an open PR](https://github.com/symfony/symfony-standard/pull/407) adding a Vagrant template setup to the official Symfony2 Standard Edition.

Magnolia Conference
===================

Next day I headed to Basel for the Magnolia Conference.
It was funny to meet two old friends Zak and Sandro from the PHP world at my very first Java based technology conference.
Also caught up with Gregory who I had last seen at the hack day in April where we first prototyped the [PHPCR - Magnolia integration](https://github.com/symfony-cmf/cmf-sandbox/compare/magnolia_integration).
But I met tons of more people and interestingly enough nobody was bashing PHP.
Instead I had lots of interesting technology discussions.
It was clear to everyone that the choice of language doesn't save from or condemn to you.
Speaking of which the [UI demo of Magnolia 5](http://www.youtube.com/watch?v=6HhZhLpSGsk&list=PLxHBbwVVoCoZHAkbVM31t3qq-zavkLnxN) was quite impressive and I believe that [create.js](http://createjs.org) could fit in very well with what they are doing there and I hope I have sparked interest in create.js with a few people during the conference.
Magnolia plans to release a set of tutorials show casing what is possible.

ezSummerCamp
============

My final story covers ezSummerCamp where I was invited by Ivo, who I had met at an IKS event last summer in Paris, to speak on Symfony2.
For those unaware ezSystems recently announced that version 5 of [ezPublish would be based on Symfony2](http://share.ez.no/blogs/ez/an-explosive-cocktail-symfony-and-ez-publish-5-joining-forces) and that they aim to make a release this fall already.
Do note that this release would essentially just wrap ezPublish version 4 inside Symfony2 with several tools to help data exchange.
The intention is to enable developers today to write custom code in Symfony2 and to slowly move more and more of the legacy code to Symfony2.
Again I was amazed with how excited people were at all the possibilities this is opening.
One of the cool results was that during the hack day I prototyped an integration of the Symfony2 CMF routing component into ezPublish, which has now [been committed](https://github.com/ezsystems/ezp-next/commit/773b267f2a52c170aebe957dd13c8244ab31ee12).
This same component is also [being evaluated by Drupal](http://drupal.org/node/1606794).
Fun times! Also again the topic of governance structures around Symfony2 has come up while taking to [Nicholas](http://twitter.com/jeanvoye).

Getting back again
==================

On my way back from the summer camp, I just used "vagrant up" to bring up that new projected I am working on at Liip.
I quickly added the Symfony2 CMF components and bundles to it.
Its not a CMS project per se, but it will give us a quick way to let the customer edit content, handle translations.
Can't wait to add inline editing as we should be able to wrap up a big refactoring of the create.js integration with the work done at yesterdays hack day in Fribourg.
Here is a [quick summary](https://groups.google.com/d/msg/symfony-cmf-devs/XwaDeFam79I/uOfiyGzGpVMJ) of the results.
This hack day, but more importantly the growing number of contributors, is prooving that we are now well on track with the Symfony2 CMF.
And now that it's already far along enough so that it's easier to integrate than trying to hack up something with the ORM means that we at Liip can finally start reaping the benefits of our investments!