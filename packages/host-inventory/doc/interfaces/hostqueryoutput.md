[@redhat-cloud-services/host-inventory-client](../README.md) › [Globals](../globals.md) › [HostQueryOutput](hostqueryoutput.md)

# Interface: HostQueryOutput

A paginated host search query result with host entries and their Inventory metadata.

**`export`** 

**`interface`** HostQueryOutput

## Hierarchy

* **HostQueryOutput**

## Index

### Properties

* [count](hostqueryoutput.md#count)
* [page](hostqueryoutput.md#page)
* [per_page](hostqueryoutput.md#per_page)
* [results](hostqueryoutput.md#results)
* [total](hostqueryoutput.md#total)

## Properties

###  count

• **count**: *number*

*Defined in [packages/host-inventory/api.ts:507](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L507)*

A number of entries on the current page.

**`memberof`** HostQueryOutput

___

###  page

• **page**: *number*

*Defined in [packages/host-inventory/api.ts:513](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L513)*

A current page number.

**`memberof`** HostQueryOutput

___

###  per_page

• **per_page**: *number*

*Defined in [packages/host-inventory/api.ts:519](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L519)*

A page size – a number of entries per single page.

**`memberof`** HostQueryOutput

___

###  results

• **results**: *Array‹[HostOut](hostout.md)›*

*Defined in [packages/host-inventory/api.ts:531](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L531)*

Actual host search query result entries.

**`memberof`** HostQueryOutput

___

###  total

• **total**: *number*

*Defined in [packages/host-inventory/api.ts:525](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L525)*

A total count of the found entries.

**`memberof`** HostQueryOutput
