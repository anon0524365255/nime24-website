---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: post
title: Real-time Timbre Remapping with Differentiable DSP
---

<div align="center">
    <a href="https://github.com/anon0524365255/nime24-plugin"><i class="fab fa-github"></i> <b>Audio Plugin</b></a> | <a href="https://github.com/anon0524365255/nime24-code"><i class="fab fa-github"></i> <b>Training Code</b></a> 
</div>

<br />

## Musical Experiment

### Snare Preset 1

Synth Only Mix:
<iframe width="560" height="315" src="https://www.youtube.com/embed/GuR5lGN3oeM?si=1Mf2JxN4Xdoh1uWu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Synth plus Drum Mix:
<iframe width="560" height="315" src="https://www.youtube.com/embed/jhXyEqhFnuE?si=iliz6GoLJf9Qfvgx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Snare Preset 2

Synth Only Mix:
<iframe width="560" height="315" src="https://www.youtube.com/embed/mdg_xsxcLPU?si=eO0d4EAhRCgCg5f3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Synth plus Drum Mix:
<iframe width="560" height="315" src="https://www.youtube.com/embed/FEy9pRbeJOc?si=6bvK9ZeAi4WhPJh9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Snare Preset 3

Synth Only Mix:
<iframe width="560" height="315" src="https://www.youtube.com/embed/2R55K15gUuk?si=zWN8v3EGvUSwUM__" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Synth plus Drum Mix:
<iframe width="560" height="315" src="https://www.youtube.com/embed/Gyxs6uBiSPU?si=2xAxP2tHRmezRuaB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Snare Preset 1 - Missed Hits
Example of playing from quiet to loud, showing that quiet hits were not captured well with
this particular onset detection setup.
Cresendos on the drumhead show more
dynamic range than the rim hits during synthesis.

Synth Only Mix:
<iframe width="560" height="315" src="https://www.youtube.com/embed/vz6CXLjIruo?si=2N0Pe_AONdDau2KJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Synth plus Drum Mix:
<iframe width="560" height="315" src="https://www.youtube.com/embed/0ii6G0TZI1M?si=SungHmUDyM6if3oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


<!-- ## Abstract

Timbre is a primary mode of expression in diverse musical contexts.
However, prevalent audio-driven synthesis methods predominantly rely on pitch and loudness envelopes, effectively flattening timbral expression from the input.
Our approach draws on the concept of timbre analogies and investigates how timbral expression from an input signal can be mapped onto controls for a synthesizer.
Leveraging differentiable digital signal processing, our method facilitates direct optimization of synthesizer parameters through a novel feature difference loss. This loss function, designed to learn relative timbral differences between musical events, prioritizes the subtleties of graded timbre modulations within phrases, allowing for meaningful translations in a timbre space
Using snare drum performances as a case study, where timbral expression is central, we demonstrate real-time timbre remapping from acoustic snare drums to a differentiable synthesizer modeled after the Roland TR-808.
Additionally, we release an open-source audio plugin and training notebooks to allow musicians to experiment with this method within their own musical contexts. -->