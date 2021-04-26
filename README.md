# Typechain


``` typescript
const name = "Donghee",
  age = 27,
  gender = "male";

const sayHello= (name:string, age:number, gender?:string):void => {
  console.log(`Hello i'm ${name}, i'm ${age} and ${gender} `);
}

const sayHello= (name:string, age:number, gender?:string):string => {
  return `Hello i'm ${name}, i'm ${age} and ${gender} `;


sayHello(name,age,gender)

export {};
```


## Typescript - class
```typescript
class Human {
  public name: string;
  public age: number;
  public gender: string;
  constructor(name:string, age:number, gender:string) {
    this.name = name;
    this.age = age;
    this.gender = gender;
  }
}
```



## tsc-watch 사용하기
[LINK](https://darrengwon.tistory.com/116)