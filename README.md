# Final Project - Sequence

## Introduction

This repository contains the final project for the Software Engineering course, which involves developing a distributed program for playing Sequence games in a user-versus-user mode.

## Objective

Develop a program that supports Sequence games between two users, using a distributed client-server architecture.

## Game Rules

The rules of the Sequence game can be found on the [Copag website](https://copag.com.br/blog/detalhes/sequence).

## Program Architecture

The program is based on a distributed client-server architecture, implemented in Python together with the [TKinter](https://docs.python.org/3/library/tkinter.html) library. It uses DOG as support for distributed execution.

## Development Premises

- The program must be implemented in Python.
- The program must use DOG (Distributed Objects in Python) as support for distributed execution.
- In addition to the source code, this repository contains a project specification based on UML (Unified Modeling Language), version 2.

## Repository Structure

- `src/`: Contains the program's source code.
- `docs/`: Contains the project documentation, including the UML specification.
- `README.md`: This documentation file.

## Installation and Execution

1. Clone this repository:

    ```sh
    git clone https://github.com/vvc-git/engenharia-de-software.git
    cd engenharia-de-software
    ```

2. Create a virtual environment and activate it:

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the dependencies:

    ```sh
    pip install -r requirements.txt
    ```

4. Execute:

    ```sh
    python src/main.py
    ```
