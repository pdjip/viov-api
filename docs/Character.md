# Character

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ID** | **int32** |  | 
**AccountID** | **int32** |  | 
**Name** | **string** |  | 
**Playingtime** | **int32** |  | 
**Gender** | **int32** |  | 
**STVO** | **int32** |  | 
**VehicleLimit** | **int32** |  | 
**BusExp** | **int32** |  | 
**Spawn** | **string** |  | 
**SpawnID** | **int32** |  | 
**Wanteds** | **int32** |  | 
**JailTime** | **int32** |  | 
**MethTime** | **int32** |  | 
**WeaponLicenseA** | **int32** |  | 
**WeaponLicenseB** | **int32** |  | 
**WeaponLicenseC** | **int32** |  | 
**ActivityTimestamp** | **int32** |  | 
**QuestID** | **string** |  | 
**QuestStatus** | **int32** |  | 
**PhoneNumber** | **int32** |  | 
**FactionTime** | **int32** |  | 
**Grade** | **float64** |  | 
**Raiting** | **float64** |  | 
**DrivingLicenseA** | **int32** |  | 
**FoodStatus** | **int32** |  | 
**ActivityStep** | **int32** |  | 
**DrivingLicensesBlockedTimestamp** | **int32** |  | 
**WantedArchiv** | **string** |  | 
**Skin** | **string** |  | 
**Skills** | **string** |  | 
**DailyQuests** | **string** |  | 
**BonusVehicleLimit** | **int32** |  | 
**Accessory** | **string** |  | 
**Achievements** | **string** |  | 
**TotalStatus** | **string** |  | 
**ActiveStatus** | **string** |  | 
**SkillPoints** | **string** |  | 
**SkillBranches** | **string** |  | 
**SkillSync** | **int32** |  | 
**Boosts** | **string** |  | 
**Tattoos** | **string** |  | 
**Licenses** | **string** |  | 
**DailyBonus** | **string** |  | 
**SeasonPass** | **string** |  | 
**SeasonPassPoints** | **float64** |  | 
**SeasonPassPremium** | **int32** |  | 
**WeaponsSkins** | **string** |  | 
**VehiclesSkins** | **string** |  | 
**HalloweenCount** | **int32** |  | 
**LoginTimestamp** | **int32** |  | 
**RegisterTimestamp** | **time.Time** |  | 

## Methods

### NewCharacter

`func NewCharacter(iD int32, accountID int32, name string, playingtime int32, gender int32, sTVO int32, vehicleLimit int32, busExp int32, spawn string, spawnID int32, wanteds int32, jailTime int32, methTime int32, weaponLicenseA int32, weaponLicenseB int32, weaponLicenseC int32, activityTimestamp int32, questID string, questStatus int32, phoneNumber int32, factionTime int32, grade float64, raiting float64, drivingLicenseA int32, foodStatus int32, activityStep int32, drivingLicensesBlockedTimestamp int32, wantedArchiv string, skin string, skills string, dailyQuests string, bonusVehicleLimit int32, accessory string, achievements string, totalStatus string, activeStatus string, skillPoints string, skillBranches string, skillSync int32, boosts string, tattoos string, licenses string, dailyBonus string, seasonPass string, seasonPassPoints float64, seasonPassPremium int32, weaponsSkins string, vehiclesSkins string, halloweenCount int32, loginTimestamp int32, registerTimestamp time.Time, ) *Character`

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


### GetRaiting

`func (o *Character) GetRaiting() float64`

GetRaiting returns the Raiting field if non-nil, zero value otherwise.

### GetRaitingOk

`func (o *Character) GetRaitingOk() (*float64, bool)`

GetRaitingOk returns a tuple with the Raiting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRaiting

`func (o *Character) SetRaiting(v float64)`

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


### GetBoosts

`func (o *Character) GetBoosts() string`

GetBoosts returns the Boosts field if non-nil, zero value otherwise.

### GetBoostsOk

`func (o *Character) GetBoostsOk() (*string, bool)`

GetBoostsOk returns a tuple with the Boosts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoosts

`func (o *Character) SetBoosts(v string)`

SetBoosts sets Boosts field to given value.


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


### GetSeasonPass

`func (o *Character) GetSeasonPass() string`

GetSeasonPass returns the SeasonPass field if non-nil, zero value otherwise.

### GetSeasonPassOk

`func (o *Character) GetSeasonPassOk() (*string, bool)`

GetSeasonPassOk returns a tuple with the SeasonPass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeasonPass

`func (o *Character) SetSeasonPass(v string)`

SetSeasonPass sets SeasonPass field to given value.


### GetSeasonPassPoints

`func (o *Character) GetSeasonPassPoints() float64`

GetSeasonPassPoints returns the SeasonPassPoints field if non-nil, zero value otherwise.

### GetSeasonPassPointsOk

`func (o *Character) GetSeasonPassPointsOk() (*float64, bool)`

GetSeasonPassPointsOk returns a tuple with the SeasonPassPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeasonPassPoints

`func (o *Character) SetSeasonPassPoints(v float64)`

SetSeasonPassPoints sets SeasonPassPoints field to given value.


### GetSeasonPassPremium

`func (o *Character) GetSeasonPassPremium() int32`

GetSeasonPassPremium returns the SeasonPassPremium field if non-nil, zero value otherwise.

### GetSeasonPassPremiumOk

`func (o *Character) GetSeasonPassPremiumOk() (*int32, bool)`

GetSeasonPassPremiumOk returns a tuple with the SeasonPassPremium field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeasonPassPremium

`func (o *Character) SetSeasonPassPremium(v int32)`

SetSeasonPassPremium sets SeasonPassPremium field to given value.


### GetWeaponsSkins

`func (o *Character) GetWeaponsSkins() string`

GetWeaponsSkins returns the WeaponsSkins field if non-nil, zero value otherwise.

### GetWeaponsSkinsOk

`func (o *Character) GetWeaponsSkinsOk() (*string, bool)`

GetWeaponsSkinsOk returns a tuple with the WeaponsSkins field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeaponsSkins

`func (o *Character) SetWeaponsSkins(v string)`

SetWeaponsSkins sets WeaponsSkins field to given value.


### GetVehiclesSkins

`func (o *Character) GetVehiclesSkins() string`

GetVehiclesSkins returns the VehiclesSkins field if non-nil, zero value otherwise.

### GetVehiclesSkinsOk

`func (o *Character) GetVehiclesSkinsOk() (*string, bool)`

GetVehiclesSkinsOk returns a tuple with the VehiclesSkins field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVehiclesSkins

`func (o *Character) SetVehiclesSkins(v string)`

SetVehiclesSkins sets VehiclesSkins field to given value.


### GetHalloweenCount

`func (o *Character) GetHalloweenCount() int32`

GetHalloweenCount returns the HalloweenCount field if non-nil, zero value otherwise.

### GetHalloweenCountOk

`func (o *Character) GetHalloweenCountOk() (*int32, bool)`

GetHalloweenCountOk returns a tuple with the HalloweenCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHalloweenCount

`func (o *Character) SetHalloweenCount(v int32)`

SetHalloweenCount sets HalloweenCount field to given value.


### GetLoginTimestamp

`func (o *Character) GetLoginTimestamp() int32`

GetLoginTimestamp returns the LoginTimestamp field if non-nil, zero value otherwise.

### GetLoginTimestampOk

`func (o *Character) GetLoginTimestampOk() (*int32, bool)`

GetLoginTimestampOk returns a tuple with the LoginTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoginTimestamp

`func (o *Character) SetLoginTimestamp(v int32)`

SetLoginTimestamp sets LoginTimestamp field to given value.


### GetRegisterTimestamp

`func (o *Character) GetRegisterTimestamp() time.Time`

GetRegisterTimestamp returns the RegisterTimestamp field if non-nil, zero value otherwise.

### GetRegisterTimestampOk

`func (o *Character) GetRegisterTimestampOk() (*time.Time, bool)`

GetRegisterTimestampOk returns a tuple with the RegisterTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisterTimestamp

`func (o *Character) SetRegisterTimestamp(v time.Time)`

SetRegisterTimestamp sets RegisterTimestamp field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


