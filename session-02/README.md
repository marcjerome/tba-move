# Session 2: Setting Up the Move Workspace & Building Your First Smart Contract

## 🎯 Objectives

By the end of this session, you will:

- Set up a complete development environment for Move
- Understand the basic syntax and language constructs of Move
- Build, compile, and test a basic Move smart contract
- Explore Move modules, resources, and functions

## 📖 Lesson Overview

This session is focused on getting hands-on with Move development. You will start by preparing your workspace, then dive into the syntax and semantics of Move — from variables and functions to structs and modules. Finally, you’ll create and interact with a custom smart contract on a local Aptos network.

Topics covered:

- Setting up the Aptos CLI and Move environment
- Initializing a new Move project
- Understanding Move’s basic language constructs (variables, functions, structs)
- Writing a `Counter.move` smart contract

## 💻 Hands-On Task

Inside the `code/` directory:

- `counter.move` — a smart contract that increments and stores a count
- `Move.toml` and `sources/` — basic Move project setup
- `scripts/increment.move` — script for interacting with the module

### Task Breakdown

1. Set up your Aptos development environment
2. Initialize a new Move project using `aptos init`
3. Create a new module named `Counter` that:

   - Defines a `resource` to store a count
   - Provides public functions to initialize, increment, and view the count

4. Compile and test your module

## 📚 Further Reading

See `reading.md` for:

- Move Book (Official Docs)
- Aptos CLI usage guide
- Move language cheat sheet

## 📝 Homework

1. Modify the `Counter` module to allow resetting the count.
2. Add a new function that allows incrementing by an arbitrary value.
3. Try creating a second module named `Greeter` that stores and displays a greeting message.
