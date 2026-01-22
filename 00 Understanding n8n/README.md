# Understanding n8n

This project introduces **n8n** at a conceptual level.

Before building workflows, it is important to understand what n8n is,
what problems it solves, and how it fits into modern product and
operations environments.

This project contains no executable workflows. Its purpose is to
establish foundational understanding.

------------------------------------------------------------------------

## What is n8n?

n8n is an open-source workflow automation tool that allows users to
connect systems, services, and APIs using a node-based visual interface.

Workflows in n8n are built by chaining together nodes that:

- Trigger an execution
- Fetch or receive data
- Transform or enrich data
- Perform actions in other systems

Each execution follows a defined flow, making automation predictable
and observable.

------------------------------------------------------------------------

## Core concepts

### Workflows
A workflow is a sequence of connected nodes that define how data moves
from one step to the next.

### Nodes
Nodes represent individual actions or logic units, such as:
- Triggers
- API calls
- Data transformations
- Conditional checks

### Triggers
Triggers start a workflow execution. Common examples include:
- Manual triggers
- Webhooks
- Scheduled triggers
- Events from external systems

### Executions
Each time a workflow runs, n8n creates an execution that can be inspected
to understand inputs, outputs, and failures.

------------------------------------------------------------------------

## Where n8n fits in a product context

From a product perspective, n8n is commonly used for:

- Internal tooling and operational automation
- Integrating third-party services
- Prototyping workflows before engineering implementation
- Reducing manual work for product, support, and growth teams

It is especially useful when:
- Systems need to be connected quickly
- Requirements are evolving
- Full custom development is not yet justified

------------------------------------------------------------------------

## n8n compared to similar tools

Compared to no-code automation tools, n8n offers:

- More flexibility in handling data
- Greater control over execution logic
- Self-hosting and extensibility options

Compared to fully custom code, n8n provides:

- Faster iteration
- Visual observability
- Lower setup overhead for many use cases

------------------------------------------------------------------------

## Learning goal of this project

The goal of this project is to:

- Build a mental model of how n8n works
- Understand where automation adds value
- Establish vocabulary and concepts used in later projects

Subsequent projects build on this foundation with hands-on workflows.
