
# us-holidays-helper

The purpose of this project is to give an interface to work with holidays using `date-fns`

## Install

```
npm i us-holidays-helper   
```

## Table of contents

### Type Aliases

- [Holiday](README.md#holiday)
- [Holidays](README.md#holidays)

### Functions

- [getBankHolidays](README.md#getbankholidays)
- [getChristmas](README.md#getchristmas)
- [getEaster](README.md#geteaster)
- [getFathersDay](README.md#getfathersday)
- [getFederalHolidays](README.md#getfederalholidays)
- [getGoodFriday](README.md#getgoodfriday)
- [getHalloween](README.md#gethalloween)
- [getHolidays](README.md#getholidays)
- [getIndependenceDay](README.md#getindependenceday)
- [getIndigenousPeoplesDay](README.md#getindigenouspeoplesday)
- [getJuneteenth](README.md#getjuneteenth)
- [getLaborDay](README.md#getlaborday)
- [getMartinLutherKingJrDay](README.md#getmartinlutherkingjrday)
- [getMemorialDay](README.md#getmemorialday)
- [getMothersDay](README.md#getmothersday)
- [getNewYearsDay](README.md#getnewyearsday)
- [getNewYearsEve](README.md#getnewyearseve)
- [getObservedHolidays](README.md#getobservedholidays)
- [getPresidentsDay](README.md#getpresidentsday)
- [getThanksgiving](README.md#getthanksgiving)
- [getValentinesDay](README.md#getvalentinesday)
- [getVeteransDay](README.md#getveteransday)
- [isBankHoliday](README.md#isbankholiday)
- [isDateAHoliday](README.md#isdateaholiday)
- [isFederalHoliday](README.md#isfederalholiday)
- [isHoliday](README.md#isholiday)
- [isInHolidayList](README.md#isinholidaylist)

## Type Aliases

### Holiday

Ƭ **Holiday**: ``"christmas"`` \| ``"easter"`` \| ``"halloween"`` \| ``"valentinesDay"`` \| ``"mothersDay"`` \| ``"indigenousPeoplesDay"`` \| ``"independenceDay"`` \| ``"presidentsDay"`` \| ``"laborDay"`` \| ``"veteransDay"`` \| ``"thanksgiving"`` \| ``"newYearsEve"`` \| ``"martinLutherKingJrDay"`` \| ``"newYearsDay"`` \| ``"fathersDay"`` \| ``"memorialDay"`` \| ``"goodFriday"`` \| ``"juneteenth"``

#### Defined in

[index.ts:13](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L13)

___

### Holidays

Ƭ **Holidays**: { [K in Holiday]: Object }

#### Defined in

[index.ts:139](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L139)

## Functions

### getBankHolidays

▸ **getBankHolidays**(`year`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Object`

#### Defined in

[index.ts:242](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L242)

___

### getChristmas

▸ **getChristmas**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:99](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L99)

___

### getEaster

▸ **getEaster**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:49](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L49)

___

### getFathersDay

▸ **getFathersDay**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:127](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L127)

___

### getFederalHolidays

▸ **getFederalHolidays**(`year`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Object`

#### Defined in

[index.ts:264](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L264)

___

### getGoodFriday

▸ **getGoodFriday**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:135](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L135)

___

### getHalloween

▸ **getHalloween**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:33](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L33)

___

### getHolidays

▸ **getHolidays**(`year`): [`Holidays`](README.md#holidays)

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

[`Holidays`](README.md#holidays)

#### Defined in

[index.ts:147](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L147)

___

### getIndependenceDay

▸ **getIndependenceDay**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:91](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L91)

___

### getIndigenousPeoplesDay

▸ **getIndigenousPeoplesDay**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:87](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L87)

___

### getJuneteenth

▸ **getJuneteenth**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:45](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L45)

___

### getLaborDay

▸ **getLaborDay**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:103](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L103)

___

### getMartinLutherKingJrDay

▸ **getMartinLutherKingJrDay**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:119](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L119)

___

### getMemorialDay

▸ **getMemorialDay**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:131](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L131)

___

### getMothersDay

▸ **getMothersDay**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:41](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L41)

___

### getNewYearsDay

▸ **getNewYearsDay**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:123](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L123)

___

### getNewYearsEve

▸ **getNewYearsEve**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:115](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L115)

___

### getObservedHolidays

▸ **getObservedHolidays**(`year`): `Record`<`string`, `Record`<``"date"``, `Date`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Record`<`string`, `Record`<``"date"``, `Date`\>\>

#### Defined in

[index.ts:286](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L286)

___

### getPresidentsDay

▸ **getPresidentsDay**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:95](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L95)

___

### getThanksgiving

▸ **getThanksgiving**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:111](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L111)

___

### getValentinesDay

▸ **getValentinesDay**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:37](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L37)

___

### getVeteransDay

▸ **getVeteransDay**(`year`): `Date`

#### Parameters

| Name | Type |
| :------ | :------ |
| `year` | `number` |

#### Returns

`Date`

#### Defined in

[index.ts:107](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L107)

___

### isBankHoliday

▸ **isBankHoliday**(`date`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `date` | `Date` |

#### Returns

`boolean`

#### Defined in

[index.ts:339](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L339)

___

### isDateAHoliday

▸ **isDateAHoliday**(`date`, `holidaysToInclude`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `date` | `Date` |
| `holidaysToInclude` | [`Holiday`](README.md#holiday)[] |

#### Returns

`boolean`

#### Defined in

[index.ts:343](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L343)

___

### isFederalHoliday

▸ **isFederalHoliday**(`date`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `date` | `Date` |

#### Returns

`boolean`

#### Defined in

[index.ts:335](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L335)

___

### isHoliday

▸ **isHoliday**(`date`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `date` | `Date` |

#### Returns

`boolean`

#### Defined in

[index.ts:331](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L331)

___

### isInHolidayList

▸ **isInHolidayList**(`date`, `getHolidayList`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `date` | `Date` |
| `getHolidayList` | (`year`: `number`) => { `[key: string]`: { `date`: `Date`  };  } |

#### Returns

`boolean`

#### Defined in

[index.ts:319](https://github.com/bradymholt/us-holidays-helper/blob/main/src/index.ts#L319)

