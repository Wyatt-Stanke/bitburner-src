<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Grafting](./bitburner.grafting.md) &gt; [getAugmentationGraftTime](./bitburner.grafting.getaugmentationgrafttime.md)

## Grafting.getAugmentationGraftTime() method

Retrieves the time required to graft an aug.

<b>Signature:</b>

```typescript
getAugmentationGraftTime(augName: string): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  augName | string | Name of the aug to check the grafting time of. Must be an exact match. |

<b>Returns:</b>

number

The time required, in millis, to graft the named augmentation.

## Exceptions

Will error if an invalid Augmentation name is provided.

## Remarks

RAM cost: 3.75 GB
