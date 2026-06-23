# LinkedIn Content Generator using n8n and Airtable

## Overview

This workflow automatically generates LinkedIn posts for topics stored in Airtable.

## Workflow

Manual Trigger
→ Search Airtable Records
→ Loop Over Items
→ AI Agent (Google Gemini)
→ Update Airtable Record

## Airtable Structure

Table: Post Topics

Fields:
- Post ID
- Topic
- Draft Post

## Expected Outcome

The workflow reads all topics with empty Draft Post values, generates professional LinkedIn content using Gemini, and writes the generated content back to Airtable.

## Screenshots

See:
- workflow.png
- airtable-result.png

## Exported Workflow

See:
- linkedin-content-generator.json
