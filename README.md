# Tintin

Teach someone what these scripts do and how they work.

(they're not in any special order)


### Index
* [one](#one)
* [two](#two)
* [three](#three)
* [four](#four)
* [five](#five)
* [six](#six)

---

## One

```js
{
  function tin() {
      return (tin())()
  };
  const done = tin();
  console.log("done: ", done);
}
```

[TOP](#the-tins)

---

## Two


```js
{
  function tin() {
      return tin
  };

  const done = tin()()()()();

  console.log("done: ", done);
}
```

[TOP](#the-tins)

---

## Three

```js
{
  function tin() {
      return tin
  };
  tin.tin = tin;

  const done_1 = tin.tin()().tin().tin.tin.tin().tin.tin();
  const done_2 = tin(tin.tin.tin.tin.tin)();
  const done_3 = (tin.tin.tin.tin().tin()()()().tin)();
  const done_4 = tin[tin().name];

  console.log("done 1: ", done_1);
  console.log("done 2: ", done_2);
  console.log("done 3: ", done_3);
  console.log("done 4: ", done_4);
}
```


[TOP](#the-tins)

---

## Four

```js
{
  function tin(arg) {
    tin = arg;
    return tin;
  }

  const done_1 = tin(tin);
  const done_2 = tin();

  console.log("done 1: ", done_1);
  console.log("done 2: ", done_2);
}
```

[TOP](#the-tins)

---

## Five

```js
{
  function tin(arg) {
    return arg;
  }
  tin.tin = tin;

  const done = (tin(tin(tin).tin))();

  console.log("done: ", done);
}
```


[TOP](#the-tins)

---

## Six


```js
{
  function tin(arg) {
    return arg.tin; 
  }
  tin.tin = tin;

  const done_1 = tin.tin.tin.tin(tin);
  const done_2 = tin.tin.tin.tin();

  console.log("done 1: ", done_1);
  console.log("done 2: ", done_2);
}
```

[TOP](#the-tins)

___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>
