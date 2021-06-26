# 内置函数 - 数据结构

## `Array`

| 函数名称       | 范式                         | 作用描述                    |
| -------------- | ---------------------------- | --------------------------- |
| 构造 | `newArray(sz: Num): Array` | 构造一个长度为 `sz` 的数组 |
| 填充 | `fill(arr: Array, pos: Num, val: Any): None` | 在 `arr` 的 `pos` 索引位填充 `val` 元素 |
| 获取长度 | `size(arr: Array): Num` | 获取 数组 `arr` 的长度|

## `Map`

| 函数名称       | 范式                         | 作用描述                    |
| -------------- | ---------------------------- | --------------------------- |
| 构造 | `newMap(): Map` | 构造一个表 |
| 填充 | `put(map: Map, key: Str, val: Any): None` | 在 `map` 的 `key` 键填充 `val` 值 |
| 获取元素个数 | `count(map: Map): Num` | 获取 表 `map` 的长度 |
| 查找键 | `keyIn(map: Map, key: Str): Num` | 查找 `key` 是否在 表 `map` 中 |