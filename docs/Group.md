# Group

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ID** | **int32** |  | 
**Name** | **string** |  | 
**Exp** | **int32** |  | 
**Level** | **int32** |  | 
**Server** | **int32** |  | 
**Msg** | **string** |  | 
**R** | **int32** |  | 
**G** | **int32** |  | 
**B** | **int32** |  | 
**ChatR** | **int32** |  | 
**ChatG** | **int32** |  | 
**ChatB** | **int32** |  | 
**Memberlimit** | **int32** |  | 
**Tag** | **int32** |  | 
**Rang0** | **string** |  | 
**Rang1** | **string** |  | 
**Rang2** | Pointer to **string** |  | [optional] 
**Rang3** | Pointer to **string** |  | [optional] 
**Rang4** | **string** |  | 
**Rang5** | **string** |  | 
**ForumMember** | **int32** |  | 
**ForumAdmin** | **int32** |  | 
**Synced** | **int32** |  | 
**LastExp** | **int32** |  | 
**R2** | **int32** |  | 
**G2** | **int32** |  | 
**B2** | **int32** |  | 
**Type** | **string** |  | 
**Boost1** | **int32** |  | 
**SkinMale** | **string** |  | 
**SkinFemale** | **string** |  | 
**Boosts** | **string** |  | 
**Relationships** | **string** |  | 
**CraftingStorage** | **int32** |  | 
**LastExpCount** | **int32** |  | 
**LastActivity** | **int32** |  | 
**Tags** | **string** |  | 

## Methods

### NewGroup

`func NewGroup(iD int32, name string, exp int32, level int32, server int32, msg string, r int32, g int32, b int32, chatR int32, chatG int32, chatB int32, memberlimit int32, tag int32, rang0 string, rang1 string, rang4 string, rang5 string, forumMember int32, forumAdmin int32, synced int32, lastExp int32, r2 int32, g2 int32, b2 int32, type_ string, boost1 int32, skinMale string, skinFemale string, boosts string, relationships string, craftingStorage int32, lastExpCount int32, lastActivity int32, tags string, ) *Group`

NewGroup instantiates a new Group object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupWithDefaults

`func NewGroupWithDefaults() *Group`

NewGroupWithDefaults instantiates a new Group object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetID

`func (o *Group) GetID() int32`

GetID returns the ID field if non-nil, zero value otherwise.

### GetIDOk

`func (o *Group) GetIDOk() (*int32, bool)`

GetIDOk returns a tuple with the ID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetID

`func (o *Group) SetID(v int32)`

SetID sets ID field to given value.


### GetName

`func (o *Group) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Group) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Group) SetName(v string)`

SetName sets Name field to given value.


### GetExp

`func (o *Group) GetExp() int32`

GetExp returns the Exp field if non-nil, zero value otherwise.

### GetExpOk

`func (o *Group) GetExpOk() (*int32, bool)`

GetExpOk returns a tuple with the Exp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExp

`func (o *Group) SetExp(v int32)`

SetExp sets Exp field to given value.


### GetLevel

`func (o *Group) GetLevel() int32`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *Group) GetLevelOk() (*int32, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *Group) SetLevel(v int32)`

SetLevel sets Level field to given value.


### GetServer

`func (o *Group) GetServer() int32`

GetServer returns the Server field if non-nil, zero value otherwise.

### GetServerOk

`func (o *Group) GetServerOk() (*int32, bool)`

GetServerOk returns a tuple with the Server field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServer

`func (o *Group) SetServer(v int32)`

SetServer sets Server field to given value.


### GetMsg

`func (o *Group) GetMsg() string`

GetMsg returns the Msg field if non-nil, zero value otherwise.

### GetMsgOk

`func (o *Group) GetMsgOk() (*string, bool)`

GetMsgOk returns a tuple with the Msg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsg

`func (o *Group) SetMsg(v string)`

SetMsg sets Msg field to given value.


### GetR

`func (o *Group) GetR() int32`

GetR returns the R field if non-nil, zero value otherwise.

### GetROk

`func (o *Group) GetROk() (*int32, bool)`

GetROk returns a tuple with the R field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetR

`func (o *Group) SetR(v int32)`

SetR sets R field to given value.


### GetG

`func (o *Group) GetG() int32`

GetG returns the G field if non-nil, zero value otherwise.

### GetGOk

`func (o *Group) GetGOk() (*int32, bool)`

GetGOk returns a tuple with the G field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetG

`func (o *Group) SetG(v int32)`

SetG sets G field to given value.


### GetB

`func (o *Group) GetB() int32`

GetB returns the B field if non-nil, zero value otherwise.

### GetBOk

`func (o *Group) GetBOk() (*int32, bool)`

GetBOk returns a tuple with the B field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetB

`func (o *Group) SetB(v int32)`

SetB sets B field to given value.


### GetChatR

`func (o *Group) GetChatR() int32`

GetChatR returns the ChatR field if non-nil, zero value otherwise.

### GetChatROk

`func (o *Group) GetChatROk() (*int32, bool)`

GetChatROk returns a tuple with the ChatR field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChatR

`func (o *Group) SetChatR(v int32)`

SetChatR sets ChatR field to given value.


### GetChatG

`func (o *Group) GetChatG() int32`

GetChatG returns the ChatG field if non-nil, zero value otherwise.

### GetChatGOk

`func (o *Group) GetChatGOk() (*int32, bool)`

GetChatGOk returns a tuple with the ChatG field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChatG

`func (o *Group) SetChatG(v int32)`

SetChatG sets ChatG field to given value.


### GetChatB

`func (o *Group) GetChatB() int32`

GetChatB returns the ChatB field if non-nil, zero value otherwise.

### GetChatBOk

`func (o *Group) GetChatBOk() (*int32, bool)`

GetChatBOk returns a tuple with the ChatB field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChatB

`func (o *Group) SetChatB(v int32)`

SetChatB sets ChatB field to given value.


### GetMemberlimit

`func (o *Group) GetMemberlimit() int32`

GetMemberlimit returns the Memberlimit field if non-nil, zero value otherwise.

### GetMemberlimitOk

`func (o *Group) GetMemberlimitOk() (*int32, bool)`

GetMemberlimitOk returns a tuple with the Memberlimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemberlimit

`func (o *Group) SetMemberlimit(v int32)`

SetMemberlimit sets Memberlimit field to given value.


### GetTag

`func (o *Group) GetTag() int32`

GetTag returns the Tag field if non-nil, zero value otherwise.

### GetTagOk

`func (o *Group) GetTagOk() (*int32, bool)`

GetTagOk returns a tuple with the Tag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTag

`func (o *Group) SetTag(v int32)`

SetTag sets Tag field to given value.


### GetRang0

`func (o *Group) GetRang0() string`

GetRang0 returns the Rang0 field if non-nil, zero value otherwise.

### GetRang0Ok

`func (o *Group) GetRang0Ok() (*string, bool)`

GetRang0Ok returns a tuple with the Rang0 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRang0

`func (o *Group) SetRang0(v string)`

SetRang0 sets Rang0 field to given value.


### GetRang1

`func (o *Group) GetRang1() string`

GetRang1 returns the Rang1 field if non-nil, zero value otherwise.

### GetRang1Ok

`func (o *Group) GetRang1Ok() (*string, bool)`

GetRang1Ok returns a tuple with the Rang1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRang1

`func (o *Group) SetRang1(v string)`

SetRang1 sets Rang1 field to given value.


### GetRang2

`func (o *Group) GetRang2() string`

GetRang2 returns the Rang2 field if non-nil, zero value otherwise.

### GetRang2Ok

`func (o *Group) GetRang2Ok() (*string, bool)`

GetRang2Ok returns a tuple with the Rang2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRang2

`func (o *Group) SetRang2(v string)`

SetRang2 sets Rang2 field to given value.

### HasRang2

`func (o *Group) HasRang2() bool`

HasRang2 returns a boolean if a field has been set.

### GetRang3

`func (o *Group) GetRang3() string`

GetRang3 returns the Rang3 field if non-nil, zero value otherwise.

### GetRang3Ok

`func (o *Group) GetRang3Ok() (*string, bool)`

GetRang3Ok returns a tuple with the Rang3 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRang3

`func (o *Group) SetRang3(v string)`

SetRang3 sets Rang3 field to given value.

### HasRang3

`func (o *Group) HasRang3() bool`

HasRang3 returns a boolean if a field has been set.

### GetRang4

`func (o *Group) GetRang4() string`

GetRang4 returns the Rang4 field if non-nil, zero value otherwise.

### GetRang4Ok

`func (o *Group) GetRang4Ok() (*string, bool)`

GetRang4Ok returns a tuple with the Rang4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRang4

`func (o *Group) SetRang4(v string)`

SetRang4 sets Rang4 field to given value.


### GetRang5

`func (o *Group) GetRang5() string`

GetRang5 returns the Rang5 field if non-nil, zero value otherwise.

### GetRang5Ok

`func (o *Group) GetRang5Ok() (*string, bool)`

GetRang5Ok returns a tuple with the Rang5 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRang5

`func (o *Group) SetRang5(v string)`

SetRang5 sets Rang5 field to given value.


### GetForumMember

`func (o *Group) GetForumMember() int32`

GetForumMember returns the ForumMember field if non-nil, zero value otherwise.

### GetForumMemberOk

`func (o *Group) GetForumMemberOk() (*int32, bool)`

GetForumMemberOk returns a tuple with the ForumMember field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForumMember

`func (o *Group) SetForumMember(v int32)`

SetForumMember sets ForumMember field to given value.


### GetForumAdmin

`func (o *Group) GetForumAdmin() int32`

GetForumAdmin returns the ForumAdmin field if non-nil, zero value otherwise.

### GetForumAdminOk

`func (o *Group) GetForumAdminOk() (*int32, bool)`

GetForumAdminOk returns a tuple with the ForumAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForumAdmin

`func (o *Group) SetForumAdmin(v int32)`

SetForumAdmin sets ForumAdmin field to given value.


### GetSynced

`func (o *Group) GetSynced() int32`

GetSynced returns the Synced field if non-nil, zero value otherwise.

### GetSyncedOk

`func (o *Group) GetSyncedOk() (*int32, bool)`

GetSyncedOk returns a tuple with the Synced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSynced

`func (o *Group) SetSynced(v int32)`

SetSynced sets Synced field to given value.


### GetLastExp

`func (o *Group) GetLastExp() int32`

GetLastExp returns the LastExp field if non-nil, zero value otherwise.

### GetLastExpOk

`func (o *Group) GetLastExpOk() (*int32, bool)`

GetLastExpOk returns a tuple with the LastExp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastExp

`func (o *Group) SetLastExp(v int32)`

SetLastExp sets LastExp field to given value.


### GetR2

`func (o *Group) GetR2() int32`

GetR2 returns the R2 field if non-nil, zero value otherwise.

### GetR2Ok

`func (o *Group) GetR2Ok() (*int32, bool)`

GetR2Ok returns a tuple with the R2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetR2

`func (o *Group) SetR2(v int32)`

SetR2 sets R2 field to given value.


### GetG2

`func (o *Group) GetG2() int32`

GetG2 returns the G2 field if non-nil, zero value otherwise.

### GetG2Ok

`func (o *Group) GetG2Ok() (*int32, bool)`

GetG2Ok returns a tuple with the G2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetG2

`func (o *Group) SetG2(v int32)`

SetG2 sets G2 field to given value.


### GetB2

`func (o *Group) GetB2() int32`

GetB2 returns the B2 field if non-nil, zero value otherwise.

### GetB2Ok

`func (o *Group) GetB2Ok() (*int32, bool)`

GetB2Ok returns a tuple with the B2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetB2

`func (o *Group) SetB2(v int32)`

SetB2 sets B2 field to given value.


### GetType

`func (o *Group) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Group) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Group) SetType(v string)`

SetType sets Type field to given value.


### GetBoost1

`func (o *Group) GetBoost1() int32`

GetBoost1 returns the Boost1 field if non-nil, zero value otherwise.

### GetBoost1Ok

`func (o *Group) GetBoost1Ok() (*int32, bool)`

GetBoost1Ok returns a tuple with the Boost1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoost1

`func (o *Group) SetBoost1(v int32)`

SetBoost1 sets Boost1 field to given value.


### GetSkinMale

`func (o *Group) GetSkinMale() string`

GetSkinMale returns the SkinMale field if non-nil, zero value otherwise.

### GetSkinMaleOk

`func (o *Group) GetSkinMaleOk() (*string, bool)`

GetSkinMaleOk returns a tuple with the SkinMale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkinMale

`func (o *Group) SetSkinMale(v string)`

SetSkinMale sets SkinMale field to given value.


### GetSkinFemale

`func (o *Group) GetSkinFemale() string`

GetSkinFemale returns the SkinFemale field if non-nil, zero value otherwise.

### GetSkinFemaleOk

`func (o *Group) GetSkinFemaleOk() (*string, bool)`

GetSkinFemaleOk returns a tuple with the SkinFemale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkinFemale

`func (o *Group) SetSkinFemale(v string)`

SetSkinFemale sets SkinFemale field to given value.


### GetBoosts

`func (o *Group) GetBoosts() string`

GetBoosts returns the Boosts field if non-nil, zero value otherwise.

### GetBoostsOk

`func (o *Group) GetBoostsOk() (*string, bool)`

GetBoostsOk returns a tuple with the Boosts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoosts

`func (o *Group) SetBoosts(v string)`

SetBoosts sets Boosts field to given value.


### GetRelationships

`func (o *Group) GetRelationships() string`

GetRelationships returns the Relationships field if non-nil, zero value otherwise.

### GetRelationshipsOk

`func (o *Group) GetRelationshipsOk() (*string, bool)`

GetRelationshipsOk returns a tuple with the Relationships field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelationships

`func (o *Group) SetRelationships(v string)`

SetRelationships sets Relationships field to given value.


### GetCraftingStorage

`func (o *Group) GetCraftingStorage() int32`

GetCraftingStorage returns the CraftingStorage field if non-nil, zero value otherwise.

### GetCraftingStorageOk

`func (o *Group) GetCraftingStorageOk() (*int32, bool)`

GetCraftingStorageOk returns a tuple with the CraftingStorage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCraftingStorage

`func (o *Group) SetCraftingStorage(v int32)`

SetCraftingStorage sets CraftingStorage field to given value.


### GetLastExpCount

`func (o *Group) GetLastExpCount() int32`

GetLastExpCount returns the LastExpCount field if non-nil, zero value otherwise.

### GetLastExpCountOk

`func (o *Group) GetLastExpCountOk() (*int32, bool)`

GetLastExpCountOk returns a tuple with the LastExpCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastExpCount

`func (o *Group) SetLastExpCount(v int32)`

SetLastExpCount sets LastExpCount field to given value.


### GetLastActivity

`func (o *Group) GetLastActivity() int32`

GetLastActivity returns the LastActivity field if non-nil, zero value otherwise.

### GetLastActivityOk

`func (o *Group) GetLastActivityOk() (*int32, bool)`

GetLastActivityOk returns a tuple with the LastActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivity

`func (o *Group) SetLastActivity(v int32)`

SetLastActivity sets LastActivity field to given value.


### GetTags

`func (o *Group) GetTags() string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *Group) GetTagsOk() (*string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *Group) SetTags(v string)`

SetTags sets Tags field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


