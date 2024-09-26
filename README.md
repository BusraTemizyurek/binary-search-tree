# Binary Search Tree

This repository contains a binary search tree npm package.

## Usage

```ts
import { BinarySearchTree } from 'basic-binary-search-tree';

const bst = new BinarySearchTree();

bst.add(10);
bst.add(5);
bst.add(15);

console.log(bst.toArray());

console.log(bst.has(5));
bst.remove(10);
console.log(bst.has(5));

console.log(bst.getMin());
console.log(bst.getMax());
```