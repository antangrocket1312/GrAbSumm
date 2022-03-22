# GrAbSumm

# Opinion summarization using graph-based method

## Introduction
This repo contains sample dataset of Vietnamese public opinion used in the GrAbSumm - Graph-based Abstractive Summarization framework

## Summarization Data Documentation
- Locate to [/sample_topics](/sample_topics) directory for preview of sample data corpus utilized for algorithm description and evaluation in the paper. The directory contains a sample of 8 topic-clustered documents of public opinion from VnExpress (Car) and TripAdvisor (4 documents per data source).
- Download the [zip file](summarizer-data.zip) for full reference of user opinion datasets collected from VnExpress (Car) and TripAdvisor. The zip file contains:
    - /topics: This directory contains the topic-clustered documents used for summarization demonstration of GrAbSumm. The documents contain sentences of user comments clustered 
    into corresponding topics by SBM from the two sources (VnExpress (Car) and TripAdvisor)
    - /summaries-gold: This directory contains human composed summaries used as the reference for the evaluation of the GrAbSumm summarization technique describe in the paper. The directory has directories of selected topic documents which contain short gold-summaries composed by three human-summarizing experts.