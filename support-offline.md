# Architectural Decision Record by Darrel Nguyen and Gabreal Kalaf

  * Decision 1: Offline Mode Support

  * Date: Oct 7, 2023

## Context 
  * The retail company wants the app to support offline mode, allowing customers to browse products and view their order history even when they are not connected to the internet. The app should sync data with the server once an internet connection is available.

**Options Considered**:
  * Implement an offline mode using local servers and data storing
  * Create a lite version that requires no internet access 

**Decision**:
  * We have decided to go with option number 1

**Rationale**:
  * As asked for with the company goal of achieving offline mode to help provide an easier shopping experience, with areas with little to no internet
  * With the offline browsing active, it will help raise customer satisfaction and positivity
  * And once an internet connection is secure it will sync with the app and make sure it is up to date

**Consequences**:
  
  * Extra Development Measures: Adding an offline mode will require a local system which will have additional resources required
  * Extra App Size: The app size will increase because of the local system, which will affect download and installation times.
  * Maintenance: Updating the local system with the live server will require ongoing monitoring.


**Follow-Up Actions**:

  * Develop a local caching system to retrieve and store data while the user is in offline mode.
  * Develop an efficient way to sync data between the local server and the live server.
  * Do testing with offline scenarios, to make sure it runs smoothly and to catch issues and bugs.
  * Notifications when the app switches between offline and online.

    
       