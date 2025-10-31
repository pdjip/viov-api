# InventoryItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | **string** | The title or category of the inventory. | 
**MaxWeight** | **float32** | Maximum weight capacity allowed for this inventory. | 
**MaxCount** | **int32** | Maximum number of items allowed. | 
**Item** | **int32** | Identifier of the item type. | 
**Amount** | **int32** | The quantity of this item currently held. | 
**Meta** | Pointer to **map[string]interface{}** | Additional metadata about the item, if any. | [optional] 

## Methods

### NewInventoryItem

`func NewInventoryItem(title string, maxWeight float32, maxCount int32, item int32, amount int32, ) *InventoryItem`

NewInventoryItem instantiates a new InventoryItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInventoryItemWithDefaults

`func NewInventoryItemWithDefaults() *InventoryItem`

NewInventoryItemWithDefaults instantiates a new InventoryItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *InventoryItem) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *InventoryItem) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *InventoryItem) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetMaxWeight

`func (o *InventoryItem) GetMaxWeight() float32`

GetMaxWeight returns the MaxWeight field if non-nil, zero value otherwise.

### GetMaxWeightOk

`func (o *InventoryItem) GetMaxWeightOk() (*float32, bool)`

GetMaxWeightOk returns a tuple with the MaxWeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxWeight

`func (o *InventoryItem) SetMaxWeight(v float32)`

SetMaxWeight sets MaxWeight field to given value.


### GetMaxCount

`func (o *InventoryItem) GetMaxCount() int32`

GetMaxCount returns the MaxCount field if non-nil, zero value otherwise.

### GetMaxCountOk

`func (o *InventoryItem) GetMaxCountOk() (*int32, bool)`

GetMaxCountOk returns a tuple with the MaxCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxCount

`func (o *InventoryItem) SetMaxCount(v int32)`

SetMaxCount sets MaxCount field to given value.


### GetItem

`func (o *InventoryItem) GetItem() int32`

GetItem returns the Item field if non-nil, zero value otherwise.

### GetItemOk

`func (o *InventoryItem) GetItemOk() (*int32, bool)`

GetItemOk returns a tuple with the Item field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItem

`func (o *InventoryItem) SetItem(v int32)`

SetItem sets Item field to given value.


### GetAmount

`func (o *InventoryItem) GetAmount() int32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *InventoryItem) GetAmountOk() (*int32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *InventoryItem) SetAmount(v int32)`

SetAmount sets Amount field to given value.


### GetMeta

`func (o *InventoryItem) GetMeta() map[string]interface{}`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *InventoryItem) GetMetaOk() (*map[string]interface{}, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *InventoryItem) SetMeta(v map[string]interface{})`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *InventoryItem) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### SetMetaNil

`func (o *InventoryItem) SetMetaNil(b bool)`

 SetMetaNil sets the value for Meta to be an explicit nil

### UnsetMeta
`func (o *InventoryItem) UnsetMeta()`

UnsetMeta ensures that no value is present for Meta, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


