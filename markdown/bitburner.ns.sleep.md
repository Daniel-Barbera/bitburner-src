<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [NS](./bitburner.ns.md) &gt; [sleep](./bitburner.ns.sleep.md)

## NS.sleep() method

Suspends the script for n milliseconds.

**Signature:**

```typescript
sleep(millis: number): Promise<true>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  millis | number | Number of milliseconds to sleep. |

**Returns:**

Promise&lt;true&gt;


## Remarks

RAM cost: 0 GB

## Example 1


```ts
// NS1:
// This will count from 1 to 10 in your terminal, with one number every 5 seconds
for (var i=0; i<10; i++) {
  tprint(i + 1);
  sleep(5000);
}
```

## Example 2


```ts
// NS2:
// This will count from 1 to 10 in your terminal, with one number every 5 seconds
for (var i=0; i<10; i++) {
  ns.tprint(i + 1);
  await ns.sleep(5000);
}
```

