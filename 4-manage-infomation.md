# Architectural Decision Record by Darrel Nguyen and Gabreal Kalaf

  * Scenario 1: Mobile Retail App

  * Decision 4: Infomation Management (Track User Behavior)

  * Date: Oct 7, 2023

## Context 
  The retail company wants to track user behavior, such as product views, purchases, and loyalty program interactions. The team should select an analytics tool or service that provides detailed insights and metrics to help improve the app's performance and user experience.

**Options Considered**:
  * Adding a in house translation software
  * Using a third-party platform to translate, such as Google Analytics


**Decision**:
  * The option that we decide to go with is option two using a third-party platform

**Rationale**:
  * Google is already well well-known and widely used platform, as it offers many features and integrations
  * It allows real-time tracking, provides customizable reports, and many more
  * It user friendly and it is really easier to set up and use effectively
  * Using a third-party makes it so that the company does not have to put resources into developing the software, which allows in reduce of cost

**Consequences**:
  * Third-party ongoing cost
  * Data is stored with Google, which could have some privacy problems


**Follow-Up Actions**:
  * Start the integration into our applications
  * Update the privacy policy to inform users of the data being used
  * See the cost associated with the third-party, to make sure it fits the budget
