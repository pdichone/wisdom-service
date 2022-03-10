# Wisdom-service

Simple express API to demonstrate basic routes that can be run in a container.

## What Does it Do?

This container starts a webserver on port 80, and it has three endpoints:

- `/` route that shows a simple `It Works.`
- `/greeting` route that shows a simple `Hello friend!`
- `/wisdom` route that shows a random quote (feed from a list of quotes).

## Usage

To start this container, map local port 80 into the container.
