
# *ADM-HW-2*   *GROUP - #6*

## Steam Game Reviews Analysis

![steam1](https://github.com/user-attachments/assets/3584628a-2dbf-4c88-aeb5-b1a40df3eb9e)

## Project Overview

Video games have become a significant part of global culture, evolving from a pastime to an influential industry impacting technology and social interactions. Platforms like **Steam** play a central role, offering not only game distribution but also features like community forums, in-game chat, and cloud storage. Steam has fostered a vibrant community where users share their gaming experiences through reviews, providing insights into player preferences, criticisms, and trends in gaming.

Our objective is to analyze these reviews and answer key research questions. Our findings will help understand what players value in a video game, leading to better design, marketing strategies, and ultimately a more engaging user experience.

## Objectives

The primary objective of this project is to uncover meaningful patterns and insights from Steam game reviews. Specifically, we aim to:

1. Identify key factors that influence positive and negative reviews.
2. Discover common themes and trends across highly rated and poorly rated games.
3. Analyze the relationship between review length, sentiment, and user engagement.
4. Provide actionable recommendations based on player feedback to enhance future game development.

## Dataset

The dataset consists of **Steam game reviews** and includes the following attributes:

- **Unnamed: 0**: Index column.
- **app_id**: Unique identifier for each game on Steam.
- **app_name**: Name of the game.
- **review_id**: Unique identifier for each review.
- **language**: Language in which the review was written.
- **review**: Content of the review written by the user.
- **timestamp_created**: Date and time when the review was created.
- **timestamp_updated**: Date and time when the review was last updated.
- **recommended**: Indicates whether the review recommends the game (e.g., True/False).
- **votes_helpful**: Number of helpful votes received by the review.
- **votes_funny**: Number of funny votes received by the review.
- **weighted_vote_score**: Weighted score for the review based on votes.
- **comment_count**: Number of comments on the review.
- **steam_purchase**: Indicates whether the game was purchased on Steam.
- **received_for_free**: Indicates whether the game was received for free.
- **written_during_early_access**: Indicates if the review was written during early access.
- **author.steamid**: Steam ID of the review author.
- **author.num_games_owned**: Total number of games owned by the author.
- **author.num_reviews**: Total number of reviews written by the author.
- **author.playtime_forever**: Total playtime of the game in minutes.
- **author.playtime_last_two_weeks**: Playtime in the last two weeks, in minutes.
- **author.playtime_at_review**: Playtime at the time of the review, in minutes.
- **author.last_played**: Timestamp of the last time the game was played by the author.
- **year_month**: Year and month of the review (derived attribute).
- **review_hour**: Hour of the day the review was posted (derived attribute).

Each row in the dataset represents a unique review, capturing interactions between players and games.

## Project Structure


The dataset reflects a diverse collection of reviews, capturing unique interactions between players and games. Each row represents one review.

## Project Structure
