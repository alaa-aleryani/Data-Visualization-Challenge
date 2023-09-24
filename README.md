# Data Visualization Challenge

In this challenge, suppose that I've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, I've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked us with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked us for a top-level summary of the study results.

 - First, we cleaned the data, some mice have duplicated timpoints such as the mouse with ID ('g988'), which has multiple records from the same day, each record has different "Tumor Volume (mm3)" record; thus, we removed that mouse from the analysis, so we get accurate results of the clinical study.