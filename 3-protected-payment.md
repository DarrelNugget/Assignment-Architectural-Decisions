# Architectural Decision Record by Darrel Nguyen and Gabreal Kalaf

  * Scenario 1: Mobile Retail App

  * Decision 3: Payment Protection

  * Date: Oct 7, 2023

## Context 
  The app needs to integrate with various payment gateways to facilitate secure and convenient transactions for customers. The team should select and integrate a suitable payment gateway or a combination of gateways based on security, ease of use, and compatibility with the app's target platforms.

**Options Considered**:
  * Select a payment method that targets only a single payment method like PayPal
  * Select a multi-payment method that targets a wide audience range like Paypal, interact e-transfer venmo etc

**Decision**:
  * The second decision seems like the best option to help with wider payment methods

**Rationale**:
  * Better customer ease of payments with it being more accessible to different people using different payment methods.
  * Better region reach, with some regions only allowing specific online transfers or having specific transfers, helps us gain a wider reach to more people.
  * using a single payment method narrows our customer reach and satisfaction with having limited payment services

**Consequences**:
  * Having a large amount of payment services for our retail app may be complex and time-consuming 
  * May take more time to customize the UI to larger payment methods
  * Potential third-party fees where a transaction may cost extra per transaction type based on the service


**Follow-Up Actions**:
  * Figuring out what payment methods are the most used and trusting
  * Add error handling regarding payment failure, or failure in general whether it server side or user-sided
  * Encryption to help keep user's banking and online information safe when entering details to the application
  * Give constant updates to users regarding new payment changes in the app

