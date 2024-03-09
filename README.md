# @jnlietta/id-generator

## Description
@jnlietta/id-generator is easy-to-use package that will help you generate a random id that contains big and small letters, numbers from 0 to 9 and have length that you'll choose.

## Installation
To install the package, run the following command in your terminal:

```
yarn add @jnlietta/randomid-generator
```

## Usage
After installation you can easily import the function into your project. Here is a example of usage the package: 

```
// import package to your project as a randomID
const randomID = require('@jnlietta/randomid-generator');

// generate a random ID with length 10
const newRandomID = randomID(10);
console.log(newRandomID); // console will show a random string, e.g., 'Dc1ZzS95rD'
```

## Requirements
To use method properly you have to put a single argument that is a number:

-**idLength** : number that will determine the amount of signs used in the generated id in string type.

## License
This project is licensed under MIT License.