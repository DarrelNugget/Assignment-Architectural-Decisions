# Architectural Decision Record by Darrel Nguyen and Gabreal Kalaf

  * Scenario 1: Mobile Retail App

  * Decision 6: Support Multiple Languages

  * Date: Oct 7, 2023

## Context 
  The retail company plans to expand its customer base internationally. The app should support multiple languages and adapt to various cultural preferences. The team needs to implement localization techniques and decide on the appropriate localization framework or libraries.

**Options Considered**:
  * Develop a custom localization solution
  * Use a popular localization library/framework

**Decision**:
  * We decided to go with option two to use a popular library/framework

**Rationale**:
  * Allows to support multiple languages and supports localization
  * Some libraries/framework would support interpolation, pluralization
  * Reduce development time 

**Consequences**:
  * Would need to set the libraryframework
  * maintaining multiple language files may require ongoing resources
  * Maintaining the user interface to ensure culturally sensitive in different languages


**Follow-Up Actions**:
  * Setup the library/framework into the system
  * Select which languages to support
  * Figure out usability and cultural sensitivity testing to make sure the app is good for everyone
