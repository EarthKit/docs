---
title: Roadmap
---

EarthKit Agent is under active development. The following is a list of features and enhancements we plan to ship next. We'd love your input on what you'd like to see! Please reach out on [Discord](https://discord.gg/earthkit) if you'd like to chat.

{{% steps %}}

### More Modalities & Social Media Import
- Geolocation task consisting of multiple images
- Video uploads
- Automatically importing Tweets, Telegram posts, and other social media sources, likely via Bellingcat's [auto-archiver](https://github.com/bellingcat/auto-archiver)


### Geo-Calibration
Given an initial rough geolocation produced by EarthKit Agent, use a mix of [OrienterNet](https://github.com/facebookresearch/OrienterNet) and [Sample4Geo](https://github.com/Skyy93/Sample4Geo) to refine the geolocation to the geographical features of proximity of the point of interest.

### Expand the set of tools available to Agents
- Overpass Turbo querying (similar to the one on [earthkit](https://earthkit.app/osm)) 
- Call ML models: [EigenPlaces](https://github.com/gmberton/EigenPlaces) and [Sample4Geo](https://github.com/Skyy93/Sample4Geo)
- Python code execution for calculations
- [MultiOn](https://www.multion.ai/) Web Agent

### Improvements to Geoverification
- Support streaming for report generation
- Add more content types (e.g. showing google streetview embeds)
- Bounding box annotations of images
- Agentic Geoverification (currently we have a deterministic flow that uses LMMs as a judge and report generator.)

### Human-in-the-loop
- Ability to interrupt the agent workflow, change its behavior, and add additional instructions
- Ability for the agent to generate intermediate results / carry out sub-tasks in a geolocation project

### Tree-based Agent workflow for complex tasks
Imagine a scenario in which the image could either be in San Francisco, Tokyo, or New York. 
Instead of exploring all the possibilities at once, the agent branches out into three separate investigations, 
collecting evidence from each of the three locations. 
A tree-based approach allows the agent to explore each of the three locations in parallel, 
before merging the results back together. 
This will also enable longer chains of thought and more complex investigations.
Reference: [Language Agent Tree Search](https://arxiv.org/abs/2310.04406) and [Multion's Q](https://www.multion.ai/blog/introducing-agent-q-research-breakthrough-for-the-next-generation-of-ai-agents-with-planning-and-self-healing-capabilities).
Additionally, check out [this video](https://drive.google.com/file/d/1ES48xquWJZg8rJNxok8MEt_M08ggjLIN/view?usp=sharing) for an experimental demo.

{{% /steps %}}