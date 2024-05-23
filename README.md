# Monty Hall Problem Simulation

## What is the Monty Hall Problem?

The Monty Hall Problem is a famous probability puzzle based on a game show scenario. Here’s how it works:

1. **Setup:** You are a contestant on a game show. There are three doors. Behind one door is a car (the prize), and behind the other two doors are goats.
2. **First Choice:** You pick one of the three doors.
3. **Host's Action:** The host, who knows what’s behind the doors, opens one of the two remaining doors, revealing a goat.
4. **Second Choice:** You are then given the option to stick with your original choice or switch to the other unopened door.
5. **Outcome:** The question is: should you switch your choice or stay with your initial pick to maximize your chances of winning the car?

Counterintuitively, switching doors gives you a 2/3 chance of winning the car, while staying with your initial choice only gives you a 1/3 chance.

## How This Script Works

This PHP script simulates the Monty Hall Problem to demonstrate the probabilities involved. You can specify the number of simulation runs, the number of doors, and the switching strategy (always switch, never switch, or switch randomly). The script will then output the results, showing the win and loss rates for the specified conditions.

### Key Features:
- **Customizable Runs:** Simulate the problem for any number of runs between 1 and 1,000,000.
- **Variable Doors:** Simulate with any number of doors between 3 and 100.
- **Switching Strategies:** Test different strategies (always switch, never switch, random switch).

## Why Use This Script?

Understanding the Monty Hall Problem is a great exercise in probability theory and can help enhance your critical thinking and decision-making skills. By simulating the problem multiple times, you can see the statistical evidence of why switching doors increases your chances of winning.

## How to Use It

### Prerequisites

- **PHP**: Make sure you have PHP installed on your machine. You can download it from [php.net](https://www.php.net/).

### Running the Script

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/33Piter/the-monty-hall-problem.git
   cd the-monty-hall-problem
   ```

2. **Run the Script with Options:**
   You can provide options directly via the command line:
   ```sh
   php montyHall.php --runs=1000 --doors=3 --switch=always
   ```

3. **Interactive Mode:**
   If you don’t provide options, the script will prompt you to enter them interactively:
   ```sh
   php montyHall.php
   ```

### Options

- **--runs:** Number of runs to simulate (1 to 1,000,000). Default is 1000.
- **--doors:** Number of doors (3 to 100). Default is 3.
- **--switch:** Switching strategy (`always`, `never`, `random`). Default is `always`.

### Example Commands

- **Always Switch Strategy:**
  ```sh
  php montyHall.php --runs=5000 --doors=3 --switch=always
  ```

- **Never Switch Strategy:**
  ```sh
  php montyHall.php --runs=1000 --doors=3 --switch=never
  ```

- **Random Switch Strategy:**
  ```sh
  php montyHall.php --runs=10000 --doors=5 --switch=random
  ```

Enjoy exploring the probabilities of the Monty Hall Problem and see for yourself why switching is the better strategy!