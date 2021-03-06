# PHP Interview Exercises · [![Build Status](https://img.shields.io/travis/com/azdanov/php-interview-exercises/master.svg?logo=travis)](https://travis-ci.com/azdanov/php-interview-exercises) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-blue.svg?logo=github)](http://makeapullrequest.com) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?logo=read-the-docs&logoColor=white)](https://github.com/azdanov/questions/blob/master/LICENSE) [![Exercise Count](https://img.shields.io/endpoint.svg?url=https://php-interview-questions-counter.netlify.com/.netlify/functions/count)](./exercises)

A number of exercises to practice whiteboard interview questions in PHP.

Inside `exercises` directory, you can find folders containing the exercises and completed versions.
There are multiple ways to solve each problem, feel free to experiment.

If you are stuck don't be afraid to search online for a pseudo-code algorithm or a solution. Even by copying and later analyzing the solution you will gain lots of experience in problem solving.

Also check out the tests and see what results are expected. Playing around with [Xdebug](https://xdebug.org/) is a plus.

It is useful to actually see how algorithms manipulate data. [Visualgo](https://visualgo.net/en) is a good resource for that.

## Install

1. Clone this repository.
2. Run `composer install`.

## Usage

1. Pick an exercise for example `exercises/ReverseString` and inside `tests/ReverseString/ReverseStringTest.php` delete `static::markTestSkipped();`.
2. Run `./vendor/bin/phpunit` or `./vendor/bin/phpunit-watcher watch` to start tests.
3. Write implementation.

This will allow you to write code and be sure that the solution is correct.

## Problem Solving Patterns

To solve certain problems in the most efficient way many [algorithmic patterns](https://cs.lmu.edu/~ray/notes/algpatterns/) are available.
Such as:
- Frequency Counter
- Multiple Pointers
- Sliding Window
- Divide and Conquer
- Backtracking

And more...

## Suggested Path

- [FizzBuzz](./exercises/FizzBuzz/FizzBuzz.php)
- [Numbers](./exercises/Numbers/Numbers.php)
- [Reverse](./exercises/Reverse/Reverse.php)
- [Palindrome](./exercises/Palindrome/Palindrome.php)
- [MaxChar](./exercises/MaxChar/MaxChar.php)
- [ArrayGroup](./exercises/ArrayGroup/ArrayGroup.php)
- [Capitalize](./exercises/Capitalize/Capitalize.php)
- [Vowels](./exercises/Vowels/Vowels.php)
- [Anagram](./exercises/Anagram/Anagram.php)
- [MaxSubArraySum](./exercises/MaxSubArraySum/MaxSubArraySum.php)
- [Search](./exercises/Search/Search.php)
- [Ladder](./exercises/Ladder/Ladder.php)
- [Pyramid](./exercises/Pyramid/Pyramid.php)
- [Spiral](./exercises/Spiral/Spiral.php)
- [Fibonacci](./exercises/Fibonacci/Fibonacci.php)
- [Events](./exercises/Events/Events.php)
- [Queue](./exercises/Queue/Queue.php)
- [Stack](./exercises/Stack/Stack.php)
- [QueueFromStacks](./exercises/QueueFromStacks/QueueFromStacks.php)
- [Sort](./exercises/Sort/Sort.php)
- [LinkedList](./exercises/LinkedList/LinkedList.php)
- [Tree](./exercises/Tree/Tree.php)
- [BinarySearchTree](./exercises/BinarySearchTree/BinarySearchTree.php)

## Aside

[![Exercise Count](https://img.shields.io/endpoint.svg?url=https://php-interview-questions-counter.netlify.com/.netlify/functions/count)](./exercises)

This Exercise Counter is made with [Shields IO](https://shields.io/endpoint), [Axios](https://github.com/axios/axios), [GitHub GraphQL](https://developer.github.com/v4/) and [Netlify Functions](https://www.netlify.com/docs/functions/).

## Contributing

Do you have an idea for an exercise or a better solution? Submit a PR!

## License

[MIT](./LICENSE)
