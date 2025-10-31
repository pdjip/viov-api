# GroupRank

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RankID** | **int32** |  | 
**GroupID** | **int32** |  | 
**Name** | **string** |  | 
**Bonus** | **int32** |  | 
**Leader** | **bool** |  | 

## Methods

### NewGroupRank

`func NewGroupRank(rankID int32, groupID int32, name string, bonus int32, leader bool, ) *GroupRank`

NewGroupRank instantiates a new GroupRank object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupRankWithDefaults

`func NewGroupRankWithDefaults() *GroupRank`

NewGroupRankWithDefaults instantiates a new GroupRank object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRankID

`func (o *GroupRank) GetRankID() int32`

GetRankID returns the RankID field if non-nil, zero value otherwise.

### GetRankIDOk

`func (o *GroupRank) GetRankIDOk() (*int32, bool)`

GetRankIDOk returns a tuple with the RankID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRankID

`func (o *GroupRank) SetRankID(v int32)`

SetRankID sets RankID field to given value.


### GetGroupID

`func (o *GroupRank) GetGroupID() int32`

GetGroupID returns the GroupID field if non-nil, zero value otherwise.

### GetGroupIDOk

`func (o *GroupRank) GetGroupIDOk() (*int32, bool)`

GetGroupIDOk returns a tuple with the GroupID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupID

`func (o *GroupRank) SetGroupID(v int32)`

SetGroupID sets GroupID field to given value.


### GetName

`func (o *GroupRank) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GroupRank) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GroupRank) SetName(v string)`

SetName sets Name field to given value.


### GetBonus

`func (o *GroupRank) GetBonus() int32`

GetBonus returns the Bonus field if non-nil, zero value otherwise.

### GetBonusOk

`func (o *GroupRank) GetBonusOk() (*int32, bool)`

GetBonusOk returns a tuple with the Bonus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBonus

`func (o *GroupRank) SetBonus(v int32)`

SetBonus sets Bonus field to given value.


### GetLeader

`func (o *GroupRank) GetLeader() bool`

GetLeader returns the Leader field if non-nil, zero value otherwise.

### GetLeaderOk

`func (o *GroupRank) GetLeaderOk() (*bool, bool)`

GetLeaderOk returns a tuple with the Leader field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeader

`func (o *GroupRank) SetLeader(v bool)`

SetLeader sets Leader field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


