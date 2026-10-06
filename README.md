This program is an Ohm's law calculator

Purpose:
    This program reads a voltage and resistance and prints the current I = V/R

Input Format:
    Two numbers separated by a space as (volts ohms)

Build and run
    g++ -std=c++17 -Wall -Wextra -pedantic src/main.cpp -o build/app
    ./build/app
Run the tests with: "bash test.sh"

Example output:
    $ echo "12 4" | ./build/app
    Current: 3 A

Limitations:
    - Rejects zero or negative resistance and non-numeric input with "Invalid input"
    - Only reads the first two values; extra input is ignored
    - No units or formatting control on the output

Debugging reflection:
    The main branch was missing from this repository so I had to create it and set the github repository to use main as the default.