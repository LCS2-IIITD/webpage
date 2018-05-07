---
title: Retweet Us, We Will Retweet You


<!-- notitle: true -->

description: |
 Spotting Collusive Retweeters Involved in Blackmarket Services	

people:
  - profx
  - grad-a
  - ugrad-a
  - ugrad-b
layout: project
last-updated: 2017-04-11
---

<!-- Some preliminary text. -->

## Abstract

Twitter has increasingly become a popular platform to share news and user opinion. A tweet is considered to be important if it receives high number of affirmative reactions from other Twitter users via <b>Retweets</b>. Retweet count is thus considered as a surrogate measure for positive crowd-sourced reactions -- high number of retweets of a tweet not only help the tweet being broadcasted, but also aid in making its topic trending. This in turn bolsters the social reputation of the author of the tweet. Since social reputation/impact of users/tweets influences  many decisions (such as promoting brands, advertisement etc.), several blackmarket syndicates have actively been engaged in producing fake retweets in a collusive manner. Users who want to boost the impact of their tweets approach the blackmarket services, and gain retweets for their own tweets by either paying money (Premium Services) or by 
retweeting other customers' tweets. Thus they become customers of blackmarket syndicates and engage in fake activities. Interestingly, these customers are neither bots, nor even fake users -- they are usually normal human beings; they express a mix of organic and inorganic retweeting activities, and there is no synchronicity across their behaviors.

In this paper, we make a first attempt to investigate such blackmarket customers engaged in producing fake retweets. We collected and annotated a novel dataset comprising of customers of many blackmarket services and characterize them using a set of 64 novel features. We show how their social behavior differs from genuine users. We then use state-of-the-art supervised models to detect four types of customers (bots, promotional, normal) and genuine users. We achieve a Macro F1-score of <b>0.87</b> with SVM, outperforming four other baselines significantly. We further design a browser extension, <b>SCoRe</b> which, given the link of a tweet, spots its fake retweeters in real-time. We also collected users' feedback on the performance of <b>SCoRe</b> and obtained 85% accuracy.
