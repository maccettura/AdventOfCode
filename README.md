# AdventOfCode
Base .NET Core project for Advent Of Code solutions

## To use

Each day's solution will be implemented in the `Solution` class located in each day's respective folder. Each solution has two parts (methods) and they will return a string.

Solution inputs are in the Resources.resx file, the keys are already there just replace the value with your own input.  The `BaseSolution` abstract class has a `GetResourceString()` method that will return the input as a string for you.

To run, just run the `AdventOfCode.SolutionRunner` this will automatically iterate through all 25 days, giving both parts of the solution for each day (or displaying nothing if the solution has not been implemented).
