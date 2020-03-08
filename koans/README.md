# Quick Recap notes

## Storage & Databases

## Cloud Pub/Sub

## Cloud DataProc

## Cloud BigTable

- Only 4 clusters per BigTable instance are allowed

- Make sure row-key doesn't trigger full-table scan

- Use keyVisulizer tool to identify hot-spots and consider chnaging how the row-key distributes rows among clusters

- Tablets are stored on google colossus, but a node has a limit on how much a storage it can process.

- More notes..

## Cloud BigQuery
