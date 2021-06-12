---
layout: post
title:  "Checking out Observable"
date:   2021-06-09 17:37:00 -000
---

Recently, I've been having a lot of fun checking out [Observable](https://www.observablehq.com){:target="\_blank"}---it's pretty cool! (You can check out my work so far on [my profile](https://www.observablehq.com/@pgi){:target="\_blank"}). If you've never heard of it, it's a little like a Jupyter notebook, but it uses Javascript instead of Python (with a couple of other fun differences!). Now, if you're like me, you say to that, "ew...why would I want to use Javascript, blech." But, after playing around with it a little, there's a couple things that I really like about it, and I definitely think I'll be using it in the future.

The first thing that's nice about using Javascript has got to be the ~interactivity~. It really just takes your charts up to another level.  I found it to be a little easier to use than Bokeh or Plotly as well, and definitely more customizable as you can really animate almost anything super easily with D3. I really don't think there was a good way to show the [street shortest path map](https://observablehq.com/@pgi/philadelphia-street-network){:target="\_blank"} that I made without the interactive element, it just would not have had the same effect.

The other thing I like is that the notebooks look super nice. The default jupyter notebook looks ok, but without doing anything on Observable, you're starting from a very good place. It's just nice to be able to easily get some super nice-looking results.

The main downside is that Javascript doesn't have anywhere close to the data processing libraries that Python has with numpy/scipy/pandas. So, I've taken to doing my data processing in a Jupyter notebook, then uploading a final dataset with just what I want to show onto Observable, and then going from there to create the more polished visual. It's not the best workflow for fast prototyping, so I see myself more using Observable for final, locked-in, nice-looking versions of visualizations, rather than intermediate stages.

Looking forward to doing a lot more with Observable in the future. If you want to see all my notebooks, check out [my Observable profile](https://www.observablehq.com/@pgi).