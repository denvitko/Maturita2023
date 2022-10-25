# 4) Podmínky


## Boolean logic

| AND   | OR     | Bitwise AND | Bitwise OR | XOR   | NOT   | Bitwise NOT | × | Equal | NOT equal | AND Equal | OR Equal | XOR Equal |
| :--:  | :---:  | :---:       | :---:      | :---: | :---: | :---:       | - | :---: | :---:     | :---:     | :---:    | :---:     |
| `&&`  | `\|\|` | `&`         | `\|`       | `^`   | `!`   |  `~`        | × | `==`  | `!=`      | `&=`      | `\|=`    | `^=`      |
| `and` | `or`   |  `bitand`   | `bitor`    | `xor` | `not` | `compl`     | × | `eq`  | `not_eq`  | `and_eq`  | `or_eq`  | `xor_eq`  |

## if-else

```cpp
if(condition) {
  // block of code...
} else if(condition) {
  // block of code...
} else {
  // block of code...
}
```

## switch

```cpp
switch(condition) {
  case 1: 
    // statement...
    break;
  case 2: {
    // block of code ...
  } break;
  default:
    // statement
}
```

<!--
```cpp
if(true and true) {
  std::cout << "Both are true." << std::endl;
} else if(false and false) {
  std::cout << "Both are false." << std::endl;
} else {
  std::cout << "One of them is true, the other is false." << std::endl;
}
```
-->
