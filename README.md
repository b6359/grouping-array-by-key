# grouping-array-by-key

Groups an array by the specified key.

## Installation

```
npm install --save grouping-array-by-key
```

## Usage

### Angular & React JS

```js
import * as groupByArray from 'grouping-array-by-key'

const students = [
  { name: 'Priscilla Hall', marks: 68 },
  { name: 'Marie Gonzalez', marks: 71 },
  { name: 'Kaylee Nichols', marks: 68 },
  { name: 'Kaylee Burns', marks: 82 },
  { name: 'Ellen Powell', marks: 71 },
];
  
const result = groupByArray(students, 'marks');
```

```js
// result

{
  68: [
    { name: 'Priscilla Hall', marks: 68 },
    { name: 'Kaylee Nichols', marks: 68 }
  ],
  71: [
     { name: 'Marie Gonzalez', marks: 71 },
     { name: 'Ellen Powell', marks: 71 }
  ],
  82: [
    { name: 'Kaylee Burns', marks: 82 }
  ]
};
```

### Node JS

```js
var groupByArray = require("grouping-array-by-key");

const students = [
  { name: 'Priscilla Hall', marks: 68 },
  { name: 'Marie Gonzalez', marks: 71 },
  { name: 'Kaylee Nichols', marks: 68 },
  { name: 'Kaylee Burns', marks: 82 },
  { name: 'Ellen Powell', marks: 71 },
];
  
const result = groupByArray(students, 'marks');
```

```js
// result

{
  68: [
    { name: 'Priscilla Hall', marks: 68 },
    { name: 'Kaylee Nichols', marks: 68 }
  ],
  71: [
     { name: 'Marie Gonzalez', marks: 71 },
     { name: 'Ellen Powell', marks: 71 }
  ],
  82: [
    { name: 'Kaylee Burns', marks: 82 }
  ]
};
```
### React-Native

```js
import groupByArray from 'grouping-array-by-key'

const students = [
  { name: 'Priscilla Hall', marks: 68 },
  { name: 'Marie Gonzalez', marks: 71 },
  { name: 'Kaylee Nichols', marks: 68 },
  { name: 'Kaylee Burns', marks: 82 },
  { name: 'Ellen Powell', marks: 71 },
];
  
const result = groupByArray(students, 'marks');
```

```js
// result

{
  68: [
    { name: 'Priscilla Hall', marks: 68 },
    { name: 'Kaylee Nichols', marks: 68 }
  ],
  71: [
     { name: 'Marie Gonzalez', marks: 71 },
     { name: 'Ellen Powell', marks: 71 }
  ],
  82: [
    { name: 'Kaylee Burns', marks: 82 }
  ]
};
```