# how-to-improve-the-valid-metric-kick-off
This repo stores my code for the Kaggle analytics competition of NFL Big Data Bowl 2022


# Purpose
This is a Kaggle competition for analytics purpose. Participants need to find insight from NFL special play data and bring up actionable suggestions.

My analysis focuses on how to kick a ball far in kickoff plays, for the kick length is a highly correlated metric with how many scores a team can make.

# Business questions

1. Is kick length a good metric to evaluate a kickoff play in NFL games?

2. How to kick a ball far?

# Dataset
https://www.kaggle.com/competitions/nfl-big-data-bowl-2022/data

# Jupyter notebook
It is included in this repo named how-to-improve-the-valid-metric-kick-length.ipynb

You can also find my Kaggle notebook [here](https://www.kaggle.com/code/tianmin/how-to-improve-the-valid-metric-kick-length)

# Summary
**"Kick the ball harder, if you want to kick it further."** This is what I learned from a lot of people saying. 

But how true is it? Or what does it exactly mean when we say "kicking it harder"? Data from NFL games reveal to us some insight which I'd like to share with you in this notebook.

Kickoff play is the most common type in special plays from season 2018 to 2020. Even though with six different outcomes, the kicking team has basically one ultimate goal - gaining as many yards as possible after the session ends. In this notebook, I'd bring up the **kick length** of the ball as an actionable and robust metric to evaluate how good a kickoff it is. This metric has a high positive association with the number of gained yards, since the receiving team needs to return the ball from a very low yard line if the ball is kicked long distance. Apart from that, with using the multiple linear regression method, I also find two relevant variables which might affect the kick length. Those are 

1. **Foot speed** in the approach, usually seen in a long approach distance, and it is also a predictor of the last step length, which is related with how much engergy will be transmitted to the ball, according to the formula of kinetic energy.

2. The **direction of the ball being kicked to**. If the ball was kicked to the right side of the kicker, the length is usually shorter than to the center or to the left. The hypothesis behind is kicking to the right takes more energy from the body because of a larger pivoting angle. This cost of energy results in less volume brought to the ball.