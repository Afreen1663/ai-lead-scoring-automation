# AI Lead Scoring Automation (n8n + OpenAI)

## Overview

AI-driven lead scoring and automation pipeline integrating OpenAI and Google Sheets via n8n.

## Workflow

1. Reads leads from Google Sheets
2. Sends lead data to OpenAI
3. Generates:

   * Lead Score
   * Industry
   * Business Need
   * Recommended Action
4. Writes results back to a new Google Sheet

<img width="578" height="167" alt="image" src="https://github.com/user-attachments/assets/722702c2-8fa3-42c1-a901-3e413e28550f" />

## Input

The input file that is the Google Sheet "leads" contains 20 sample lead entries, each representing a potential customer with details such as Name, Email, Company Name, Job Title, and a Message describing their business needs or interest in services.

<img width="505" height="306" alt="image" src="https://github.com/user-attachments/assets/2b002901-54b4-4d9d-9048-19558c0bfb07" />


## Tools Used

* n8n (workflow automation)
* OpenAI API (Credits were purchased for 5$ for the implementation of workflow)
* Google Sheets API

## Features

* Automated lead qualification
* AI-powered recommendations
* Scalable workflow design

## File

* `workflow.json` → n8n workflow export

## Ouput 
Your output will be reflected in your Google Sheets as shown below.

<img width="742" height="305" alt="image" src="https://github.com/user-attachments/assets/da04f5de-b368-465b-8778-98c4e098db16" />

## How to Use

1. Import workflow into n8n
2. Add your OpenAI API key
3. Connect Google Sheets
4. Run workflow

## Use Case

Sales teams can prioritize leads and improve conversion rates using AI insights.

## Python vs JS
Here for this project we used JavaScript because this task was relatively simpler and therefore Python was not used as n8n is a JavaScript-based automation tool, making JavaScript more suitable for seamless integration and faster workflow execution.
