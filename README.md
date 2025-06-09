# Technical Test – Back-End Internship at ZettaByte

## Task

Create a function that returns the maximum number of words in a single sentence from a given array of sentences.

## Example

**Input:**
```js
const sentences = [
  'Mauris ultricies sed sapien eget malesuada. Suspendisse et aliquet odio, id ultrices erat. Praesent vehicula erat nulla. Aliquam a lorem urna. Donec.',
  'Duis at tellus et ex bibendum pellentesque sed in nibh. Sed aliquet, diam id mollis facilisis, massa metus accumsan elit, at mattis magna.',
  'Sed non nibh quam. Pellentesque eget ultrices diam. Aliquam diam justo, consectetur ac dui lobortis, vestibulum bibendum lorem. Sed porta pulvinar.',
];
```

**Output:**
```
23
```

## Approach

- Iterate through each sentence
- Split each sentence into words
- Count the number of valid words
- Track the maximum count and return it

## Result

The function returns the maximum number of words found in a single sentence. In this case, the result is `23`.