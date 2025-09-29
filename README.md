# TCR Refactoring Kata in Golang

This repository contains all the code for The Engineering Coach YouTube tutorial on using Test && Commit || Revert (TCR) for Refactoring.

## What You'll Learn

  - How to apply the disciplined TCR workflow to complex, existing code.
  - A step-by-step application of the Untangling Conditionals Kata, originally created by Tom Oram.
  - How the automatic commit or revert mechanism of TCR enforces small, safe refactoring steps, minimizing the risk of introducing new bugs.
  - Practical Golang techniques for simplifying deeply nested conditional logic.

## The Challenge: Untangling Conditionals
This project starts with tangled logic, and the goal is to refactor it safely. The TCR methodology is the perfect tool for this, as it guarantees that your code remains working and tested after every successful change.

## The Video

To see the full demonstration of the TCR refactoring workflow and watch the solution to the Untangling Conditionals Kata, check out the video on YouTube.

Watch the Refactoring with TCR video here!

[![Episode 011 Testify](https://img.youtube.com/vi/8w-0rOG5f5E/0.jpg)](https://www.youtube.com/watch?v=8w-0rOG5f5E)

## Getting Started

To run the code and follow along with the video, you will need to have Golang installed. The project uses the native Go testing package.

Clone the repository:

```shell
git clone https://github.com/the-engineering-coach/026-TCR-Refactoring
cd 026-TCR-Refactoring
```
Run the tests (to verify the starting state):

```shell
go test ./...
```

## About The Engineering Coach

The Engineering Coach is a YouTube channel dedicated to helping software engineers and engineering managers improve their skills and craft. We provide practical advice and tutorials on topics like TDD, BDD, Refactoring, and Software Architecture.

## Let's Connect
For more software engineering tutorials and coaching, subscribe to The Engineering Coach on YouTube. You can also connect with me on Bluesky or Mastodon.

  - YouTube: [https://www.youtube.com/c/TheEngineeringCoach](https://www.youtube.com/c/TheEngineeringCoac)
  - Mastodon: [https://mastodon.social/@braddle](https://mastodon.social/@braddle)
  - Bluesky: [https://bsky.app/profile/braddle1.bsky.social](https://bsky.app/profile/braddle1.bsky.social)
  - LinkedIn: [https://www.linkedin.com/in/mark-bradley-engineering-coach/](https://www.linkedin.com/in/mark-bradley-engineering-coach/)
