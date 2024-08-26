# FK EVM Address Generator

This JavaScript function generates a human-readable Ethereum address using the library. The generated address includes the specified postfix.

## Installation

Use the package manager [npm](npmjs.com) to install.

```bash
npm install fk-evm-address-generator
```

## Usage

```javascript
import { generateAddressEVM } from './generateAddressEVM'; // Assuming the file is in the same directory

const postfix = 'ETH';
const address = generateAddressEVM(postfix);

console.log(address); // Output: milkETH
```

## Parameter

postfix: A string to append to the generated address.

## Return Value

A human-readable Ethereum address with the specified postfix.

## Example

```javascript
const address = generateAddressEVM('token');
console.log(address); // Output: milktoken
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
