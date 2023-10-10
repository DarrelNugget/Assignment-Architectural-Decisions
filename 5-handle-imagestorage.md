# Architectural Decision Record by Darrel Nguyen and Gabreal Kalaf

  * Scenario 1: Mobile Retail App

  * Decision 5: Image Storage Management

  * Date: Oct 7, 2023

## Context 
  The app will display product images, which may vary in size and resolution. To ensure optimal performance, the team needs to decide on an image storage solution and implement image optimization techniques such as caching, lazy loading, and compression.

**Options Considered**:
  * Store the images on a content delivery network(CDN)
  * Store the images on a company server

**Decision**:
  * We decided to pick option one and store images on the content delivery network

**Rationale**:
  * Using CDN allows fast and reliable delivery across the world
  * CDN has many servers across the world, which allow improved speeds and reduced latency
  * CDN is well designed to handle large amounts of data, so in the future, we don't have to worry about downtime
  * We would not use the company server because it would cause too much resources into developing the company server
  * Having the images put onto the company server would also cost a increase in traffic causing a decrease in efficiency 


**Consequences**:
  * Initial setting up with the CDN company is required
  * Ongoing cost, cost is charged for service 
  * Required management on chase expiration to make sure all images are served


**Follow-Up Actions**:
  * Start the setup with CDN
  * Check on the ongoing cost to make sure that it fits the budget