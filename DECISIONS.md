# Decisions

We made thoughtful decisions to ensure our designs are visually appealing, intuitive, and accessible. By considering user needs, aesthetic principles, and technical constraints, we created solutions that enhance the overall user experience and meet our project goals.

## Naming Conventions

File names should be kept as short as possible but should be date, name, version.
Examples:

* 250212-Wealth-Manager-v01.fig
* 260522-Wealth-Manager-v02.fig

## Page Design Status

Chips to be used above right-hand corner of sections

## Sign Off Ready

A component in Figma is considered "signed off" and ready to publish to other designers when it has been reviewed and approved by the relevant stakeholders, usually including designers, developers, and product managers, and is considered to be in a stable state with consistent functionality and visual appearance, with any necessary documentation readily available.

Key indicators that a component is ready to publish:

| Step                  | Description                                                                                                                                      |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Design Review Process | The component has gone through a formal design review process where feedback is gathered and addressed                                           |
| Documentation         | Detailed documentation is created explaining the component's usage, accessibility considerations, and any specific design guidelines             |
| Version Control       | The component is marked as "ready for dev" or a similar status within your design system, indicating it's finalized and ready for implementation |
| Team Alignment        | There is clear communication across the design team that the component is ready for use in live projects                                         |

## How to manage component approval in Figma

| Feature               | Description                                                                                                                                          |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Design System Library | Organize components within a dedicated Figma library and publish only "ready" components                                                             |
| Component Status Tags | Use labels or tags to indicate the current state of components (e.g., "In Progress", "Review", "Approved").                                          |
| Branching Feature     | Utilize Figma's branching feature to create separate development branches for components under refinement, publishing only from the "master" branch. |
| Feedback Mechanisms   | Leverage Figma's commenting and annotation features to provide feedback during the review process.                                                   |

## Changes to designed and live pages

* Once we ship or have major changes, all changes should be branched, even adding a button or text
* Snowflakes stay in CDS Project called BetaNXT Snowflakes
* If a UI pattern is used more than three times, turn it into a reusable UI component.
* If a UI component is used in 3 or more projects/teams, put it in your design system.

## Buttons

* Different buttons have different use cases.
* Border radius 4px

### Primary Buttons

* Primary button is designed for a user to perform the most important task on the page, the “Done” button to show that you have completed the task in this case

### Secondary Buttons

* Secondary buttons are usually the alternative to the primary action. Use secondary buttons for less important actions or for multiple actions that have equal importance.
* It is paired with a primary button. The secondary button serves as the negative action of the pair, such as “Delete,” "Cancel" or “Remove”.
  Examples:

### Client Mode

* Button on card will always be set to Primary Dark Mode. The Card is always in dark mode.
  * Decision made on 5/5/2025
* Example MIC Shareholder Dashboard:

## Charts

### Donut Charts

* Data starts at 12 o’ clock

## Top Navigation Bar

Top level navigation should always link back to main page of that heading

* decision made on 5/5/2025

## Design Screen Sizes

We will develop our designs based on two size options to meet our requirements.

* iPad 1366 x 1024
* Mobile 430 x 932

## Font Family

We have selected the following font family for our design.

* Roboto

## Buttons

* Different buttons have different use cases.
* Border radius 4px

### Primary Buttons

* Primary button is designed for a user to perform the most important task on the page, the “Done” button to show that you have completed the task in this case

### Client Mode

* Button on card will always be set to Primary Dark Mode.  The Card is always in dark mode.
  * Decision made on 5/5/2025

Example MIC Shareholder Dashboard:

### Secondary Buttons

* Secondary buttons are usually the alternative to the primary action. Use secondary buttons for less important actions or for multiple actions that have equal importance.
* It is paired with a primary button. The secondary button serves as the negative action of the pair, such as “Delete,” "Cancel" or “Remove”.
  Examples

## Theming

Our system supports four different color configurations.

### Light Mode

### Dark Mode

### Client Light Mode

### Client Dark Mode

## Client Logo in the Masthead

### Light Mode

* No modification to the logo

### Dark More

* 4px padding around the logo
* 2px border radius
* White fill

### Light Mode

* No modification to the logo

## Color Locations

### MIC Shareholder

#### Primary

#### Secondary

#### Tertiary

### MIC Wealth Manager

#### Primary

#### Secondary

#### Tertiary

## Charts

### Donut Charts

* Data starts at 12 o'clock position

## Top Navigation Bar

* Top level navigation should always link back to the main page of that heading
  * Decision made on 5/5/2025

## AG Grid

* Developers are using it so we must make it work for us
  * Decision made at CDS Meeting  5/14/2025
  * This component must be upgraded manually

## Alert Custom Component

* Corner radius 8px

### Use Case:

* This is to be used when a alert needs to be show
