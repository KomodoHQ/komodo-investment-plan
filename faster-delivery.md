# Faster Delivery

_"What are the biggest barriers to faster delivery? How can we deliver faster?"_

## Eliminate Interruptions

### Personal

 - Work from home.
 - Use DND on Slack.

### Business

 - No meeting days.
 - Separate support from feature development team members. 
 - Dedicate team members as "interruptible" vs "not-interruptible".
 - Dedicated "don’t interrupt me" time and allocated time for interruptions during office hours.

### Tool / Product

 - Measure interruptions - Interruption counter? Dash button? 

## Reduce time to review and amend pull requests

### Personal

 - Reduce the size of PR’s
 - Pre-allocated PR review time

### Business

 - Ensure PR is "complete" - checklist of expected content
 - Have a hard limit for the number of "pending" PR’s, and once hit ensure they are reviewed immediately

### Tool / Product

 - Measure time from open PR to review
 - Github tool - Automate elements of PR review, e.g. automate check for README update

## Eliminate time waiting for resources / feedback

### Personal

 - Pre-prepare a list of resources / feedback that is required for each ticket at the start of a sprint

### Business

 - Set deadlines for getting resources / feedback to us. Have a punitive system for handling delays and missing information
 - Ensure all resources and feedback are in one specific place

### Tool / Product

 - Measure the number of times a task was unable to be started due to missing detail

## Stop changing tasks and priorities

### Personal

 - Refuse to change task without approval by management
 - Do not engage directly with the customer work requests on Slack, forcefully redirect the customer to a PM

### Business

 - Prevent customers from being able to mandate changes to tasks / priorities during a sprint - committed delivery


### Tool / Product

 - Measure how many times priorities / tasks change within a sprint

## Get rid of slow development environments, jumping through hoops, lack of existing documentation

### Personal

 - Make sure environments are a 1 line start up 
 - Make sure dependencies are locked

### Business

 - Allocate time to refactor slow development environments
 - Create a separate Github organisation for environments, put them all in there and track and update them separately

### Tool / Product

 - Measure startup times for environments

## Understand the problem from the outside

### Personal

 - Read the proposal before cutting code

### Business

 - Dedicate time for developers to communicate with users

### Tool / Product

 - Have a checklist to ensure questions have been asked, risks have been assessed and unknowns have been identified

## Don't reinvent the wheel

### Personal

 - Pro-actively research solution before cutting code

### Business

 - Dedicated R&D week at the start of development for creating a POA

### Tool / Product

 - Project knowledge base - include docs folders in projects which mention complex items etc

## Stop creating / maintaining overly complex engineered systems

### Personal

 - Ensure the team is consulted when designing new applications
 - Challenge each other to simplify

### Business

 - Set a business end of life for all projects
 - Ensure every project has a maintenance agreement
 - Dedicate time for refactoring as new / simpler solutions become available
 - Setup a regular review for active projects, including AM involvement to suggest improvements, innovations, performance enhancements etc

### Tool / Product

 - Setup time since last review tracker

## Having to (re)learn systems, especially poorly documented or maintained ones

### Personal

 - Ensure to document systems as we go, so that onboarding new members is easier

### Business

 - Where possible, seek to only onboard high-quality brownfield projects. Ensure there is time and a clear process of review to understand the project
 - Have an escape mechanism for projects we are uncomfortable with
 - Ensure there is always team overlap for rotating team members onto a project

### Tool / Product

 - Automated auditing tool to highlight potential issues early


## Worries about breaking other parts of the system

### Personal

 - Make sure to create code with tests
 - Have a method of immediate roll back, with as little impact as possible

### Business

 - Ensure there is an assessment of what might break and why
 - Put in reasonable QA / QC / Testing processes that always cover those elements highlighted
 - Have a review process so that if / when something does break, lessons are learned as to the cause and a check is added to the PR to ensure the circumstance is not repeated

### Tool / Product

 - PR checklist

## Give people space to solve a problem, but give them clear avenues to get immediate support

### Personal

 - Encourage team members to speak up if they need help

### Business

 - Dedicate time to developer isolation
 - Highlight team member creativity and independence when it is observed

### Tool / Product

 - 

## Empower team to take decisions, not have to wait for them

### Personal

 - Take initiative

### Business

 - Highlight who is empowered to take decisions, and on what basis / with regards to what

### Tool / Product

 - 

## Reduce deployment time

### Personal

 - Strive to setup CI / CD with a minimal number of blockers
 - Ensure as much as possible is checked at the PR stage

### Business

 - Consistent deployment procedures
 - Dedicate time to improving pipelines
 - Highlight issues / blockers to third parties in advance
 - Document common failure reasons, and resolve / mitigate in a checklist

### Tool / Product

 - Measure average time from ticket open to ticket close
 - Consistent CI / deployment tool

