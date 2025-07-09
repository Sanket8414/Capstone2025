# Capstone2025

# Dynamic Parking Pricing System
A real-time parking pricing system that adjusts prices based on demand, occupancy, and various environmental factors using streaming data processing.
## Overview 🚀 
This project implements two dynamic pricing models for parking lots:

**Model 1**: Baseline Linear Model with time-based and occupancy-based pricing  
**Model 2** : Advanced Demand-Based Model with multi-factor pricing algorithm  

The system processes real-time parking data and generates dynamic prices to optimize parking lot utilization and revenue.

## Tech Stack 🛠️
 **Core Technologies**

**Python 3.x** - Primary programming language  
**Pathway** - Stream processing framework for real-time data  
**Pandas** - Data manipulation and analysis  
**NumPy** - Numerical computing  

## Visualization & Analysis

**Bokeh** - Interactive visualization library  
**Google collab** - Development environment

## Data Processing

CSV Processing - Real-time data ingestion  
Streaming Data - Continuous data processing pipeline

## Architecture Flow 📊
**Model 1** : Baseline Linear Model  
Raw Data → Schema Validation → Time Features → Price Calculation → Visualization  
**Model 2** : Demand-Based Model  
Raw Data → Schema Validation → Multi-Factor Analysis → Demand Calculation → Price Optimization → Visualization  

## System Architecture 🧱

 ┌──────────────┐         ┌──────────────────┐     ┌────────────────────────┐
 │ Data Source  │   ─▶   │  Pathway Stream  │─▶   │     Pricing Engine     │
 │  (CSV File)  │         │    Processing    │     │     (Models 1 & 2)     │
 └──────────────┘         └──────────────────┘     └────────────────────────┘
                                                              │
                                                              ▼
 ┌────────────────────┐   ┌───────────────────────┐   ┌────────────────────┐
 │   Visualization    │ ◀ │   Data Enrichment     │ ◀ │    Price Output   │
 │   (Bokeh Plots)    │   │     & Features        │   │      (Dynamic)     │
 └────────────────────┘   └───────────────────────┘   └────────────────────┘


## Files 📁  

**dataset.csv**                   : dataset provided to us and the main file used as the path  
**model1_code**                   : complete code for model 1  
**model2_code**                   : complete code for model 2  
**model1_plot**                   : visualization for model 1  
**model2_plot**                   : visualization for model 2  
**model1_result**                 : output of model 1 used for visualization  
**model2_result**                 : output of model 2 used for visualization  
