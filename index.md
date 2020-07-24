---
layout: default
permalink: /
title: Home
---
My name is Aaron Tagliaboschi. Here's some stuff I'm up to:

* TOC
{:toc}

## Writing

I really enjoy writing. I'm still fairly new and trying to find my stride, but
it at least makes me happy.

### Blog
I write in a blog sometimes called [My Kind of Beauty](/blog/), where I put
thoughts and musings about me and myself. I want to start writing more technical
articles and deep dives, but I haven't yet. That'll probably be it's own thing
though...

Here's some of the more recent posts:

{% for post in site.posts limit:5 %}
[{{ post.title }}]({{ post.url }})
: {{post.excerpt}}

---
{% endfor %}

## Music

I play jazz piano and other stuff (but mostly piano and mostly jazz-adjacent).

Here's where you can find various recordings

* [SoundCloud](https://soundcloud.com/amtunlimited/)
* [BandCamp](https://amtunlimited.bandcamp.com/)
* [YouTube](https://www.youtube.com/playlist?list=PL4fu3juqIttcuNq4vL0I0oy-p5u0wD9AE)

### Releases

I've also released an album called [Time Enough](https://distrokid.com/hyperfollow/aarontagliaboschi/dmJw)
that I'm incredibly proud of.

> **Sidenote:** I've been very pleased with DistroKid as a service, so if you're
> looking to release something everywhere and think DistroKid might work,
> [here's an affiliate link](https://distrokid.com/vip/seven/654112)

I was a guest musician on my good friend
[Martha Christian's](https://open.spotify.com/artist/7scj7N4bGZIBSUspha9GtC?si=6mulavZnRHiu7xfpgVjPaQ) 
Christmas album, 
[All Will Be Well](https://open.spotify.com/album/1ikNK9UjlR0JTHjazkecHC?si=uAbMJHUZTFaPzX4r_f2CzA),
where I arranged and and played piano (and midi vibrophone) on a slightly 
different take on 
[Silent Night](https://open.spotify.com/track/7JCvFmavIW0dlvss57GETj?si=MqFXAdZBR1qDCMpQ70d_0A)

## Livestreams

Here lately I've been 
[live streaming](https://www.youtube.com/watch?v=yQ68RjxbZEE&list=PL4fu3juqIttf7z_UbRRaILsAKn-oL-r7U)
on [YouTube](https://www.youtube.com/channel/UCVlEkuqoQMnsHzjy-DJWOnA) myself 
playing piano, improvising, analyzing, and making improptu arrangements live on
the spot. You can also find other bits of improv and music there as well. I'm 
trying to develop it a bit more as I learn on the guitar.

## Web Toys

Every once in a while I make something small or silly (another thing I'd like to
do more). 

Here's a couple hosted here:

{%for project in site.data.projects%}
  [{{project.name}}](/{{project.github}}/) ([Code](https://github.com/amtunlimited/{{project.github}}))
  : {{project.description}}
{%endfor%}

I don't really do social media, but there's a RSS feed for my blog and a mailing
list (linked below), and all of the various music platforms have subscriptions.
Drop me an email if you've seen anything you liked, and peace be with you.

{% include signoff.html %}
