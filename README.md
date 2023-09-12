# Higher Lower Social Media Game
This is a social media game where the quantity of followers for two celebrities are compared. 


The aim of the game is to guess which celebrity has the most followers.


Players get 1 point for each correct answer. 

## Objectives


## Results
![image](https://github.com/frantzalexander/higher_lower/assets/128331579/ad75cf3c-51db-4446-b50c-1fe9db46d9eb)


## Process
```mermaid
flowchart TD
start((START))
logo[Display Logo]
score[Show Score]
first_celeb[Compare 1st Celebrity]
versus[Display The VS Logo]
second_celeb[Against 2nd Celebrity]
ask{Ask The User Which Celebrity Has More Followers}
score_increase[Increase Score]
play_again{Ask User To Play Again}
finish((END))
start --> logo
logo --> score
score --> first_celeb
first_celeb --> versus
versus --> second_celeb
second_celeb --> ask
ask -->|Right Answer|score_increase
score_increase --> score
ask -->|Wrong Answer| play_again
play_again -->|No| finish
play_again -->|Yes| score
