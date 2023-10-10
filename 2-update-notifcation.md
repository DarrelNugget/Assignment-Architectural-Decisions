# Architectural Decision Record by Darrel Nguyen and Gabreal Kalaf

  * Scenario 1: Mobile Retail App

  * Decision 2: Notification Updates

  * Date: Oct 7, 2023

## Context 
  The retail company wants to send push notifications to customers to notify them about order updates, new product arrivals, and exclusive offers. The app should integrate with a push notification service to handle the delivery of notifications.

**Options Considered**:
  * Build specific push notifications tailored to the app
  * Use third-party push notification software

**Decision**:
  * We have decided that option 2 would be best with the third-party push notification software

**Rationale**:
  * Using a third-party notification service is more time and cost-effective.
  * Third-party already have the infrastructure, expertise, and reliability to deliver messages
  * Third-party services can handle large-scale traffic, to ensure a seamless experiences
  * building our own notification software would be too resource and time consuming

**Consequences**:
  * Dependency: On third-party software and depending on them to stay live and not go down when needed, and not being able to do much when it occurs
  * Subscription/money: With the third-party notifications will most likely have to through with a paid subscription to ensure we maintain their service


**Follow-Up Actions**:
  * find a reliable and well-known third-party notifications software
  * Set up notification templates for how they should appear to customers as well as how they should appear for different events
  * Implement user preference and usability into them so it is as simple and efficient as possible with delivering constant messages and updates