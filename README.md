# steam

A recommendation system for Steam using matrix factorization

## Variables

*int* `user_id`: numerical ID to identify while anonymizing Steam users  
*str* `game_title`: name of the game with which the user made an interaction  
*str* `behavior`: type of behavior exhibited by user; can only be either "purchase" or "play"  
*int* `value`: if the `behavior` value is "purchase", the `value` is always 1; otherwise, it specifies the number of hours the game has been played by the user

## Files

Aside from `README.md`, the repository contains 2 other files:

1. steam-200k.csv, which contains the data used for training the recommendation system
1. steam.ipynb, which contains the code for training the recommendation system and recommending video games to a certain user

## Remarks

This recommendation system was developed with the goal of exploring Tensorflow through making projects. In the future I hope to improve it by programming a more sophisticated model with three stages: retrieval, ranking, and post-ranking.

<br>

- - -

#### Code authorship

2021 © Jessan Rendell G. Belenzo

<br>

#### Terms of use

Licensed under the GNU General Public License v3.0. See [LICENSE](LICENSE).

<br>

## Acknowledgments

The Tamber Team (2017). Steam Video Games, version 3. Retrieved October 29, 2021 from https://www.kaggle.com/tamber/steam-video-games.
