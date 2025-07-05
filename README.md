# Smart Student Model

## Final Model & Full Pipeline

### Automating Question Validation for Reading Comprehension

**Group Members:** Cathy Hou, James Alexandr Carr, Joanna Walters, Rosa Wu, and Sam Mucyo


## Table of Contents
1. [Introduction](#introduction)
2. [EDA Review](#eda-review)
3. [Model Training](#model-training)
4. [Results Interpretation and Analysis](#results-interpretation-and-analysis)
5. [References](#references)

## Introduction

See full_model.ipynb for full implementation and writeup. 

### Motivation

Our project focuses on automating the validation of multiple-choice questions (MCQs) in both English and Portuguese using the Pirá 2.0 dataset. MCQs are a fundamental assessment tool in education, but creating high-quality MCQs that effectively evaluate student understanding remains challenging. We aim to develop an automated system to evaluate the quality of MCQs, particularly in terms of their dependence on provided passages and their ability to assess comprehension.

The Pirá dataset is a bilingual (Portuguese-English) question-answering dataset focused on topics related to the ocean, the Brazilian coast, and climate change. It consists of scientific paper abstracts and UN report excerpts.

### Significance and Impact

Improving MCQ quality has significant implications for educational assessment, ensuring tests measure comprehension and critical thinking rather than test-taking strategies. Our model could be a valuable tool for educators to validate and improve assessment materials, enhancing learning experiences and evaluation accuracy. Additionally, our project contributes to expanding NLP resources for Portuguese, supporting equitable access to educational technologies across languages.

### Approach

To address this problem, we implemented two models:
- **Context Model**: Takes passage + question + options as input.
- **No-Context Model**: Takes only question + options as input.

We compare the performance between these models to determine if questions truly depend on passage comprehension. If the No-Context Model performs well, it suggests that questions can be answered without reading the passage, indicating potential issues with question quality.

## Setup and Data Loading

Instructions on setting up the environment and loading the data. 

## EDA Review

A brief overview of the exploratory data analysis conducted on the dataset.

## Model Training

Details about the model training process, including the algorithms used and any specific configurations.

## Results Interpretation and Analysis

An analysis of the results obtained from the model, including metrics and visualizations.

## References

Any references or resources used in the project.
