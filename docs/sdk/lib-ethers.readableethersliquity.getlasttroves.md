<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-ethers](./lib-ethers.md) &gt; [ReadableEthersLiquity](./lib-ethers.readableethersliquity.md) &gt; [getLastTroves](./lib-ethers.readableethersliquity.getlasttroves.md)

## ReadableEthersLiquity.getLastTroves() method

Get a slice from the list of Troves sorted by collateral ratio in ascending order.

<b>Signature:</b>

```typescript
getLastTroves(startIdx: number, numberOfTroves: number, overrides?: EthersCallOverrides): Promise<[string, TroveWithPendingRedistribution][]>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  startIdx | number | Index of first Trove to include from the sorted list. |
|  numberOfTroves | number | The length of the slice. |
|  overrides | [EthersCallOverrides](./lib-ethers.etherscalloverrides.md) |  |

<b>Returns:</b>

Promise&lt;\[string, [TroveWithPendingRedistribution](./lib-base.trovewithpendingredistribution.md)<!-- -->\]\[\]&gt;

Pairs of owner addresses and their Troves.
