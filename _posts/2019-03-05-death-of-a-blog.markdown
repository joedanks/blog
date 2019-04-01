---
layout: post
title:  "Death of a blog"
date:   2019-03-05 21:00:00 -0600
categories: non-tech
---
The date was February 12th, 2019. It was a usual winter day. We had a couple of inches of snow the night before. I had managed to clear the driveway and sidewalks bright and early. And managed to get my daughter dropped off at daycare and arrived at work; without issue. I knew the day was going too smoothly. I received a text from my wife saying the power went out. I didn't give much thought to it other than I was hoping she wasn't expecting me to do something about the outage. 

Later that evening I was sitting down to write a new blog post, and couldn't get to my site.  I figured that with the power outage my modem picked up a new IP and I would need to update No-IP. Well the IP listed was the same as my current. So next I tried to remote into the RaspberryPi directly. No luck. I walked over to the Pi sitting next to the modem and saw only a single red light on. I was a little concerned at that point. So I unplugged and moved it over to my desktop to diagnose. Still no luck to get it to turn on. Off to google to see what a single red light means. I was pretty sure I should have a solid red and a blinking green light. Turns out a solid red light means it can't boot, and primary reason is the Pi is having a problem reading the sd card.

Then next part is an assumption of what transpired that fateful day. More than likely the power outage and/or restoration resulted in a power surge. My RaspberryPi hosting my blog is not behind a surge protector. So that poor little computer got a little more than it could handle. The only way for it to survive was to let the sd card take the punishment. So the little computer did just that. It let the sd card take the brunt of the surge and fry. Since I was using WordPress; the blog articles were all stored on that sd card. Poof. Gone. Never to be seen again.

It took me a few weeks to move past the trauma. I enjoyed writing those blogs. They wil be missed.