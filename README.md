# js-sha420

A simple SHA-420 hash function for JavaScript supports UTF-8 encoding.


## Installation

For node.js, you can use this command to install:

    npm install js-sha420

## Usage
If you use node.js, you should require the module first:
```JavaScript
const sha420 = require('js-sha420');
```

## Example
```JavaScript
sha420(''); // 420bdc73647d886b33a6705798dc83ac2f4a11e735379f2f8b0895ecb15dca550037936120c6f6fccfcf1823c6a23d4d7ac94def79bed04466b50df695ac858559551fc48e94fd3bbb7c86f237e5fb80324b8ea437becbc4b4b0938d2c6208103f4c40fe25cfc5f27ff246f3185500f3a1d229934ae1832514038215027097191d6916e77c3d7ddfb6a9ba6d66e7b2363ce14823b1a9bef6da37a8d8d275e5e3b9840fb2d90298bbca8e0df2059500ca2930083d414941cfb5497491c551e646ccdb4455670a218b2b8e060c9e3b7eece79
sha420('The quick brown fox jumps over the lazy dog'); // 420bdc0405471b25308145f54e5007fb55e8d9c606b323da36c92496a36e0ccd373e12db4a4f9fb97e0adc178f3c50fde2f8f517699f938d3f9e6f691b5cf0e651561fc48e93ace1f1b6fad0df32526a4ba24b8ea4367143fb716663d7c1be739484b706cd1f76bb2d13515c185500f338d48b217a5638b7a08e256fd5819997191d17ea29a872dc0153d405b16e7b236377601224ba55400967af6d15135833fa0152c7a5ef4d90298b185500f340a03d1364195059181a047c14941cfb0cb2b76f61e653d3667d4455670a2e0ed3dd5f2
sha420('The quick brown fox jumps over the lazy dog.'); // 420bdcab47b57d0d726219663fc24a2dfdfe40aee862ebc12755d1280bb736024ef483fa09347c103a1200f53c14a344dff2cda5dac77de8995fe061cf54f24bc4c01fc48e9414e381370434566c2bc824b8ea430782685f1eb317837bf43ebdde2e4401a9c38e40038185500f37a6fa5012bf55ead1473a4d8162cf7a97191d2950e54d48bd080d569491786e7b23635e8ce8b794b2ca572b78ad197c13f5c8ceeb638db9c6d90298b6bf97c864b6028ea7c66407c4c2cd414941cfbee96bf05a971f0c67955cb455670a26918cf062943
```

## License
The project is released under the [MIT license](http://www.opensource.org/licenses/MIT).

## Contact
Author: Alek Murder_One, https://github.com/Alek12313/js-sha420

Original author: Chen, Yi-Cyuan https://github.com/emn178/js-sha512  
