# Javascrip Code tips

## Get Unique Values from an array

```
let fruits = ['🍇', '🍉', '🍎', '🍇', '🍒', '🍍', '🍎', '🍐', '🍒', '🍓', '🍇'];
let uniqueFruits = [... new Set(fruits)];

console.log(uniqueFruits);
// ['🍇', '🍉', '🍎', '🍒', '🍍', '🍐', '🍓']
```

## Removing Falsy values from Array

```
myArray.filter(Boolean);
```

## Sort number arrays

```
[1, 8, 5, 3, 13, 21, 2].sort((a, b) => a - b);

// [1, 2, 3, 5, 8, 13, 21]
```

## Disable Right click

```
<body oncontextmenu="return false">
  <div></div>
</body>
```

# CSS modern properties

## Aspect ratio

70% browsers

```
.element {
  width: 200px;
  aspect-ratio: 16 / 9;
}
```

## Content visibility

70% browsers
When skip the rendering of the element until it is actually needed (improves performance)

```
.element {
  content-visibility: auto
}
```

## Accent Color

40% browsers

```
input[type=checkbox] {
  accent-color: #FF5BDB
}
```

## Flex Gap

87% browsers

```
container {
  display: flex;
  gap: 12px;
  /* or */
  row-gap: 12px;
  column-gap: 12px;
}
```
