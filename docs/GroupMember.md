# GroupMember

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CharacterID** | **int32** |  | 
**GroupID** | **int32** |  | 
**Rank** | **int32** |  | 
**Activity** | **int32** |  | 
**Name** | Pointer to **string** |  | [optional] 
**Permissions** | **string** |  | 
**LastActivity** | **int32** |  | 
**Online** | Pointer to **bool** |  | [optional] 

## Methods

### NewGroupMember

`func NewGroupMember(characterID int32, groupID int32, rank int32, activity int32, permissions string, lastActivity int32, ) *GroupMember`

NewGroupMember instantiates a new GroupMember object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupMemberWithDefaults

`func NewGroupMemberWithDefaults() *GroupMember`

NewGroupMemberWithDefaults instantiates a new GroupMember object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCharacterID

`func (o *GroupMember) GetCharacterID() int32`

GetCharacterID returns the CharacterID field if non-nil, zero value otherwise.

### GetCharacterIDOk

`func (o *GroupMember) GetCharacterIDOk() (*int32, bool)`

GetCharacterIDOk returns a tuple with the CharacterID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacterID

`func (o *GroupMember) SetCharacterID(v int32)`

SetCharacterID sets CharacterID field to given value.


### GetGroupID

`func (o *GroupMember) GetGroupID() int32`

GetGroupID returns the GroupID field if non-nil, zero value otherwise.

### GetGroupIDOk

`func (o *GroupMember) GetGroupIDOk() (*int32, bool)`

GetGroupIDOk returns a tuple with the GroupID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupID

`func (o *GroupMember) SetGroupID(v int32)`

SetGroupID sets GroupID field to given value.


### GetRank

`func (o *GroupMember) GetRank() int32`

GetRank returns the Rank field if non-nil, zero value otherwise.

### GetRankOk

`func (o *GroupMember) GetRankOk() (*int32, bool)`

GetRankOk returns a tuple with the Rank field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRank

`func (o *GroupMember) SetRank(v int32)`

SetRank sets Rank field to given value.


### GetActivity

`func (o *GroupMember) GetActivity() int32`

GetActivity returns the Activity field if non-nil, zero value otherwise.

### GetActivityOk

`func (o *GroupMember) GetActivityOk() (*int32, bool)`

GetActivityOk returns a tuple with the Activity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivity

`func (o *GroupMember) SetActivity(v int32)`

SetActivity sets Activity field to given value.


### GetName

`func (o *GroupMember) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GroupMember) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GroupMember) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *GroupMember) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPermissions

`func (o *GroupMember) GetPermissions() string`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *GroupMember) GetPermissionsOk() (*string, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *GroupMember) SetPermissions(v string)`

SetPermissions sets Permissions field to given value.


### GetLastActivity

`func (o *GroupMember) GetLastActivity() int32`

GetLastActivity returns the LastActivity field if non-nil, zero value otherwise.

### GetLastActivityOk

`func (o *GroupMember) GetLastActivityOk() (*int32, bool)`

GetLastActivityOk returns a tuple with the LastActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivity

`func (o *GroupMember) SetLastActivity(v int32)`

SetLastActivity sets LastActivity field to given value.


### GetOnline

`func (o *GroupMember) GetOnline() bool`

GetOnline returns the Online field if non-nil, zero value otherwise.

### GetOnlineOk

`func (o *GroupMember) GetOnlineOk() (*bool, bool)`

GetOnlineOk returns a tuple with the Online field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnline

`func (o *GroupMember) SetOnline(v bool)`

SetOnline sets Online field to given value.

### HasOnline

`func (o *GroupMember) HasOnline() bool`

HasOnline returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


