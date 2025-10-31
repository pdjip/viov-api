# GangArea

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ID** | **int32** |  | 
**DistriktID** | **int32** |  | 
**Name** | **string** |  | 
**X** | **float32** |  | 
**Y** | **float32** |  | 
**Z** | **float32** |  | 
**Range** | **int32** |  | 
**Rotation** | **int32** |  | 
**Owner** | **int32** |  | 
**LastAttack** | **int32** |  | 
**ItemID** | **int32** |  | 
**Amount** | **int32** |  | 
**Impact** | **int32** |  | 
**OldOwner** | **int32** |  | 

## Methods

### NewGangArea

`func NewGangArea(iD int32, distriktID int32, name string, x float32, y float32, z float32, range_ int32, rotation int32, owner int32, lastAttack int32, itemID int32, amount int32, impact int32, oldOwner int32, ) *GangArea`

NewGangArea instantiates a new GangArea object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGangAreaWithDefaults

`func NewGangAreaWithDefaults() *GangArea`

NewGangAreaWithDefaults instantiates a new GangArea object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetID

`func (o *GangArea) GetID() int32`

GetID returns the ID field if non-nil, zero value otherwise.

### GetIDOk

`func (o *GangArea) GetIDOk() (*int32, bool)`

GetIDOk returns a tuple with the ID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetID

`func (o *GangArea) SetID(v int32)`

SetID sets ID field to given value.


### GetDistriktID

`func (o *GangArea) GetDistriktID() int32`

GetDistriktID returns the DistriktID field if non-nil, zero value otherwise.

### GetDistriktIDOk

`func (o *GangArea) GetDistriktIDOk() (*int32, bool)`

GetDistriktIDOk returns a tuple with the DistriktID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDistriktID

`func (o *GangArea) SetDistriktID(v int32)`

SetDistriktID sets DistriktID field to given value.


### GetName

`func (o *GangArea) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GangArea) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GangArea) SetName(v string)`

SetName sets Name field to given value.


### GetX

`func (o *GangArea) GetX() float32`

GetX returns the X field if non-nil, zero value otherwise.

### GetXOk

`func (o *GangArea) GetXOk() (*float32, bool)`

GetXOk returns a tuple with the X field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX

`func (o *GangArea) SetX(v float32)`

SetX sets X field to given value.


### GetY

`func (o *GangArea) GetY() float32`

GetY returns the Y field if non-nil, zero value otherwise.

### GetYOk

`func (o *GangArea) GetYOk() (*float32, bool)`

GetYOk returns a tuple with the Y field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY

`func (o *GangArea) SetY(v float32)`

SetY sets Y field to given value.


### GetZ

`func (o *GangArea) GetZ() float32`

GetZ returns the Z field if non-nil, zero value otherwise.

### GetZOk

`func (o *GangArea) GetZOk() (*float32, bool)`

GetZOk returns a tuple with the Z field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZ

`func (o *GangArea) SetZ(v float32)`

SetZ sets Z field to given value.


### GetRange

`func (o *GangArea) GetRange() int32`

GetRange returns the Range field if non-nil, zero value otherwise.

### GetRangeOk

`func (o *GangArea) GetRangeOk() (*int32, bool)`

GetRangeOk returns a tuple with the Range field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRange

`func (o *GangArea) SetRange(v int32)`

SetRange sets Range field to given value.


### GetRotation

`func (o *GangArea) GetRotation() int32`

GetRotation returns the Rotation field if non-nil, zero value otherwise.

### GetRotationOk

`func (o *GangArea) GetRotationOk() (*int32, bool)`

GetRotationOk returns a tuple with the Rotation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRotation

`func (o *GangArea) SetRotation(v int32)`

SetRotation sets Rotation field to given value.


### GetOwner

`func (o *GangArea) GetOwner() int32`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *GangArea) GetOwnerOk() (*int32, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *GangArea) SetOwner(v int32)`

SetOwner sets Owner field to given value.


### GetLastAttack

`func (o *GangArea) GetLastAttack() int32`

GetLastAttack returns the LastAttack field if non-nil, zero value otherwise.

### GetLastAttackOk

`func (o *GangArea) GetLastAttackOk() (*int32, bool)`

GetLastAttackOk returns a tuple with the LastAttack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastAttack

`func (o *GangArea) SetLastAttack(v int32)`

SetLastAttack sets LastAttack field to given value.


### GetItemID

`func (o *GangArea) GetItemID() int32`

GetItemID returns the ItemID field if non-nil, zero value otherwise.

### GetItemIDOk

`func (o *GangArea) GetItemIDOk() (*int32, bool)`

GetItemIDOk returns a tuple with the ItemID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemID

`func (o *GangArea) SetItemID(v int32)`

SetItemID sets ItemID field to given value.


### GetAmount

`func (o *GangArea) GetAmount() int32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *GangArea) GetAmountOk() (*int32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *GangArea) SetAmount(v int32)`

SetAmount sets Amount field to given value.


### GetImpact

`func (o *GangArea) GetImpact() int32`

GetImpact returns the Impact field if non-nil, zero value otherwise.

### GetImpactOk

`func (o *GangArea) GetImpactOk() (*int32, bool)`

GetImpactOk returns a tuple with the Impact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpact

`func (o *GangArea) SetImpact(v int32)`

SetImpact sets Impact field to given value.


### GetOldOwner

`func (o *GangArea) GetOldOwner() int32`

GetOldOwner returns the OldOwner field if non-nil, zero value otherwise.

### GetOldOwnerOk

`func (o *GangArea) GetOldOwnerOk() (*int32, bool)`

GetOldOwnerOk returns a tuple with the OldOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOldOwner

`func (o *GangArea) SetOldOwner(v int32)`

SetOldOwner sets OldOwner field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


