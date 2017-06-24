# Ultimo Tres

## Table of Contents
- [Introduction](#introduction)
- [Architecture](#architecture)

## Introduction

Ultimo Tres is going to be one of the best soccer game data visualization platform.

## architecture

### Data Collection
The data collection workflow will be done with scripts which invokes service calls to a NodeJS application.

The data collection workflow will be done on a periodic time basis, (e.g. every Tuesday after game day).

### Data Persistence
All collected data will be stored in NoSQL database, (e.g. AWS DynamoDB).

### Data Visualization
Data visualization will be done with Grafana.

### Prediction
Prediction will needs some data analysis and even machine learning.
