# 3Chan Project Plan
## Product Vision
3chan is an ImageBoard that allows users to create posts about any topic and comment on them anonymously, so creating an account is not required.

## Success Metrics
Development Time: The first iteration of the project is completed by August 20, 2026.
Load Time: Page load speed is under two seconds.
Publication Success Rate: The percentage of successful posts must be greater than 95%.
Image Size Limit: Images can not exceed 5 mb of space.
Text Character Limit: The number of characters in each post must be less than 256.

## Product Backlog
### Epic 1. Post Management
#### Enabler Story (Technical) 1.1: Setting up the Stack
Configure the Linux + Apache + MariaDB + PHP + Git stack

**Acceptance Criteria**:
* Create entity-relationship diagram
* Create the ImageBoard database
* Set up the working environment, separating frontend and backend into distinct folders
* Set up the github repository with the project name

#### Story (Functional) 1.2: Create a Post
As a user, I want to be able to create a post on any topic of my choice, including an image and text within it

**Acceptance Criteria**:
* Each post must have a unique identifier
* A unique local hash must be created for the user and associated with their posts
* The text, date, and image path must be stored
* Database Fields: Create the posts table with the associated hash

#### Story 1.3 (Functional): Delete a Post
As a user, I want to be able to delete the posts I have created

**Acceptance Criteria**:
* Use the user's unique local hash to delete the posts associated with it

## Roadmap
Version 1.0 of the project is scheduled for completion during the first sprint, running from August 13, 2026, to August 20, 2026.