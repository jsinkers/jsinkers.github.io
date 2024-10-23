---
title: "Other projects"
excerpt: "Collection of other coursework and side projects"
collection: portfolio
---

## Breadboard computer

Personal project, 2019-2020

<!--[Fibonacci sequence on breadboard computer](https://imgur.com/gallery/4jkHO5a)-->
<blockquote class="imgur-embed-pub" lang="en" data-id="a/4jkHO5a"  ><a href="//imgur.com/a/4jkHO5a">Fibonacci</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

I constructed this 8-bit breadboard computer, largely following [Ben Eater's brilliant series](https://eater.net/8bit/). I made some changes here and there, and used 74HC series ICs instead of 74LS as they are a lot cheaper and
easier to find - these are mostly compatible but sometimes needed changes. I really enjoyed learning about hardware at the level of logic gates and gradually building up to the point where you have a fully-functional, programmable, Turing-complete computer running your programs.

<!--I have some more details on it written up [here](https://jsinkers.github.io/notes/notebooks/other/01_breadboard_comp.html).-->

## Conway's Game of Life and other cellular automata

Personal project, 2020

Always a favourite of mine - here's [Conway's Game of Life](https://jsinkers.github.io/conway/conway.html). I love the emergence of complexity from the application of simple deterministic rules.

![Conway's Game of Life](/images/conway.gif)

I have also implemented Wolfram's [256 rules](https://jsinkers.github.io/conway/rule.html).

[4 Billion Rules](https://jsinkers.github.io/conway/rule-extended.html) This is my extension of 256 rules, which uses 2 neighbours either side of each cell to determine the next cell state. As there are 5 cells, there are 32 possible states, meaning there are 2^32 ~ 4 billion rules. I always find something new when I explore some random rules.

### Cellular Automata Planter

Personal project, 2024 <!-- TODO -->



## Quadlock Clone - 3D Printing

Personal project, 2019

I love compliant mechanisms and print-in-place assemblies. I designed a clone of a [Quadlock mount](https://www.thingiverse.com/thing:3870880) for 3D printing (by FDM) which prints as a single piece with an integrated orthoplanar spring.

![Quadlock mount](/images/quadlock.png)

## 3D Pong on an 8x8x8 LED cube

Personal project, ~ 2013

A long while back I made an [LED cube](https://youtu.be/BrMr_Wx8Z84), using protoboard and some Atmega microcontrollers plus endless soldering. I thought it might be fun to create 3D pong, so I created a controller using a thumbstick and an ATtiny microcontroller, and coded up a game of 3D pong.

- [Joystick video](https://youtu.be/TF5w_ConQk8)
- [3D Pong Video](https://youtu.be/0-yoEmxVzAU)

## AI Player for Yinsh

Course project, AI planning for autonomy, 2022

- Yinsh is a 2 player competitive board game, similar to a combination of Go and Othello
- As a team of 3, we created an AI player for this game using a few AI techniques:
  - heuristic search
  - Q-learning/temporal difference methods
  - Monte Carlo Tree Search
- [Video](https://youtu.be/VLc_vtldEkc)

![Yinsh](/images/yinsh.png)

## Centralisation in Proof of Stake blockchains

Course project for Cryptocurrencies and Decentralised Ledgers, 2022

- Centralisation is a problem for decentralised blockchains as it can lead to various attacks (e.g. 51% attacks)
- Proof of Stake is increasingly preferred as the consensus mechanism over Proof of Work for a variety of reasons (e.g. vastly lower energy consumption)
- As a team of 3, we scraped block headers for 3 proof of stake chains: Solana, Cardano, and Polkadot
- we estimated the proportion of stake of the top validators based on selection frequency
- we computed the level of centralisation using a variety of metrics (e.g. Herfindahl-Hirschman index)
- Solana was found to have a considerably higher level of centralisation than Cardano or Polkadot. This was consistent with Cardano and Polkadot having designed in incentives to discourage centralisation, while Solana had no such mechanism. 

![Proof of Stake Centralisation](/images/pos-comparison.png)

## Fundamental constants of the Universe 

Summer vacation research scholarship, UNSW School of Physics, 2011

A fascinating project helping to reduce data from observations of quasars from the High-resolution echelle spectrometer instrument in the Keck telescope. The research group at UNSW found evidence of variation in the
fine-structure constant across the sky, which goes against one of the fundamental assumptions of cosmology of 
isotropy.

![Quasar absorption spectrum](/images/keck.png)
(Source: King, J. PhD Thesis: Searching for variations in the fine-structure constant and the proton-toelectron
mass ratio using quasar absorption lines. Sydney : University of New South Wales, 2010.)

## Warman Competition - National finalists

Engineering student competition, 2011

As a team of 4 we developed an autonomous vehicle to traverse a track, pick up nine coloured balls, return to the other end of the track and place the balls in individual designated slots. The vehicle had to negotiate a height clearance obstacle in the centre of the track, and was subject to a number of size and weight constraints. I was responsible for the development of electronics and programming using Arduino to control a variety of sensors and motors. This project was great because I got to teach myself about Arduino, electronics, sensors, and designing PCBs.

![Warman competition](/images/warman.gif)
