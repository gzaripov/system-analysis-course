# Make cats free again

Before I brought you to the system design lets cover up some details on what we are going to build.

## The product

We need to create the platform which will allow cats to hire workers to perform their chores.

### Cat client user flow

1. Post a work order with all details by using our platform
1. Wait for worker being assigned to a work order
1. Receive a notification that asignee is found and a work order is scheduled
1. Wait until job is done
1. Considers a report of completed work
1. Accept or reject a order
1. Pay for all orders once a week

### Cat worker user flow

1. Pass testing to become a worker
1. Wait for an order
1. Receive a notification that work is found and scheduled
1. Come to specified place and perform a work
1. Provide report with before/after photos
1. Wait for a approval or rejection
1. Receive money for orders (or pay a fine) once a month

### Administrator flow

- edit on order parameters in admin panel
- randomly check an order to ensure quality
- call the client to ask a feedback
- investigate failed/cancelled orders
- reward workers
- fine workers

## Requirements

[Requirements details are in separate file](./requirements.md)

## Iteration 1

[Lesson 1](./lesson-1.md)

## Iteration 2

[Lesson 2](./lesson-2.md)