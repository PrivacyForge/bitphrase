# ByteWorder.js

Encode and Decode Bytes to Meaningful Word

## Encode

```js
const encoded = encodeUint8ArrayToWord(
  new Uint8Array([2, 23, 43, 123, 2, 23, 42, 12, 34, 10, 98, 7])
);
console.log(encoded); // عاقبت مهر نر خدایی جهانبان تونیک تبرک
```

## Decode

```js
const encoded = "عاقبت مهر نر خدایی جهانبان تونیک تبرک";
const decoded = decodeWordToUint8Array(encoded);
console.log(decoded); // [2, 23, 43, 123, 2, 23, 42, 12, 34, 10, 98, 7]
```
