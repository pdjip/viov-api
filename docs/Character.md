# Character

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ID** | Pointer to **int32** |  | [optional] 
**AccountID** | **int32** |  | 
**Name** | **string** |  | 
**Playingtime** | Pointer to **int32** |  | [optional] 
**Gender** | **int32** |  | 
**STVO** | **int32** |  | 
**VehicleLimit** | **int32** |  | 
**BusExp** | Pointer to **int32** |  | [optional] 
**Spawn** | Pointer to **string** |  | [optional] 
**SpawnID** | Pointer to **int32** |  | [optional] 
**Wanteds** | Pointer to **int32** |  | [optional] 
**JailTime** | Pointer to **int32** |  | [optional] 
**MethTime** | Pointer to **int32** |  | [optional] 
**WeaponLicenseA** | Pointer to **int32** |  | [optional] 
**WeaponLicenseB** | Pointer to **int32** |  | [optional] 
**WeaponLicenseC** | Pointer to **int32** |  | [optional] 
**ActivityTimestamp** | Pointer to **int32** |  | [optional] 
**QuestID** | **string** |  | 
**QuestStatus** | Pointer to **int32** |  | [optional] 
**PhoneNumber** | Pointer to **int32** |  | [optional] 
**FactionTime** | Pointer to **int32** |  | [optional] 
**Grade** | Pointer to **float64** |  | [optional] 
**Raiting** | **int32** |  | 
**DrivingLicenseA** | Pointer to **int32** |  | [optional] 
**FoodStatus** | **int32** |  | 
**ActivityStep** | **int32** |  | 
**DrivingLicensesBlockedTimestamp** | Pointer to **int32** |  | [optional] 
**WantedArchiv** | Pointer to **string** |  | [optional] 
**Skin** | Pointer to **string** |  | [optional] 
**Skills** | Pointer to **string** |  | [optional] 
**DailyQuests** | Pointer to **string** |  | [optional] 
**BonusVehicleLimit** | Pointer to **int32** |  | [optional] 
**Accessory** | Pointer to **string** |  | [optional] 
**Achievements** | Pointer to **string** |  | [optional] 
**TotalStatus** | Pointer to **string** |  | [optional] 
**ActiveStatus** | Pointer to **string** |  | [optional] 
**SkillPoints** | Pointer to **string** |  | [optional] 
**SkillBranches** | Pointer to **string** |  | [optional] 
**SkillSync** | **int32** |  | 
**ExpBoost** | Pointer to **int32** |  | [optional] 
**Tattoos** | Pointer to **string** |  | [optional] 
**Licenses** | Pointer to **string** |  | [optional] 
**DailyBonus** | Pointer to **string** |  | [optional] 

## Methods

### NewCharacter

`func NewCharacter(accountID int32, name string, gender int32, sTVO int32, vehicleLimit int32, questID string, raiting int32, foodStatus int32, activityStep int32, skillSync int32, ) *Character`

NewCharacter instantiates a new Character object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCharacterWithDefaults

`func NewCharacterWithDefaults() *Character`

NewCharacterWithDefaults instantiates a new Character object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetID

`func (o *Character) GetID() int32`

GetID returns the ID field if non-nil, zero value otherwise.

### GetIDOk

`func (o *Character) GetIDOk() (*int32, bool)`

GetIDOk returns a tuple with the ID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetID

`func (o *Character) SetID(v int32)`

SetID sets ID field to given value.

### HasID

`func (o *Character) HasID() bool`

HasID returns a boolean if a field has been set.

### GetAccountID

`func (o *Character) GetAccountID() int32`

GetAccountID returns the AccountID field if non-nil, zero value otherwise.

### GetAccountIDOk

`func (o *Character) GetAccountIDOk() (*int32, bool)`

GetAccountIDOk returns a tuple with the AccountID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountID

`func (o *Character) SetAccountID(v int32)`

SetAccountID sets AccountID field to given value.


### GetName

`func (o *Character) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Character) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Character) SetName(v string)`

SetName sets Name field to given value.


### GetPlayingtime

`func (o *Character) GetPlayingtime() int32`

GetPlayingtime returns the Playingtime field if non-nil, zero value otherwise.

### GetPlayingtimeOk

`func (o *Character) GetPlayingtimeOk() (*int32, bool)`

GetPlayingtimeOk returns a tuple with the Playingtime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayingtime

`func (o *Character) SetPlayingtime(v int32)`

SetPlayingtime sets Playingtime field to given value.

### HasPlayingtime

`func (o *Character) HasPlayingtime() bool`

HasPlayingtime returns a boolean if a field has been set.

### GetGender

`func (o *Character) GetGender() int32`

GetGender returns the Gender field if non-nil, zero value otherwise.

### GetGenderOk

`func (o *Character) GetGenderOk() (*int32, bool)`

GetGenderOk returns a tuple with the Gender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGender

`func (o *Character) SetGender(v int32)`

SetGender sets Gender field to given value.


### GetSTVO

`func (o *Character) GetSTVO() int32`

GetSTVO returns the STVO field if non-nil, zero value otherwise.

### GetSTVOOk

`func (o *Character) GetSTVOOk() (*int32, bool)`

GetSTVOOk returns a tuple with the STVO field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSTVO

`func (o *Character) SetSTVO(v int32)`

SetSTVO sets STVO field to given value.


### GetVehicleLimit

`func (o *Character) GetVehicleLimit() int32`

GetVehicleLimit returns the VehicleLimit field if non-nil, zero value otherwise.

### GetVehicleLimitOk

`func (o *Character) GetVehicleLimitOk() (*int32, bool)`

GetVehicleLimitOk returns a tuple with the VehicleLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVehicleLimit

`func (o *Character) SetVehicleLimit(v int32)`

SetVehicleLimit sets VehicleLimit field to given value.


### GetBusExp

`func (o *Character) GetBusExp() int32`

GetBusExp returns the BusExp field if non-nil, zero value otherwise.

### GetBusExpOk

`func (o *Character) GetBusExpOk() (*int32, bool)`

GetBusExpOk returns a tuple with the BusExp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusExp

`func (o *Character) SetBusExp(v int32)`

SetBusExp sets BusExp field to given value.

### HasBusExp

`func (o *Character) HasBusExp() bool`

HasBusExp returns a boolean if a field has been set.

### GetSpawn

`func (o *Character) GetSpawn() string`

GetSpawn returns the Spawn field if non-nil, zero value otherwise.

### GetSpawnOk

`func (o *Character) GetSpawnOk() (*string, bool)`

GetSpawnOk returns a tuple with the Spawn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpawn

`func (o *Character) SetSpawn(v string)`

SetSpawn sets Spawn field to given value.

### HasSpawn

`func (o *Character) HasSpawn() bool`

HasSpawn returns a boolean if a field has been set.

### GetSpawnID

`func (o *Character) GetSpawnID() int32`

GetSpawnID returns the SpawnID field if non-nil, zero value otherwise.

### GetSpawnIDOk

`func (o *Character) GetSpawnIDOk() (*int32, bool)`

GetSpawnIDOk returns a tuple with the SpawnID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpawnID

`func (o *Character) SetSpawnID(v int32)`

SetSpawnID sets SpawnID field to given value.

### HasSpawnID

`func (o *Character) HasSpawnID() bool`

HasSpawnID returns a boolean if a field has been set.

### GetWanteds

`func (o *Character) GetWanteds() int32`

GetWanteds returns the Wanteds field if non-nil, zero value otherwise.

### GetWantedsOk

`func (o *Character) GetWantedsOk() (*int32, bool)`

GetWantedsOk returns a tuple with the Wanteds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWanteds

`func (o *Character) SetWanteds(v int32)`

SetWanteds sets Wanteds field to given value.

### HasWanteds

`func (o *Character) HasWanteds() bool`

HasWanteds returns a boolean if a field has been set.

### GetJailTime

`func (o *Character) GetJailTime() int32`

GetJailTime returns the JailTime field if non-nil, zero value otherwise.

### GetJailTimeOk

`func (o *Character) GetJailTimeOk() (*int32, bool)`

GetJailTimeOk returns a tuple with the JailTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJailTime

`func (o *Character) SetJailTime(v int32)`

SetJailTime sets JailTime field to given value.

### HasJailTime

`func (o *Character) HasJailTime() bool`

HasJailTime returns a boolean if a field has been set.

### GetMethTime

`func (o *Character) GetMethTime() int32`

GetMethTime returns the MethTime field if non-nil, zero value otherwise.

### GetMethTimeOk

`func (o *Character) GetMethTimeOk() (*int32, bool)`

GetMethTimeOk returns a tuple with the MethTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethTime

`func (o *Character) SetMethTime(v int32)`

SetMethTime sets MethTime field to given value.

### HasMethTime

`func (o *Character) HasMethTime() bool`

HasMethTime returns a boolean if a field has been set.

### GetWeaponLicenseA

`func (o *Character) GetWeaponLicenseA() int32`

GetWeaponLicenseA returns the WeaponLicenseA field if non-nil, zero value otherwise.

### GetWeaponLicenseAOk

`func (o *Character) GetWeaponLicenseAOk() (*int32, bool)`

GetWeaponLicenseAOk returns a tuple with the WeaponLicenseA field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeaponLicenseA

`func (o *Character) SetWeaponLicenseA(v int32)`

SetWeaponLicenseA sets WeaponLicenseA field to given value.

### HasWeaponLicenseA

`func (o *Character) HasWeaponLicenseA() bool`

HasWeaponLicenseA returns a boolean if a field has been set.

### GetWeaponLicenseB

`func (o *Character) GetWeaponLicenseB() int32`

GetWeaponLicenseB returns the WeaponLicenseB field if non-nil, zero value otherwise.

### GetWeaponLicenseBOk

`func (o *Character) GetWeaponLicenseBOk() (*int32, bool)`

GetWeaponLicenseBOk returns a tuple with the WeaponLicenseB field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeaponLicenseB

`func (o *Character) SetWeaponLicenseB(v int32)`

SetWeaponLicenseB sets WeaponLicenseB field to given value.

### HasWeaponLicenseB

`func (o *Character) HasWeaponLicenseB() bool`

HasWeaponLicenseB returns a boolean if a field has been set.

### GetWeaponLicenseC

`func (o *Character) GetWeaponLicenseC() int32`

GetWeaponLicenseC returns the WeaponLicenseC field if non-nil, zero value otherwise.

### GetWeaponLicenseCOk

`func (o *Character) GetWeaponLicenseCOk() (*int32, bool)`

GetWeaponLicenseCOk returns a tuple with the WeaponLicenseC field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeaponLicenseC

`func (o *Character) SetWeaponLicenseC(v int32)`

SetWeaponLicenseC sets WeaponLicenseC field to given value.

### HasWeaponLicenseC

`func (o *Character) HasWeaponLicenseC() bool`

HasWeaponLicenseC returns a boolean if a field has been set.

### GetActivityTimestamp

`func (o *Character) GetActivityTimestamp() int32`

GetActivityTimestamp returns the ActivityTimestamp field if non-nil, zero value otherwise.

### GetActivityTimestampOk

`func (o *Character) GetActivityTimestampOk() (*int32, bool)`

GetActivityTimestampOk returns a tuple with the ActivityTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityTimestamp

`func (o *Character) SetActivityTimestamp(v int32)`

SetActivityTimestamp sets ActivityTimestamp field to given value.

### HasActivityTimestamp

`func (o *Character) HasActivityTimestamp() bool`

HasActivityTimestamp returns a boolean if a field has been set.

### GetQuestID

`func (o *Character) GetQuestID() string`

GetQuestID returns the QuestID field if non-nil, zero value otherwise.

### GetQuestIDOk

`func (o *Character) GetQuestIDOk() (*string, bool)`

GetQuestIDOk returns a tuple with the QuestID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestID

`func (o *Character) SetQuestID(v string)`

SetQuestID sets QuestID field to given value.


### GetQuestStatus

`func (o *Character) GetQuestStatus() int32`

GetQuestStatus returns the QuestStatus field if non-nil, zero value otherwise.

### GetQuestStatusOk

`func (o *Character) GetQuestStatusOk() (*int32, bool)`

GetQuestStatusOk returns a tuple with the QuestStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestStatus

`func (o *Character) SetQuestStatus(v int32)`

SetQuestStatus sets QuestStatus field to given value.

### HasQuestStatus

`func (o *Character) HasQuestStatus() bool`

HasQuestStatus returns a boolean if a field has been set.

### GetPhoneNumber

`func (o *Character) GetPhoneNumber() int32`

GetPhoneNumber returns the PhoneNumber field if non-nil, zero value otherwise.

### GetPhoneNumberOk

`func (o *Character) GetPhoneNumberOk() (*int32, bool)`

GetPhoneNumberOk returns a tuple with the PhoneNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhoneNumber

`func (o *Character) SetPhoneNumber(v int32)`

SetPhoneNumber sets PhoneNumber field to given value.

### HasPhoneNumber

`func (o *Character) HasPhoneNumber() bool`

HasPhoneNumber returns a boolean if a field has been set.

### GetFactionTime

`func (o *Character) GetFactionTime() int32`

GetFactionTime returns the FactionTime field if non-nil, zero value otherwise.

### GetFactionTimeOk

`func (o *Character) GetFactionTimeOk() (*int32, bool)`

GetFactionTimeOk returns a tuple with the FactionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFactionTime

`func (o *Character) SetFactionTime(v int32)`

SetFactionTime sets FactionTime field to given value.

### HasFactionTime

`func (o *Character) HasFactionTime() bool`

HasFactionTime returns a boolean if a field has been set.

### GetGrade

`func (o *Character) GetGrade() float64`

GetGrade returns the Grade field if non-nil, zero value otherwise.

### GetGradeOk

`func (o *Character) GetGradeOk() (*float64, bool)`

GetGradeOk returns a tuple with the Grade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrade

`func (o *Character) SetGrade(v float64)`

SetGrade sets Grade field to given value.

### HasGrade

`func (o *Character) HasGrade() bool`

HasGrade returns a boolean if a field has been set.

### GetRaiting

`func (o *Character) GetRaiting() int32`

GetRaiting returns the Raiting field if non-nil, zero value otherwise.

### GetRaitingOk

`func (o *Character) GetRaitingOk() (*int32, bool)`

GetRaitingOk returns a tuple with the Raiting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRaiting

`func (o *Character) SetRaiting(v int32)`

SetRaiting sets Raiting field to given value.


### GetDrivingLicenseA

`func (o *Character) GetDrivingLicenseA() int32`

GetDrivingLicenseA returns the DrivingLicenseA field if non-nil, zero value otherwise.

### GetDrivingLicenseAOk

`func (o *Character) GetDrivingLicenseAOk() (*int32, bool)`

GetDrivingLicenseAOk returns a tuple with the DrivingLicenseA field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDrivingLicenseA

`func (o *Character) SetDrivingLicenseA(v int32)`

SetDrivingLicenseA sets DrivingLicenseA field to given value.

### HasDrivingLicenseA

`func (o *Character) HasDrivingLicenseA() bool`

HasDrivingLicenseA returns a boolean if a field has been set.

### GetFoodStatus

`func (o *Character) GetFoodStatus() int32`

GetFoodStatus returns the FoodStatus field if non-nil, zero value otherwise.

### GetFoodStatusOk

`func (o *Character) GetFoodStatusOk() (*int32, bool)`

GetFoodStatusOk returns a tuple with the FoodStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFoodStatus

`func (o *Character) SetFoodStatus(v int32)`

SetFoodStatus sets FoodStatus field to given value.


### GetActivityStep

`func (o *Character) GetActivityStep() int32`

GetActivityStep returns the ActivityStep field if non-nil, zero value otherwise.

### GetActivityStepOk

`func (o *Character) GetActivityStepOk() (*int32, bool)`

GetActivityStepOk returns a tuple with the ActivityStep field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityStep

`func (o *Character) SetActivityStep(v int32)`

SetActivityStep sets ActivityStep field to given value.


### GetDrivingLicensesBlockedTimestamp

`func (o *Character) GetDrivingLicensesBlockedTimestamp() int32`

GetDrivingLicensesBlockedTimestamp returns the DrivingLicensesBlockedTimestamp field if non-nil, zero value otherwise.

### GetDrivingLicensesBlockedTimestampOk

`func (o *Character) GetDrivingLicensesBlockedTimestampOk() (*int32, bool)`

GetDrivingLicensesBlockedTimestampOk returns a tuple with the DrivingLicensesBlockedTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDrivingLicensesBlockedTimestamp

`func (o *Character) SetDrivingLicensesBlockedTimestamp(v int32)`

SetDrivingLicensesBlockedTimestamp sets DrivingLicensesBlockedTimestamp field to given value.

### HasDrivingLicensesBlockedTimestamp

`func (o *Character) HasDrivingLicensesBlockedTimestamp() bool`

HasDrivingLicensesBlockedTimestamp returns a boolean if a field has been set.

### GetWantedArchiv

`func (o *Character) GetWantedArchiv() string`

GetWantedArchiv returns the WantedArchiv field if non-nil, zero value otherwise.

### GetWantedArchivOk

`func (o *Character) GetWantedArchivOk() (*string, bool)`

GetWantedArchivOk returns a tuple with the WantedArchiv field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWantedArchiv

`func (o *Character) SetWantedArchiv(v string)`

SetWantedArchiv sets WantedArchiv field to given value.

### HasWantedArchiv

`func (o *Character) HasWantedArchiv() bool`

HasWantedArchiv returns a boolean if a field has been set.

### GetSkin

`func (o *Character) GetSkin() string`

GetSkin returns the Skin field if non-nil, zero value otherwise.

### GetSkinOk

`func (o *Character) GetSkinOk() (*string, bool)`

GetSkinOk returns a tuple with the Skin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkin

`func (o *Character) SetSkin(v string)`

SetSkin sets Skin field to given value.

### HasSkin

`func (o *Character) HasSkin() bool`

HasSkin returns a boolean if a field has been set.

### GetSkills

`func (o *Character) GetSkills() string`

GetSkills returns the Skills field if non-nil, zero value otherwise.

### GetSkillsOk

`func (o *Character) GetSkillsOk() (*string, bool)`

GetSkillsOk returns a tuple with the Skills field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkills

`func (o *Character) SetSkills(v string)`

SetSkills sets Skills field to given value.

### HasSkills

`func (o *Character) HasSkills() bool`

HasSkills returns a boolean if a field has been set.

### GetDailyQuests

`func (o *Character) GetDailyQuests() string`

GetDailyQuests returns the DailyQuests field if non-nil, zero value otherwise.

### GetDailyQuestsOk

`func (o *Character) GetDailyQuestsOk() (*string, bool)`

GetDailyQuestsOk returns a tuple with the DailyQuests field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyQuests

`func (o *Character) SetDailyQuests(v string)`

SetDailyQuests sets DailyQuests field to given value.

### HasDailyQuests

`func (o *Character) HasDailyQuests() bool`

HasDailyQuests returns a boolean if a field has been set.

### GetBonusVehicleLimit

`func (o *Character) GetBonusVehicleLimit() int32`

GetBonusVehicleLimit returns the BonusVehicleLimit field if non-nil, zero value otherwise.

### GetBonusVehicleLimitOk

`func (o *Character) GetBonusVehicleLimitOk() (*int32, bool)`

GetBonusVehicleLimitOk returns a tuple with the BonusVehicleLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBonusVehicleLimit

`func (o *Character) SetBonusVehicleLimit(v int32)`

SetBonusVehicleLimit sets BonusVehicleLimit field to given value.

### HasBonusVehicleLimit

`func (o *Character) HasBonusVehicleLimit() bool`

HasBonusVehicleLimit returns a boolean if a field has been set.

### GetAccessory

`func (o *Character) GetAccessory() string`

GetAccessory returns the Accessory field if non-nil, zero value otherwise.

### GetAccessoryOk

`func (o *Character) GetAccessoryOk() (*string, bool)`

GetAccessoryOk returns a tuple with the Accessory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessory

`func (o *Character) SetAccessory(v string)`

SetAccessory sets Accessory field to given value.

### HasAccessory

`func (o *Character) HasAccessory() bool`

HasAccessory returns a boolean if a field has been set.

### GetAchievements

`func (o *Character) GetAchievements() string`

GetAchievements returns the Achievements field if non-nil, zero value otherwise.

### GetAchievementsOk

`func (o *Character) GetAchievementsOk() (*string, bool)`

GetAchievementsOk returns a tuple with the Achievements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAchievements

`func (o *Character) SetAchievements(v string)`

SetAchievements sets Achievements field to given value.

### HasAchievements

`func (o *Character) HasAchievements() bool`

HasAchievements returns a boolean if a field has been set.

### GetTotalStatus

`func (o *Character) GetTotalStatus() string`

GetTotalStatus returns the TotalStatus field if non-nil, zero value otherwise.

### GetTotalStatusOk

`func (o *Character) GetTotalStatusOk() (*string, bool)`

GetTotalStatusOk returns a tuple with the TotalStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalStatus

`func (o *Character) SetTotalStatus(v string)`

SetTotalStatus sets TotalStatus field to given value.

### HasTotalStatus

`func (o *Character) HasTotalStatus() bool`

HasTotalStatus returns a boolean if a field has been set.

### GetActiveStatus

`func (o *Character) GetActiveStatus() string`

GetActiveStatus returns the ActiveStatus field if non-nil, zero value otherwise.

### GetActiveStatusOk

`func (o *Character) GetActiveStatusOk() (*string, bool)`

GetActiveStatusOk returns a tuple with the ActiveStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveStatus

`func (o *Character) SetActiveStatus(v string)`

SetActiveStatus sets ActiveStatus field to given value.

### HasActiveStatus

`func (o *Character) HasActiveStatus() bool`

HasActiveStatus returns a boolean if a field has been set.

### GetSkillPoints

`func (o *Character) GetSkillPoints() string`

GetSkillPoints returns the SkillPoints field if non-nil, zero value otherwise.

### GetSkillPointsOk

`func (o *Character) GetSkillPointsOk() (*string, bool)`

GetSkillPointsOk returns a tuple with the SkillPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkillPoints

`func (o *Character) SetSkillPoints(v string)`

SetSkillPoints sets SkillPoints field to given value.

### HasSkillPoints

`func (o *Character) HasSkillPoints() bool`

HasSkillPoints returns a boolean if a field has been set.

### GetSkillBranches

`func (o *Character) GetSkillBranches() string`

GetSkillBranches returns the SkillBranches field if non-nil, zero value otherwise.

### GetSkillBranchesOk

`func (o *Character) GetSkillBranchesOk() (*string, bool)`

GetSkillBranchesOk returns a tuple with the SkillBranches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkillBranches

`func (o *Character) SetSkillBranches(v string)`

SetSkillBranches sets SkillBranches field to given value.

### HasSkillBranches

`func (o *Character) HasSkillBranches() bool`

HasSkillBranches returns a boolean if a field has been set.

### GetSkillSync

`func (o *Character) GetSkillSync() int32`

GetSkillSync returns the SkillSync field if non-nil, zero value otherwise.

### GetSkillSyncOk

`func (o *Character) GetSkillSyncOk() (*int32, bool)`

GetSkillSyncOk returns a tuple with the SkillSync field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkillSync

`func (o *Character) SetSkillSync(v int32)`

SetSkillSync sets SkillSync field to given value.


### GetExpBoost

`func (o *Character) GetExpBoost() int32`

GetExpBoost returns the ExpBoost field if non-nil, zero value otherwise.

### GetExpBoostOk

`func (o *Character) GetExpBoostOk() (*int32, bool)`

GetExpBoostOk returns a tuple with the ExpBoost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpBoost

`func (o *Character) SetExpBoost(v int32)`

SetExpBoost sets ExpBoost field to given value.

### HasExpBoost

`func (o *Character) HasExpBoost() bool`

HasExpBoost returns a boolean if a field has been set.

### GetTattoos

`func (o *Character) GetTattoos() string`

GetTattoos returns the Tattoos field if non-nil, zero value otherwise.

### GetTattoosOk

`func (o *Character) GetTattoosOk() (*string, bool)`

GetTattoosOk returns a tuple with the Tattoos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTattoos

`func (o *Character) SetTattoos(v string)`

SetTattoos sets Tattoos field to given value.

### HasTattoos

`func (o *Character) HasTattoos() bool`

HasTattoos returns a boolean if a field has been set.

### GetLicenses

`func (o *Character) GetLicenses() string`

GetLicenses returns the Licenses field if non-nil, zero value otherwise.

### GetLicensesOk

`func (o *Character) GetLicensesOk() (*string, bool)`

GetLicensesOk returns a tuple with the Licenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenses

`func (o *Character) SetLicenses(v string)`

SetLicenses sets Licenses field to given value.

### HasLicenses

`func (o *Character) HasLicenses() bool`

HasLicenses returns a boolean if a field has been set.

### GetDailyBonus

`func (o *Character) GetDailyBonus() string`

GetDailyBonus returns the DailyBonus field if non-nil, zero value otherwise.

### GetDailyBonusOk

`func (o *Character) GetDailyBonusOk() (*string, bool)`

GetDailyBonusOk returns a tuple with the DailyBonus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyBonus

`func (o *Character) SetDailyBonus(v string)`

SetDailyBonus sets DailyBonus field to given value.

### HasDailyBonus

`func (o *Character) HasDailyBonus() bool`

HasDailyBonus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


