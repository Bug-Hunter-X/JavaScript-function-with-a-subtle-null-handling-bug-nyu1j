# JavaScript function with a subtle null handling bug
This repository demonstrates a common but subtle bug in JavaScript related to null handling. The `foo` function is designed to add two numbers, but it incorrectly handles the case where one of the inputs is 0, treating it as null. The solution improves the null check to address this issue.

## Bug Description
The function `foo` adds two numbers. It correctly handles null inputs by returning null. However, it also incorrectly treats 0 as null, leading to unexpected behavior when 0 is passed as an argument. 

## Solution
The solution modifies the conditional check to explicitly test for both null and 0, ensuring that the addition happens correctly even when 0 is an input.