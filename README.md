# Estimating-Online-Site-Github-Statistics

## Introduction
In this individual project, the task was to estimate the total number of valid users on GitHub using GitHub APIs. The GitHub user IDs are assigned incrementally, starting from 1. However, some IDs may be missing if users have deleted their accounts. Approximately 5% of the user IDs from 1 to 1000 were missing. Due to the limitations of the GitHub API, it was not possible to download all IDs and count the missing ones directly. Instead, a sampling method needed to be employed to estimate the total number of valid users with an unbiased estimator.

## Objective
The main objective of this project was to develop a sampling/estimation method to accurately estimate the total number of valid users on GitHub. The method needed to be unbiased, and its correctness needed to be demonstrated through evaluation results.

A sampling method was employed to select a subset of GitHub user IDs. These sampled IDs were then used to estimate the total number of valid users on GitHub. The sampling process was designed to ensure unbiased estimation.


