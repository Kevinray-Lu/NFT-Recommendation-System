# NFT-Recommendation-System

Trojans Online Resource Exchange Platform is a web application designed to promote convenience on USC campus-wise second-hand product information sharing. It allows users to post and view second-hand items, manage their items, and track their status. It also provides useful USC links and a friendly user interface.

## Table of Contents

- [Trojans Online Resource Exchange Platform](#trojans-online-resource-exchange-platform)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Datasets](#datasets)
  - [Files](#files)
  - [User Interface Screenshots](#user-interface)

## Features

- User specific NFT recommendation (SVM & K-Means)
- Cold Start integration (user similarity computation) 
- User Interface Prototype
- Trending product recommendation
- Price Filtering

## Datasets

1. NFT historical sales dataset:
- https://www.kaggle.com/datasets/francescofalleni/nft-historical-sales

2. User clicking history dataset (from past opensource project of RMDS):
- https://github.com/GRMDS/User_Recommender/blob/main/match_df.csv

3. Users feature dataset: 
- https://data.world/technology/stack-overflow-developer-survey


## Files

- `NFT_Recommendation_System.ipynb`: Coding file for  NFT recommendation, implements data preprocessing, Dimensionality Reduction (PCA & SVD), Data Normalization & Standardization, and Machine Learning Algorithms to recommend groups of NFTs from selected datasets. NFT grouping method using SVM achieved 98% accuracy. This file also contains two user cases for reference.
- `NFT_Rec_Sys_Project_Report.pdf`: This report contains detailed design of the system and relative information of project management(e.g. Agile Development, Lean Six Sigma, Process Mapping, etc.). 


## User Interface

Below shows screenshots of User Interface demo, please contact developers for the online interactive prototype
- Recommendation page for user 2052, including price filter, search bar, trending products and recommended products
<img src="https://github.com/Kevinray-Lu/NFT-Recommendation-System/blob/main/demo_pics/user%202052%20recommendation.png" style="width:50%">
- User profile page for user 2052
<img src="https://github.com/Kevinray-Lu/NFT-Recommendation-System/blob/main/demo_pics/user%20profile.png" style="width:50%">
- Useful links page, connects to relative NFT websites
<img src="https://github.com/Kevinray-Lu/NFT-Recommendation-System/blob/main/demo_pics/useful%20links%20page.png" style="width:50%">
- FAQ page
<img src="https://github.com/Kevinray-Lu/NFT-Recommendation-System/blob/main/demo_pics/FAQ%20page.png" style="width:50%">
- RMDS page, introduces out stakeholder
<img src="https://github.com/Kevinray-Lu/NFT-Recommendation-System/blob/main/demo_pics/RMDS%20page.png" style="width:50%">
