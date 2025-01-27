# Mission 1 - Uncle Arnold's Local Band Review

## Task description

Your friend is being cheated out of hundreds of dollars. Help him make things even again!

<details>
  <summary>Full description</summary>

From: HeavyMetalRyan

Message: Hey man, I need a big favour from you. Remember that website I showed you once before? [Uncle Arnold's Band Review Page](https://www.hackthissite.org/missions/realistic/1/)? Well, a long time ago I made a $500 bet with a friend that my band would be at the top of the list by the end of the year. Well, as you already know, two of my band members have died in a horrendous car accident... but this ass hole still insists that the bet is on!
I know you're good with computers and stuff, so I was wondering, is there any way for you to hack this website and make my band on the top of the list? My band is Raging Inferno. Thanks a lot, man!
</details>

## Answer

When you enter the site, the ranking of the teams is shown:

<p align="center">
  <img src="images/webpage.png">
</p>

After opening `Inspect` from the browser, it is possible to check the code of the site. There I can find the section responsible for awarding points to teams:

<p align="center">
  <img src="images/source_code.png">
</p>

To elevate a team to first place, all I need to do is change the value of the points awarded as in the example below:

<p align="center">
  <img src="images/changed_value.png">
</p>
