---
title: Multi-Agent SLAM and navigation using ROSBot
summary: "Navigation using a team of robots in an indoor environment with obtacles"
tags:
- Motion Planning
- Algorithms
- Heuristics
date: "2021-05-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Autonomous Systems Laboratory
  focal_point: Smart

links:
- icon: linkedin
  icon_pack: fab
  name: Follow
  url: https://www.linkedin.com/in/nykabhishek/
- icon: youtube
  icon_pack: fab
  name: Video
  url: https://youtu.be/oH0RVqI9pJU
url_code: "https://github.com/nykabhishek/rosbot_multi-agent_SLAM"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

<b>Location:</b> Autonomous Systems Laboratory (https://autonomy.engr.tamu.edu/), Texas A&M University - College Station, TX

<!-- <p>
    <img src='/images/rosbots.jpg'>
    <small> ROSBots by Husarion </small>
</p> -->

<p>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/oH0RVqI9pJU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

<p>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/CRFiTtZXsXA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

In this project, I implemented multi-agent SLAM to obtain occupancy grid maps from point-cloud data via autonomous frontier exploration using ROSBots 2.0 by Husarion. I tinkered around to establish navigation capabilities on this robot and used algorithms like Dijkstra, A*, D* lite, RRT, and Probabilistic Roadmap (PRM) planners for indoor navigation. Further, I used these robots as a platform for demonstrating proof-of-concept prototypes of multi-agent path planning methods developed as part of my Ph.D. thesis "Planning and Vision-based tools for Autonomous Vehicles.