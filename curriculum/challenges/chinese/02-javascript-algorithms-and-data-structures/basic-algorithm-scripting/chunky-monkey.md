---
id: a9bd25c716030ec90084d8a1
title: 矮胖的猴子
challengeType: 5
videoUrl: ''
---

# --description--

编写一个函数，将数组（第一个参数）拆分为`size`的长度（第二个参数），并将它们作为二维数组返回。如果卡住，请记得使用[Read-Search-Ask](https://forum.freecodecamp.org/t/how-to-get-help-when-you-are-stuck-coding/19514) 。编写自己的代码。

# --hints--

`chunkArrayInGroups(["a", "b", "c", "d"], 2)`应返回`[["a", "b"], ["c", "d"]]` 。

```js
assert.deepEqual(chunkArrayInGroups(['a', 'b', 'c', 'd'], 2), [
  ['a', 'b'],
  ['c', 'd']
]);
```

`chunkArrayInGroups([0, 1, 2, 3, 4, 5], 3)`应返回`[[0, 1, 2], [3, 4, 5]]` 。

```js
assert.deepEqual(chunkArrayInGroups([0, 1, 2, 3, 4, 5], 3), [
  [0, 1, 2],
  [3, 4, 5]
]);
```

`chunkArrayInGroups([0, 1, 2, 3, 4, 5], 2)`应返回`[[0, 1], [2, 3], [4, 5]]` 。

```js
assert.deepEqual(chunkArrayInGroups([0, 1, 2, 3, 4, 5], 2), [
  [0, 1],
  [2, 3],
  [4, 5]
]);
```

`chunkArrayInGroups([0, 1, 2, 3, 4, 5], 4)`应该返回`[[0, 1, 2, 3], [4, 5]]` 。

```js
assert.deepEqual(chunkArrayInGroups([0, 1, 2, 3, 4, 5], 4), [
  [0, 1, 2, 3],
  [4, 5]
]);
```

`chunkArrayInGroups([0, 1, 2, 3, 4, 5, 6], 3)`应该返回`[[0, 1, 2], [3, 4, 5], [6]]` 。

```js
assert.deepEqual(chunkArrayInGroups([0, 1, 2, 3, 4, 5, 6], 3), [
  [0, 1, 2],
  [3, 4, 5],
  [6]
]);
```

`chunkArrayInGroups([0, 1, 2, 3, 4, 5, 6, 7, 8], 4)`应返回`[[0, 1, 2, 3], [4, 5, 6, 7], [8]]` `chunkArrayInGroups([0, 1, 2, 3, 4, 5, 6, 7, 8], 4)` `[[0, 1, 2, 3], [4, 5, 6, 7], [8]]` 。

```js
assert.deepEqual(chunkArrayInGroups([0, 1, 2, 3, 4, 5, 6, 7, 8], 4), [
  [0, 1, 2, 3],
  [4, 5, 6, 7],
  [8]
]);
```

`chunkArrayInGroups([0, 1, 2, 3, 4, 5, 6, 7, 8], 2)`应返回`[[0, 1], [2, 3], [4, 5], [6, 7], [8]]` 。

```js
assert.deepEqual(chunkArrayInGroups([0, 1, 2, 3, 4, 5, 6, 7, 8], 2), [
  [0, 1],
  [2, 3],
  [4, 5],
  [6, 7],
  [8]
]);
```

# --solutions--

