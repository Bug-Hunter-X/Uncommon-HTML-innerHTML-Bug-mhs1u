# Uncommon HTML innerHTML Bug
This repository demonstrates a subtle bug related to using innerHTML in JavaScript to manipulate HTML content. The bug arises from misunderstanding how innerHTML works with the += operator.

## Bug Description
The `innerHTML` property, when used with the `+=` operator, does not append content. Instead, it completely replaces the existing content of the element. This behavior is not always intuitive and can lead to unexpected results.

## Solution
The solution involves using methods such as `insertAdjacentHTML` or creating and appending new elements using `createElement` to properly add to the existing content.
