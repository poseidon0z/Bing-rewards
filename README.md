# Bing Rewards

A program made to learn about automation risks in reward systems made to bring users to websites.

## The reward system

This works for microsoft rewards, where Microsoft rewards users with points for performing a certain number of searches using their search engine - Bing.
One of the ways to get points is to search 30 different things on Bing.

## How the automation works

The automation uses simple code written in C++ for doing the following steps:

1. Choose a random word from a list of 1000 most common words in the English language
1. Open the results for the bing search for the particular word, using a link generated within the script itself.

This repeates 30 times, with a delay between each to complete the daily requirement.
The delay between each search is varied to prevent detection of the automation.

## Requirements for using the search

A system running windows, to be able to run the exe file.
An internet connection.
The user must be logged in to their microsoft rewards account in their default browser.

## How to use for mobile searches?

Use an extension that can change your browser's user agent to a mobile browser, and run the same exe again to get your mobile searches completed too!
