## ES7
const arr = [1, 2, 3];
  arr.includes(2); // true

  let a = 3;
      a**3;  // 27
      a**=3; // 27  a === 27

## ES8
const func = async () => {
    let n = await one(); 
    let m = await two(); 
    console.log(n, m) // 按顺序执行函数 并返回值
}
      
const obj = { x: "xxx", y: 1 };
      Object.values(obj); //["xxx", 1]
      
const obj = ["e", "s", "8"];
      Object.values(obj); // ["e", "s", "8"]

//使用 数字键值， 返回的数字排序
const obj = { 8: "xxx", 1: "yyy", 4: "zzz" };
			Object.values(obj); //["yyy", "zzz", "xxx"]
			
			Object.values("es8"); //["e", "s", "8"]

const obj = { x: 'xxx', y: 1 };
      Object.entries(obj); // [['x', 'xxx'], ['y', 1]]

const obj = ['e', 's', '8'];
      Object.entries(obj); // [['0', 'e'], ['1', 's'], ['2', '8']]

const obj = { 10: 'xxx', 1: 'yyy', 3: 'zzz' };
      Object.entries(obj); // [['1', 'yyy'], ['3', 'zzz'], ['10': 'xxx']]

      Object.entries('es8'); // [['0', 'e'], ['1', 's'], ['2', '8']]

'es8'.padStart(2);          // 'es8'
'es8'.padStart(5);          // '  es8'
'es8'.padStart(6, 'woof');  // 'wooes8'
'es8'.padStart(14, 'wow');  // 'wowwowwowwoes8'
'es8'.padStart(7, '0');     // '0000es8'

'es8'.padEnd(2);            // 'es8'
'es8'.padEnd(5);            // 'es8  '
'es8'.padEnd(6, 'woof');    // 'es8woo'
'es8'.padEnd(14, 'wow');    // 'es8wowwowwowwo'
'es8'.padEnd(7, '6');       // 'es86666'

//旧 [1, 2] => 新 [1, 2,] 在数组和对象中可使用结尾逗号  利于开发

## ES9
async function example() {
  // 普通迭代器:
  const iterator = createNumberIterator();
  iterator.next(); // Object {value: 1, done: false}
  iterator.next(); // Object {value: 2, done: false}
  iterator.next(); // Object {value: 3, done: false}
  iterator.next(); // Object {value: undefined, done: true}

  // 异步迭代器:
  const asyncIterator = createAsyncNumberIterator();
  const p = asyncIterator.next(); // Promise
  await p;// Object {value: 1, done: false}
  await asyncIterator.next(); // Object {value: 2, done: false}
  await asyncIterator.next(); // Object {value: 3, done: false}
  await asyncIterator.next(); // Object {value: undefined, done: true}
}

const promises = [
    new Promise(resolve => resolve(1)),
    new Promise(resolve => resolve(2)),
    new Promise(resolve => resolve(3)),
];

async function test() {
    for await (const p of promises) {
        console.log(p); 
    }
		
}
test(); // 1  2  3

const obj = {
  a: 1,
  b: 2,
  c: 3
}
const { a, ...param } = obj;
  console.log(a)     //1
  console.log(param) //{b: 2, c: 3}

function foo({a, ...param}) {
  console.log(a);    //1
  console.log(param) //{b: 2, c: 3}
}


promise
  .then(result => {···})
  .catch(error => {···})
  .finally(() => {···});   //总是会运行
	
	

