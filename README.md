# AI Lead Scoring Automation (n8n + OpenAI)

## Overview

This project automates lead scoring using OpenAI and stores results in Google Sheets.

## Workflow

1. Reads leads from Google Sheets
2. Sends lead data to OpenAI
3. Generates:

   * Lead Score
   * Industry
   * Business Need
   * Recommended Action
4. Writes results back to a new Google Sheet

## Tools Used

* n8n (workflow automation)
* OpenAI API
* Google Sheets API

## Features

* Automated lead qualification
* AI-powered recommendations
* Scalable workflow design

## File

* `workflow.json` → n8n workflow export

## How to Use

1. Import workflow into n8n
2. Add your OpenAI API key
3. Connect Google Sheets
4. Run workflow

## Use Case

Sales teams can prioritize leads and improve conversion rates using AI insights.
