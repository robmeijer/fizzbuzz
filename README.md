# Fizz Buzz
This exercise is based on a group word game for children, to teach them about division.

Players take turns to count incrementally, replacing any number divisible by three with the word "fizz",
and any number divisible by five with the word "buzz".

## Setup
First, clone the repository to your computer as follows:
```bash
git clone https://github.com/robmeijer/fizzbuzz.git
```

Once it's cloned, change into the new directory, and install the dependencies:
```bash
cd fizzbuzz
composer install
```

## Exercise
The code for this exercise should be placed in `functions/fizz_buzz.php`, in the `fizz_buzz` function.

This function can accept any whole number as the input.

If the input number is a multiple of 3, then the function must return the word 'fizz' as part of the response.

If the input number is a multiple of 5, then the function must return the word 'buzz' as part of the response.

If the input number is neither a multiple of 3, nor a multiple of 5, then the function must return the input.

## Testing
Once the dependencies are installed, the project can be tested by running the automated tests:
```bash
composer test
```
The exercise is complete once all the testcases pass successfully.
