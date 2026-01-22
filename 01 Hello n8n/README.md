# Hello n8n

This project is the first hands-on workflow in this playground.

It introduces the most basic n8n building blocks:

- A **trigger** to start the workflow
- A **Set node** to create and structure sample data
- A **final processing step** to confirm the workflow executed successfully

The goal is not to build a useful automation yet, but to build confidence
in how workflows execute and how data moves between nodes.

------------------------------------------------------------------------

## What this project demonstrates

- How a workflow is triggered
- How nodes pass data forward
- How to inspect node outputs during execution
- How to structure information into consistent fields

------------------------------------------------------------------------
## How to use this project

1. Open **n8n**
2. Go to **Workflows**
3. Select **Import from File** (or **Import workflow**)
4. Import the workflow file:   **`01-hello-n8n/workflow.json`**
5. Click **Execute Workflow**
6. Inspect the node outputs to see how data moves from one step to the next

------------------------------------------------------------------------

## Output

This workflow produces a simple payload such as:

- `name`
- `role`
- `learning_goal`
- `timestamp`
- `message`

This becomes the foundation for future projects that work with APIs, logic,
and real integrations.
