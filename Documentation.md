# rsk-utils documentation

## Addresses
<a name="zeroAddress"></a>

### zeroAddress() ⇒ <code>String</code>
Returns the zero address

<a name="isAddress"></a>

### isAddress(address) ⇒ <code>Boolean</code>
Check if a string is an address

**Params**

- address <code>String</code>

<a name="toChecksumAddress"></a>

### toChecksumAddress(address, chainId) ⇒ <code>String</code>
Implements EIP-1191 Address Checksum

**Returns**: <code>String</code> - checksummed address  
**Params**

- address <code>String</code>
- chainId <code>Integer</code> | <code>String</code>

<a name="isValidChecksumAddress"></a>

### isValidChecksumAddress(address, chainId) ⇒ <code>Boolean</code>
Validates address checksum

**Params**

- address <code>String</code>
- chainId <code>Integer</code> | <code>String</code>

<a name="isValidAddress"></a>

### isValidAddress(address, chainId) ⇒ <code>Boolean</code>
Checks if an address is valid.

**Params**

- address <code>String</code>
- chainId <code>Integer</code> | <code>String</code>

<a name="searchChecksummedNetworks"></a>

### searchChecksummedNetworks(address, [networks]) ⇒ <code>Array</code>
Search network info of checksummed address

**Params**

- address <code>String</code>
- [networks] <code>Array</code> - chainId list
see: https://chainid.network/chains.json

<a name="isZeroAddress"></a>

### isZeroAddress(address, chainId) ⇒ <code>Boolean</code>
Checks if is zero address.

**Params**

- address <code>String</code>
- chainId <code>Integer</code> | <code>String</code>


## Arrays
<a name="arrayIntersection"></a>

### arrayIntersection(a, b) ⇒ <code>Array</code>
**Returns**: <code>Array</code> - a ∩ b  
**Params**

- a <code>Array</code>
- b <code>Array</code>

<a name="arrayDifference"></a>

### arrayDifference(a, b) ⇒ <code>Array</code>
**Returns**: <code>Array</code> - a - b  
**Params**

- a <code>Array</code>
- b <code>Array</code>

<a name="arraySymmetricDifference"></a>

### arraySymmetricDifference(a, b) ⇒ <code>Array</code>
**Returns**: <code>Array</code> - a - b  
**Params**

- a <code>Array</code>
- b <code>Array</code>

<a name="hasValue"></a>

### hasValue(haystack, needle) ⇒ <code>Boolean</code>
Check if an array contains some of the searched items

**Params**

- haystack <code>Array</code>
- needle <code>Array</code>

<a name="includesAll"></a>

### includesAll(haystack, needle) ⇒ <code>Boolean</code>
Check if an array contains all the searched items

**Params**

- haystack <code>Array</code>
- needle <code>Array</code>


## Bytes
<a name="toBuffer"></a>

### toBuffer(value, [encoding]) ⇒ <code>Buffer</code>
Converts strings or numbers to buffer

**Params**

- value <code>string</code> | <code>number</code> | <code>buffer</code>
- [encoding] <code>String</code> <code> = &#x27;hex&#x27;</code>

<a name="bufferToHex"></a>

### bufferToHex(buffer) ⇒ <code>String</code>
Converts buffer to hex string

**Params**

- buffer <code>Buffer</code>


## Hashes
<a name="keccak256"></a>

### keccak256(input, [format]) ⇒ <code>Buffer</code>
Creates Keccak sha256 hash

**Params**

- input <code>String</code> | <code>Number</code> | <code>Array</code> | <code>Buffer</code>
- [format] <code>String</code> <code> = &#x27;hex&#x27;</code>


## Strings
<a name="isHexString"></a>

### isHexString(str) ⇒ <code>Boolean</code>
Checks if a string is hex string

**Params**

- str <code>String</code>

<a name="add0x"></a>

### add0x(str) ⇒ <code>String</code>
Add '0x' at start of hex strings, honoring prefix

**Params**

- str <code>String</code>

<a name="hasHexPrefix"></a>

### hasHexPrefix(str) ⇒ <code>Boolean</code>
Checks if string is hex prefixed

**Params**

- str <code>String</code>

<a name="stripHexPrefix"></a>

### stripHexPrefix(str) ⇒ <code>String</code>
remove 0x from start of string

**Params**

- str <code>String</code>

<a name="remove0x"></a>

### remove0x(value) ⇒ <code>Any</code>
Remove '0x' from hex strings, honoring prefix

**Returns**: <code>Any</code> - if value is hex string, {String} without '0x'  
**Params**

- value <code>Any</code>

<a name="isTxOrBlockHash"></a>

### isTxOrBlockHash(str) ⇒ <code>Boolean</code>
Checks if a string is a tx or block hash

**Returns**: <code>Boolean</code> - '  
**Params**

- str <code>string</code>


