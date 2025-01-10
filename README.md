# Exploring Hacker News Posts

This project analyzes posts from [Hacker News](https://news.ycombinator.com/), a platform where technology-related content is voted on and discussed. The analysis focuses on two types of posts:
- **Ask HN:** Users ask the community questions.
- **Show HN:** Users showcase projects, products, or something interesting.

## Goals
1. Determine whether `Ask HN` or `Show HN` posts receive more comments on average.
2. Investigate whether the time of posting influences the number of comments.

## Files Included
- `Exploring Hacker News Posts.ipynb`: Jupyter Notebook containing the code and analysis.
- `hacker_news.csv`: Dataset used for the analysis.

## Tools Used
- **Python:** For data manipulation and statistical analysis.
- **CSV Module:** To process the dataset.

## Dataset
The dataset was reduced from its original size (300,000 rows) to ~20,000 rows by:
- Removing posts with no comments.
- Randomly sampling the remaining data.

## Insights
- `Ask HN` posts receive more comments on average than `Show HN` posts.
- Posts submitted at specific hours tend to get significantly more engagement.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hacker-news-posts-analysis.git
