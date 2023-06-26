<h1 align="center">
    Omnius
</h1>
<p align="center">
  <strong>A lightweight event bus framework. You can easily build a powerful event bus in your project.</strong>
</p>

## What is Omnius?

Omnius is a lightweight event bus framework. You can easily build a powerful event bus in your project.

## Features

- Establishes a powerful event bus system with a simple and straightforward syntax
- Enables a callback function to subscribe to multiple events at once
- Supports various application scenarios involving events, such as asynchronous and synchronous workflows
- Enables various syntax writing modes including lambda expressions, callback functions, and decorators
- Provides publisher dispatch callback management, which can help to manage and coordinate the flow of events within the system.


## What is Event Bus?

Event bus is a software architecture pattern that enables loosely coupled communication between applications and
services in a distributed system. It provides an event-driven mechanism whereby applications and services communicate by
sending and receiving events without directly depending on each other's implementation details. The event bus typically
consists of three core components: event publisher, event subscriber, and event bus. The event publisher is responsible
for generating and publishing events, the event subscriber is responsible for subscribing to the events they are
interested in and receiving and handling them when they occur, and the event bus acts as middleware that facilitates the
transmission and handling of events. By using the event bus, applications and services can collaborate more flexibly, as
well as have better scalability and maintenance.

## Differences between Event Bus and Pub/Sub pattern

Event bus and the publish-subscribe pattern are both event-driven communication patterns that have some similarities but
also some differences.

**Similarities**

- Both are event-driven communication patterns.
- Both enable loosely coupled communication between applications and services in a distributed system.
- Both allow applications and services to communicate via events without directly depending on each other's
  implementation details.
- Both can improve the scalability and maintainability of applications and services.

**Differences**

- The publish-subscribe pattern is typically unidirectional, with the publisher only publishing events and subscribers
  only subscribing to and handling events of interest. The event bus is typically bidirectional and allows for two-way
  communication between publishers and subscribers.
- In the publish-subscribe pattern, the connection between publishers and subscribers is typically static and determined
  at runtime. Conversely, the connections in an event bus are typically dynamic and new subscribers can be added or
  removed dynamically during runtime.
- In the publish-subscribe pattern, events are typically sent directly to subscribers. In the event bus, publishers send
  events to the bus and the bus distributes and handles the events to relevant subscribers.
- The publish-subscribe pattern is typically a one-to-many relationship between publishers and subscribers, while an
  event bus typically represents a many-to-many relationship."

