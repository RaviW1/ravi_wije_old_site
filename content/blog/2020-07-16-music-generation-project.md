---
title: Music Generation Project
author: Ravi Wijeratne
date: '2020-07-16'
slug: music-generation-project
categories: []
tags: []
disable_comments: true
---
I took on a small project this year. I wanted to work more on nueral networks so I attempted to create one that generated music. I used a dataset of midi versions of mozart's music. In order to create the algorithm I utilized this [tutorial](https://www.analyticsvidhya.com/blog/2020/01/how-to-perform-automatic-music-generation/). This tutorial was very helpful in helping me understand how to work with midi data. I used a modified version of the WaveNet Architecture. One problem I ran into was that the model tended to return a long run of the same note. So in the end it would only half the time generate a good song. I want to make the model more complex in the future and train it with more data.
<audio controls>
  <source src="/blog/2020-07-16-music-generation-project_files/music-3.ogg" type="audio/ogg">
</audio>