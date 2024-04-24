# Exploring Hacker News Posts

## Introduction

Welcome to the guided project on exploring Hacker News posts! In this project, we'll analyze a dataset of submissions to the popular technology site Hacker News.

Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") receive votes and comments, similar to Reddit. It's extremely popular in technology and startup circles, and posts that make it to the top of the Hacker News listings can get hundreds of thousands of visitors as a result.

The main goals of this project are to:

- Work with strings, object-oriented programming, and dates and times.
- Analyze the Hacker News dataset to answer the following questions:
  - Do Ask HN or Show HN posts receive more comments on average?
  - Do posts created at a certain time receive more comments on average?

This project will give you hands-on experience with real-world examples, helping you to not only complete it but also to understand the underlying concepts. Feel free to refer to additional lessons if needed, especially if you're new to working with Jupyter Notebook.

## Dataset Overview

The dataset we'll be working with has been reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that didn't receive any comments and then randomly sampling from the remaining submissions. Below are descriptions of the columns:

- `id`: The unique identifier from Hacker News for the post.
- `title`: The title of the post.
- `url`: The URL that the post links to, if it has a URL.
- `num_points`: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes.
- `num_comments`: The number of comments on the post.
- `author`: The username of the person who submitted the post.
- `created_at`: The date and time of the post's submission.

## Project Goals

We're specifically interested in posts with titles that begin with either Ask HN or Show HN. Users submit Ask HN posts to ask the Hacker News community a specific question, while Show HN posts are used to show the community a project, product, or something interesting.

In this project, we'll compare these two types of posts to determine the following:

1. Do Ask HN or Show HN posts receive more comments on average?
2. Do posts created at a certain time receive more comments on average?

