# Understanding n8n (in simple terms)

n8n is a workflow automation tool that helps you connect different apps, systems, and APIs to reduce manual work.

Instead of doing repetitive tasks by hand (copying data, sending updates, checking systems), n8n lets you build workflows where:

- Something happens (a trigger)
- Data is collected or received
- Logic is applied (filtering, conditions, transformation)
- An action is performed automatically (message sent, record created, etc.)

You can think of n8n as a way to design “if this happens → do that” systems using building blocks.

---

## The core idea behind n8n

n8n is built around **workflow automation**.

A workflow is a chain of steps where each step is called a **node**.
Nodes pass data to the next step, and together they create an automated process.

At its core, n8n helps you separate automation into clear pieces:

## 1. Trigger – What starts the workflow?
A trigger is the event that starts an automation.

Examples:
- A user submits a form
- A webhook is received
- A schedule runs every day
- A manual test run is started

In n8n, the trigger node is the entry point of the workflow.

---

## 2. Action – What should happen next?
Action nodes perform work, such as:

- Sending a Slack message
- Creating a Google Sheet row
- Calling an API
- Creating a ticket in a support tool
- Updating a database record

This is the part where the workflow produces a real outcome.

---

## 3. Data flow – What information moves through the steps?
Workflows are not only about actions — they’re also about data.

Each node produces output, and that output becomes input for the next node.

Examples of what data might flow through n8n:
- user email addresses
- order IDs
- support ticket details
- webhook payloads
- API responses

Understanding inputs/outputs is key to debugging and scaling workflows.

---

## 4. Logic – What decisions should the workflow make?
Real workflows need logic, such as:

- Only notify the team if a request is high priority
- Send different messages depending on country or region
- Route requests differently for users vs admins
- Stop the workflow if required fields are missing

In n8n, this is done using nodes like:
- IF
- Switch
- Merge
- Filter patterns
- Basic transformations

This is where workflows start to feel like product systems rather than simple automations.

---

## Why this matters for a technical Product Manager

For a technical Product Manager, n8n is useful because it helps build fluency in:

- How systems exchange data
- How API-based integrations work
- How product operations can be automated
- How reliability and edge cases affect workflows
- How to prototype automation before engineering investment

Even when a workflow isn’t meant to be “production-grade,” building it helps a PM think more clearly about:

- dependencies
- failure points
- ownership
- scalability
- user experience across systems

---

## This repository’s approach

This playground uses n8n as a learning tool.

Projects are designed to show progressive understanding:

- starting from core concepts
- moving into simple workflows
- then building toward real operational use cases
- and finally introducing reliability and scaling considerations

The focus is on clarity and reasoning, not complexity for its own sake.
