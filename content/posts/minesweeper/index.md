---
date: 2026-06-08T23:21:08-04:00
description: "placeholder"
featured_image: "/images/minesweeper.png"
title: "How good can I get at Minesweeper in 24 hours?"
tags: ["Minesweeper"]
categories: ["Hobbies"]
Draft: True
---

# Background

## Rules/Objective

Minesweeper is a video game where it features a grid of tiles you can click on, some of which have hidden mines. The objective is to click on all of the non-mine tiles. The revealed tiles will have a number that represents the corresponding number of mines adjacent to that tile. To lose the game, it's relatively simple; click on a tile with a hidden mine!

Let's do a quick example if you do not know the rules already:

We are given a 4x4 grid with four mines.

![alt text](image.png)

First tile click:

![alt text](image-1.png)

There is the number "2", meaning that there are two mines in the adajcent squares (including the corners) of the revealed tiles.

Another tile click:

![alt text](image-2.png)

There is also a number "2" here, there could be a few scenarios here:
1. There are two mines intersecting the revealed tiles (The flags are meant to be markers for the tiles that have a mine)
![alt text](image-3.png)

2. There are three mines in a diagonal format
![alt text](image-4.png)

3. There are four mines on the opposite side of the revealed tiles
![alt text](image-5.png)

There are much more possiblites, but I wanted to highlight a few.

Clicking on the third tile:

![alt text](image-6.png)

This actually reveals alot of information. Since we know that the are four mines in total, the number four in the revealed tiles means that all possible mines are within the adjacent squares of that tile! So effectively, we can simply ignore the right-most and the bottom-most row/column.

![alt text](image-7.png)

This is nice because we can click on those tiles freely to gather further information.

![alt text](image-8.png)

Okay! This is relatively straightforward now.

![alt text](image-9.png)

We *know* that there are two mines here b/c there are two mines in the tile cirlced, and since there are two tiles left, they must be there!

![alt text](image-10.png)

There is also another mine near the bottom left corner, as the number one below indicates as so. Notice how that there are two mines in the adajcent tiles marked already for number circled. If we know for *sure* that there are two mines in those locations, we can simply click on the unmarked tile that is adajcent to the circled number.

![alt text](image-11.png)

Yay!! That's how you win in Minesweeper.