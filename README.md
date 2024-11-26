# API exercise

1. /add returns the sum of the array
postman test (in body) 
{"array": [1,2,3]}

it returned 6

2. /product returns the product of the array
postman test (in body) 
{"array": [1,2,3]}

it returned 6

3. /evens returns an array of all even numbers of the original array
postman test (in body)
{"array": [1,2,4,3,2]}
it returned array with 2,4,2

4. /min and /max should return the min/max number of the array, respectively
postman test (in body)
{"array": [1,2,4,3,2]}

min returned 1
max returned 4

5. /sort should take an additional boolean parameter ascending in the request JSON, and return the correctly sorted array of numbers
postman test (in body)
{
    "array": [3, 1, 4, 1, 5, 9],
    "ascending": true
}

it returned array with 1,1,3,4,5,9

6. /target should take an additional number parameter target , and return whether there are two numbers in the array that sum to target
postman test (in body)
{"array": [3, 1, 4, 1, 5, 9],
    "target": 9}

it returned yes
