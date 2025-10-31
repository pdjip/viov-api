# SystemItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ID** | **int32** |  | 
**Name** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Weight** | Pointer to **float64** |  | [optional] 
**Legal** | **int32** |  | 
**Heal** | **int32** |  | 
**Food** | **int32** |  | 
**PriceMin** | **int32** |  | 
**PriceMax** | **int32** |  | 
**AllowTrade** | **int32** |  | 
**Sync** | **int32** |  | 
**OnlyOnce** | **int32** |  | 

## Methods

### NewSystemItem

`func NewSystemItem(iD int32, legal int32, heal int32, food int32, priceMin int32, priceMax int32, allowTrade int32, sync int32, onlyOnce int32, ) *SystemItem`

NewSystemItem instantiates a new SystemItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemItemWithDefaults

`func NewSystemItemWithDefaults() *SystemItem`

NewSystemItemWithDefaults instantiates a new SystemItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetID

`func (o *SystemItem) GetID() int32`

GetID returns the ID field if non-nil, zero value otherwise.

### GetIDOk

`func (o *SystemItem) GetIDOk() (*int32, bool)`

GetIDOk returns a tuple with the ID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetID

`func (o *SystemItem) SetID(v int32)`

SetID sets ID field to given value.


### GetName

`func (o *SystemItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SystemItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SystemItem) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SystemItem) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *SystemItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SystemItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SystemItem) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SystemItem) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetWeight

`func (o *SystemItem) GetWeight() float64`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *SystemItem) GetWeightOk() (*float64, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *SystemItem) SetWeight(v float64)`

SetWeight sets Weight field to given value.

### HasWeight

`func (o *SystemItem) HasWeight() bool`

HasWeight returns a boolean if a field has been set.

### GetLegal

`func (o *SystemItem) GetLegal() int32`

GetLegal returns the Legal field if non-nil, zero value otherwise.

### GetLegalOk

`func (o *SystemItem) GetLegalOk() (*int32, bool)`

GetLegalOk returns a tuple with the Legal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegal

`func (o *SystemItem) SetLegal(v int32)`

SetLegal sets Legal field to given value.


### GetHeal

`func (o *SystemItem) GetHeal() int32`

GetHeal returns the Heal field if non-nil, zero value otherwise.

### GetHealOk

`func (o *SystemItem) GetHealOk() (*int32, bool)`

GetHealOk returns a tuple with the Heal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeal

`func (o *SystemItem) SetHeal(v int32)`

SetHeal sets Heal field to given value.


### GetFood

`func (o *SystemItem) GetFood() int32`

GetFood returns the Food field if non-nil, zero value otherwise.

### GetFoodOk

`func (o *SystemItem) GetFoodOk() (*int32, bool)`

GetFoodOk returns a tuple with the Food field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFood

`func (o *SystemItem) SetFood(v int32)`

SetFood sets Food field to given value.


### GetPriceMin

`func (o *SystemItem) GetPriceMin() int32`

GetPriceMin returns the PriceMin field if non-nil, zero value otherwise.

### GetPriceMinOk

`func (o *SystemItem) GetPriceMinOk() (*int32, bool)`

GetPriceMinOk returns a tuple with the PriceMin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceMin

`func (o *SystemItem) SetPriceMin(v int32)`

SetPriceMin sets PriceMin field to given value.


### GetPriceMax

`func (o *SystemItem) GetPriceMax() int32`

GetPriceMax returns the PriceMax field if non-nil, zero value otherwise.

### GetPriceMaxOk

`func (o *SystemItem) GetPriceMaxOk() (*int32, bool)`

GetPriceMaxOk returns a tuple with the PriceMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceMax

`func (o *SystemItem) SetPriceMax(v int32)`

SetPriceMax sets PriceMax field to given value.


### GetAllowTrade

`func (o *SystemItem) GetAllowTrade() int32`

GetAllowTrade returns the AllowTrade field if non-nil, zero value otherwise.

### GetAllowTradeOk

`func (o *SystemItem) GetAllowTradeOk() (*int32, bool)`

GetAllowTradeOk returns a tuple with the AllowTrade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowTrade

`func (o *SystemItem) SetAllowTrade(v int32)`

SetAllowTrade sets AllowTrade field to given value.


### GetSync

`func (o *SystemItem) GetSync() int32`

GetSync returns the Sync field if non-nil, zero value otherwise.

### GetSyncOk

`func (o *SystemItem) GetSyncOk() (*int32, bool)`

GetSyncOk returns a tuple with the Sync field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSync

`func (o *SystemItem) SetSync(v int32)`

SetSync sets Sync field to given value.


### GetOnlyOnce

`func (o *SystemItem) GetOnlyOnce() int32`

GetOnlyOnce returns the OnlyOnce field if non-nil, zero value otherwise.

### GetOnlyOnceOk

`func (o *SystemItem) GetOnlyOnceOk() (*int32, bool)`

GetOnlyOnceOk returns a tuple with the OnlyOnce field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnlyOnce

`func (o *SystemItem) SetOnlyOnce(v int32)`

SetOnlyOnce sets OnlyOnce field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


