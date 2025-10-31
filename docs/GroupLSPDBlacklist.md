# GroupLSPDBlacklist

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GroupID** | **int32** |  | 
**GroupName** | Pointer to **string** |  | [optional] 
**Expiry** | **int32** |  | 
**Reason** | **string** |  | 
**Creator** | **string** |  | 

## Methods

### NewGroupLSPDBlacklist

`func NewGroupLSPDBlacklist(groupID int32, expiry int32, reason string, creator string, ) *GroupLSPDBlacklist`

NewGroupLSPDBlacklist instantiates a new GroupLSPDBlacklist object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupLSPDBlacklistWithDefaults

`func NewGroupLSPDBlacklistWithDefaults() *GroupLSPDBlacklist`

NewGroupLSPDBlacklistWithDefaults instantiates a new GroupLSPDBlacklist object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroupID

`func (o *GroupLSPDBlacklist) GetGroupID() int32`

GetGroupID returns the GroupID field if non-nil, zero value otherwise.

### GetGroupIDOk

`func (o *GroupLSPDBlacklist) GetGroupIDOk() (*int32, bool)`

GetGroupIDOk returns a tuple with the GroupID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupID

`func (o *GroupLSPDBlacklist) SetGroupID(v int32)`

SetGroupID sets GroupID field to given value.


### GetGroupName

`func (o *GroupLSPDBlacklist) GetGroupName() string`

GetGroupName returns the GroupName field if non-nil, zero value otherwise.

### GetGroupNameOk

`func (o *GroupLSPDBlacklist) GetGroupNameOk() (*string, bool)`

GetGroupNameOk returns a tuple with the GroupName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupName

`func (o *GroupLSPDBlacklist) SetGroupName(v string)`

SetGroupName sets GroupName field to given value.

### HasGroupName

`func (o *GroupLSPDBlacklist) HasGroupName() bool`

HasGroupName returns a boolean if a field has been set.

### GetExpiry

`func (o *GroupLSPDBlacklist) GetExpiry() int32`

GetExpiry returns the Expiry field if non-nil, zero value otherwise.

### GetExpiryOk

`func (o *GroupLSPDBlacklist) GetExpiryOk() (*int32, bool)`

GetExpiryOk returns a tuple with the Expiry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiry

`func (o *GroupLSPDBlacklist) SetExpiry(v int32)`

SetExpiry sets Expiry field to given value.


### GetReason

`func (o *GroupLSPDBlacklist) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *GroupLSPDBlacklist) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *GroupLSPDBlacklist) SetReason(v string)`

SetReason sets Reason field to given value.


### GetCreator

`func (o *GroupLSPDBlacklist) GetCreator() string`

GetCreator returns the Creator field if non-nil, zero value otherwise.

### GetCreatorOk

`func (o *GroupLSPDBlacklist) GetCreatorOk() (*string, bool)`

GetCreatorOk returns a tuple with the Creator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreator

`func (o *GroupLSPDBlacklist) SetCreator(v string)`

SetCreator sets Creator field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


