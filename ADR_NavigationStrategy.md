# ADR 2: Navigation Strategy for Fishy Bank Expense Tracking App

## Context

A good navigation strategy is critical for the success of a mobile application. To provide user with best navigation experience, it is necessary to decide the Navigation Strategy of our Fishy Bank Expense Tracking App before starting the next User Interface Design phase.

## Decision

The design of the navigation menu items will follow the C.R.A.P. design principes:

- Contrast:
  The navigation menu icons will have sufficient color contrast between the text and background, so that they can be easy to read, especially for those users with accessibilities needs.
- Repetition:
  The navigation menu will use the same color tone, font style, and font size. This could help the menu as well as the app looks consistent, professional, and easier for user to identify the theme.
- Alignment:
  The menu items will have the same alignment with sufficient white spaces in between, which could provide a good visual impression and increase readability.
- Proximity:
  The menu items will be grouped by the app’s functionalities, which enable user to better understand the app features and structure.

After initial analysis, the Fishy Bank Expense Tacking app will have 4 key functional layouts, which can be accessed from 4 main menu icons. The app will use the bottom tab navigation method, there will have 4 fixed icons located at the bottom of the screen. This strategy enables users to access to our app functions quickly and easily, which best fit to our app and matches with our goal. The following is the sample layout:
![SampleLayout](https://raw.githubusercontent.com/cathysunkc/MobileApp/0b0b5b27f4c3b699730ae794c2d8fb5241a2e0ae/sample_layout.png)

## Status

Accepted

## Consequences

By using above navigation strategy, user will find our app interface clean, efficient, and easy to navigate. The navigation menu bar and items will also be responsive to users’ mobile devices.  
This ADR describes the navigation strategy for our Expense Tracking App project which will be developed within relative short timeframe, but not suitable for app project with complex and huge structure.
