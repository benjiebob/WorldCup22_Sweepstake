# World Cup Qatar 2022 - The Sweepstake

![World Cup 2022 - Qatar](worldcup_banner.jpg)

## Introduction

Dear friends, family & footballers, welcome to the internationally renowned World Cup Sweepstake! This README explains how the sweepstake works, presents the draw and vaguely describes prizes to be won.

To quickly view your teams, there's a handy [Streamlit webpage](http://worldcup.benbiggs.co.uk/).

The tournament starts on 20th November 2022. A match schedule is available at [World Cup 2022 - BBC Football](https://www.bbc.com/sport/football/world-cup/schedule). A wall chart with TV listings is available at [FourFourTwo - Wall Chart](http://cdn.mos.cms.futurecdn.net/emvLGLK2Ra9Ci2d8aVknq/wallchart.pdf).

For the geeks among you, the code for this World Cup Sweepstake is available in this repository. Data munging code is [here](https://github.com/benjiebob/WorldCup22_Sweepstake/blob/main/extract_rankings.py) and a simple-to-run Jupyter Notebook which computes the draw is [here](https://github.com/benjiebob/WorldCup22_Sweepstake/blob/main/run_worldcup_draw.ipynb). The streamlit demo code is available [here](https://github.com/benjiebob/WorldCup22_Sweepstake/blob/main/streamlit_demo.py).

Good luck!

## How it Works

The Sweepstake is free to enter. The 32 World Cup teams are sorted according to their FIFA World Ranking and divided into two categories: *upper* and *lower*. Each player is randomly assigned one team from the *upper* category and one from the *lower* category.

For compelling (and from the perspective of this sweepstake, entirely useless) team tips, I recommend the following [Guardian article](https://www.theguardian.com/football/2022/jun/15/world-cup-2022-power-rankings-final-32-qatar). Note the intriguing differences between the Guardian & FIFA World Cup rankings below. Wow, isn't football fun!

## Prizes

Prizes will be awarded to players with:
- The *winning* World Cup team, and/or,
- The *best performing* team from the bottom 8 according to FIFA World Cup Ranking. In particular, the players eligible for this prize are those assigned to: *Costa Rica, Australia, Canada, Cameroon, Ecuador, Qatar, Saudi Arabia and Ghana*. In order, *best performing* will be decided by: tournament progression, head-to-head match-ups, goal difference and goals for. 

The precise nature of the prizes will be revealed towards the end of the tournament. It is worth noting that the esteemed organizing committee (which comprises at least one doctor) anticipate that the prizes will be strongly personalized.

## The Draw

A random seed was selected according to the World Cup's start date: **20112022** (in DDMMYYYY format). The results of the [draw](https://github.com/benjiebob/WorldCup22_Sweepstake/blob/main/run_worldcup_draw.ipynb) are as follows:

|   FIFA World Cup Ranking | Team           | Group   |   FIFA World Ranking | Player    |
|-------------------------:|:---------------|:--------|---------------------:|:----------|
|                        1 | Brazil         | G       |                    1 | Ben CJ    |
|                        2 | Belgium        | F       |                    2 | Tom R     |
|                        3 | Argentina      | C       |                    3 | Jackie B  |
|                        4 | France         | D       |                    4 | Ben B     |
|                        5 | England        | B       |                    5 | Grandma   |
|                        6 | Spain          | E       |                    7 | Hannah GO |
|                        7 | Netherlands    | A       |                    8 | Nick B    |
|                        8 | Portugal       | H       |                    9 | Bec L     |
|                        9 | Denmark        | D       |                   10 | Nana      |
|                       10 | Germany        | E       |                   11 | Emily P   |
|                       11 | Croatia        | F       |                   12 | Josh S    |
|                       12 | Mexico         | C       |                   13 | Pip L     |
|                       13 | Uruguay        | H       |                   14 | Grandpa   |
|                       14 | Switzerland    | G       |                   15 | Sam B     |
|                       15 | USA            | B       |                   16 | Mike L    |
|                       16 | Senegal        | A       |                   18 | Adam B    |
|                       17 | Wales          | B       |                   19 | Hannah GO |
|                       18 | IR Iran        | B       |                   20 | Ben CJ    |
|                       19 | Serbia         | G       |                   21 | Grandpa   |
|                       20 | Morocco        | F       |                   22 | Sam B     |
|                       21 | Japan          | E       |                   24 | Mike L    |
|                       22 | Poland         | C       |                   26 | Nick B    |
|                       23 | Korea Republic | H       |                   28 | Josh S    |
|                       24 | Tunisia        | D       |                   30 | Pip L     |
|                       25 | Costa Rica     | E       |                   31 | Jackie B  |
|                       26 | Australia      | D       |                   38 | Adam B    |
|                       27 | Canada         | F       |                   41 | Grandma   |
|                       28 | Cameroon       | G       |                   43 | Emily P   |
|                       29 | Ecuador        | A       |                   44 | Nana      |
|                       30 | Qatar          | A       |                   50 | Tom R     |
|                       31 | Saudi Arabia   | C       |                   51 | Bec L     |
|                       32 | Ghana          | H       |                   61 | Ben B     |

## Acknowledgements
- FIFA World Rankings data 1992-2022 from [Kaggle](https://www.kaggle.com/datasets/cashncarry/fifaworldranking?resource=download).
- FIFA World Cup 2022 teams/groups from the [official FIFA website](https://www.fifa.com/fifaplus/en/articles/qatar-2022-all-qualified-teams-groups-dates-match-schedule-tickets-more).
- World Cup banner downloaded under trial account from [here](https://www.dreamstime.com/vinnytsia-ukraine-february-fifa-world-cup-qatar-banner-fifa-world-cup-qatar-banner-image241473272).
