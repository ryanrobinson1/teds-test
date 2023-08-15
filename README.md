# Thought&Function Full-stack assessment

## Instructions

This repo contains two separate projects. This isn't a mono-repo so it's best to open each folder in a separate IDE. We recommend VSCode with prettier and eslint plugins installed.

Both projects contain README files with instructions on how to setup and run locally.

### Before you start
- Create a new Github repo and commit this assessment without any changes.

### Submitting your assessment

- create a PR for **each task where the base is the previous task**
- The first PR's base should be the main branch
- update this README.MD with your total time taken
- Add **sinn1** as a reviewer


- total time taken:** // please fill this in**
  
<br />

## Tasks

In this assessment you will build an appointment booking app by fixing the backend code and implementing the frontend code. Authentication has been removed and you can ignore it for this assessment.

<br />

### Task 1 - Fix the backend

The backend contains unit tests that need to be implemented and e2e tests that are failing because. Your task is to implement the resolver and service logic so that the tests pass.

<br />

- 1a. As a user, I can fetch available slots for all doctors

  - Generate a slot based on a doctor's configured Availability and their existing appointments.
  - Slots should be 15 minutes long
  - You'll need to decide how best to add doctors and their availability to the database for dev and testing purposes

- 1b. As a user, I can book an appointment
  - Slots can only be booked once

<br />

Read core-api/README.md for instruction on how to setup, run, and add migrations.

<br />

### Task 2 - Implement the frontend

Implement the following user stories by continuing the code started in `src/views/appointments`:

- 2a. As a user, I can view available slots and select one

  - The SlotSelector is there to help you render a calendar and slots and shouldn't need modifying but you can if you want or if there's a problem with it.

- 2b. As a user, I can book an appointment and include details with my booking
  - Use react-hook-form to implement the booking form

<br />

For extra marks, make the UI look pretty.

Read webapp/README.md for instructions on how to run the solution and how to use GraphQL Codegen.

<br />

# Review process

## Marking

- For reviewer
  - number of backend unit tests passing
  - frontend integrated with api
  - followed existing patterns
  - introduced or improved patterns
  - introduced or improved utils or helpers
  - UI is clean and follows best practices
  - UI implemented following a clear pattern
  - UX decisions follow best practices
