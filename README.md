## Numeric validation
This package validates number based upon provided rules.

## Installation 🐙

```bash
npm install numeric-validation
```

## Usage 💡

When using with a valid number, you will get the number back without any extra characters
```javascript
const numericValidation = require('numeric-validation')
const number = '2'

// function returns true/false
const flag = numericValidation(number, {
    greateThan: 5
})

console.log(`${number} is greater than 5: `, flag)
```

Multiple rules can be provided to validate number.
```javascript
numericValidation(<number_to_validate>, {
    <rule_name>: <value>
})
```

Multiple rules can be provided to validate number.
```javascript
1. greaterThan: pass number with this rule
2. equalTo: pass number with this rule
3. lesserThan: pass number with this rule
4. isInteger: pass true with this rule
5. isFloat: pass true with this rule
6. isNumber: pass true with this rule
```

## Maintainers 👷
1. Gaurav Chinawale
	* <a href="https://www.linkedin.com/in/gauravchinawale" title="Code">LinkedIn</a>
	* <a href="https://github.com/GauravChinavle" title="Code">Github</a>

Dedicating this package to my boss Prashant Kamdar who compelled me to build this package.
