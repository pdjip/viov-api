# GroupVehicle

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ID** | **int64** |  | 
**GroupID** | **int32** |  | 
**Hash** | **string** |  | 
**PosX** | **string** |  | 
**PosY** | **string** |  | 
**PosZ** | **string** |  | 
**RotX** | **string** |  | 
**RotY** | **string** |  | 
**RotZ** | **string** |  | 
**Color1** | **int32** |  | 
**Color2** | **int32** |  | 
**BuyDate** | **time.Time** |  | 
**Color1R** | **int32** |  | 
**Color1G** | **int32** |  | 
**Color1B** | **int32** |  | 
**Color2R** | **int32** |  | 
**Color2G** | **int32** |  | 
**Color2B** | **int32** |  | 
**Spoilers** | **int32** |  | 
**FrontBumper** | **int32** |  | 
**RearBumper** | **int32** |  | 
**SideSkirt** | **int32** |  | 
**Exhaust** | **int32** |  | 
**Frame** | **int32** |  | 
**Grille** | **int32** |  | 
**Hood** | **int32** |  | 
**Fender** | **int32** |  | 
**RightFender** | **int32** |  | 
**Roof** | **int32** |  | 
**Engine** | **int32** |  | 
**Brakes** | **int32** |  | 
**Transmission** | **int32** |  | 
**Horns** | **int32** |  | 
**Suspension** | **int32** |  | 
**Armor** | **int32** |  | 
**Turbo** | **int32** |  | 
**Xenon** | **int32** |  | 
**FrontWheels** | **int32** |  | 
**BackWheels** | **int32** |  | 
**Plateholders** | **int32** |  | 
**TrimDesign** | **int32** |  | 
**Ornaments** | **int32** |  | 
**DialDesign** | **int32** |  | 
**SteeringWheel** | **int32** |  | 
**ShiftLever** | **int32** |  | 
**Plaques** | **int32** |  | 
**Hydraulics** | **int32** |  | 
**Livery** | **int32** |  | 
**Plate** | **int32** |  | 
**WindowTint** | **int32** |  | 
**ModName** | **string** |  | 
**InteriorColor** | **int32** |  | 
**ChipTuning** | **int32** |  | 
**PaintArt** | **int32** |  | 
**WheelColor** | **int32** |  | 
**WheelType** | **int32** |  | 
**SpawnGarage** | **int32** |  | 
**LastDriver** | **string** |  | 
**PlateText** | **string** |  | 
**Fuel** | **string** |  | 
**Health** | **int32** |  | 
**DirtLevel** | **string** |  | 
**Permission** | Pointer to **string** |  | [optional] 

## Methods

### NewGroupVehicle

`func NewGroupVehicle(iD int64, groupID int32, hash string, posX string, posY string, posZ string, rotX string, rotY string, rotZ string, color1 int32, color2 int32, buyDate time.Time, color1R int32, color1G int32, color1B int32, color2R int32, color2G int32, color2B int32, spoilers int32, frontBumper int32, rearBumper int32, sideSkirt int32, exhaust int32, frame int32, grille int32, hood int32, fender int32, rightFender int32, roof int32, engine int32, brakes int32, transmission int32, horns int32, suspension int32, armor int32, turbo int32, xenon int32, frontWheels int32, backWheels int32, plateholders int32, trimDesign int32, ornaments int32, dialDesign int32, steeringWheel int32, shiftLever int32, plaques int32, hydraulics int32, livery int32, plate int32, windowTint int32, modName string, interiorColor int32, chipTuning int32, paintArt int32, wheelColor int32, wheelType int32, spawnGarage int32, lastDriver string, plateText string, fuel string, health int32, dirtLevel string, ) *GroupVehicle`

NewGroupVehicle instantiates a new GroupVehicle object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupVehicleWithDefaults

`func NewGroupVehicleWithDefaults() *GroupVehicle`

NewGroupVehicleWithDefaults instantiates a new GroupVehicle object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetID

`func (o *GroupVehicle) GetID() int64`

GetID returns the ID field if non-nil, zero value otherwise.

### GetIDOk

`func (o *GroupVehicle) GetIDOk() (*int64, bool)`

GetIDOk returns a tuple with the ID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetID

`func (o *GroupVehicle) SetID(v int64)`

SetID sets ID field to given value.


### GetGroupID

`func (o *GroupVehicle) GetGroupID() int32`

GetGroupID returns the GroupID field if non-nil, zero value otherwise.

### GetGroupIDOk

`func (o *GroupVehicle) GetGroupIDOk() (*int32, bool)`

GetGroupIDOk returns a tuple with the GroupID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupID

`func (o *GroupVehicle) SetGroupID(v int32)`

SetGroupID sets GroupID field to given value.


### GetHash

`func (o *GroupVehicle) GetHash() string`

GetHash returns the Hash field if non-nil, zero value otherwise.

### GetHashOk

`func (o *GroupVehicle) GetHashOk() (*string, bool)`

GetHashOk returns a tuple with the Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHash

`func (o *GroupVehicle) SetHash(v string)`

SetHash sets Hash field to given value.


### GetPosX

`func (o *GroupVehicle) GetPosX() string`

GetPosX returns the PosX field if non-nil, zero value otherwise.

### GetPosXOk

`func (o *GroupVehicle) GetPosXOk() (*string, bool)`

GetPosXOk returns a tuple with the PosX field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosX

`func (o *GroupVehicle) SetPosX(v string)`

SetPosX sets PosX field to given value.


### GetPosY

`func (o *GroupVehicle) GetPosY() string`

GetPosY returns the PosY field if non-nil, zero value otherwise.

### GetPosYOk

`func (o *GroupVehicle) GetPosYOk() (*string, bool)`

GetPosYOk returns a tuple with the PosY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosY

`func (o *GroupVehicle) SetPosY(v string)`

SetPosY sets PosY field to given value.


### GetPosZ

`func (o *GroupVehicle) GetPosZ() string`

GetPosZ returns the PosZ field if non-nil, zero value otherwise.

### GetPosZOk

`func (o *GroupVehicle) GetPosZOk() (*string, bool)`

GetPosZOk returns a tuple with the PosZ field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosZ

`func (o *GroupVehicle) SetPosZ(v string)`

SetPosZ sets PosZ field to given value.


### GetRotX

`func (o *GroupVehicle) GetRotX() string`

GetRotX returns the RotX field if non-nil, zero value otherwise.

### GetRotXOk

`func (o *GroupVehicle) GetRotXOk() (*string, bool)`

GetRotXOk returns a tuple with the RotX field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRotX

`func (o *GroupVehicle) SetRotX(v string)`

SetRotX sets RotX field to given value.


### GetRotY

`func (o *GroupVehicle) GetRotY() string`

GetRotY returns the RotY field if non-nil, zero value otherwise.

### GetRotYOk

`func (o *GroupVehicle) GetRotYOk() (*string, bool)`

GetRotYOk returns a tuple with the RotY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRotY

`func (o *GroupVehicle) SetRotY(v string)`

SetRotY sets RotY field to given value.


### GetRotZ

`func (o *GroupVehicle) GetRotZ() string`

GetRotZ returns the RotZ field if non-nil, zero value otherwise.

### GetRotZOk

`func (o *GroupVehicle) GetRotZOk() (*string, bool)`

GetRotZOk returns a tuple with the RotZ field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRotZ

`func (o *GroupVehicle) SetRotZ(v string)`

SetRotZ sets RotZ field to given value.


### GetColor1

`func (o *GroupVehicle) GetColor1() int32`

GetColor1 returns the Color1 field if non-nil, zero value otherwise.

### GetColor1Ok

`func (o *GroupVehicle) GetColor1Ok() (*int32, bool)`

GetColor1Ok returns a tuple with the Color1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor1

`func (o *GroupVehicle) SetColor1(v int32)`

SetColor1 sets Color1 field to given value.


### GetColor2

`func (o *GroupVehicle) GetColor2() int32`

GetColor2 returns the Color2 field if non-nil, zero value otherwise.

### GetColor2Ok

`func (o *GroupVehicle) GetColor2Ok() (*int32, bool)`

GetColor2Ok returns a tuple with the Color2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor2

`func (o *GroupVehicle) SetColor2(v int32)`

SetColor2 sets Color2 field to given value.


### GetBuyDate

`func (o *GroupVehicle) GetBuyDate() time.Time`

GetBuyDate returns the BuyDate field if non-nil, zero value otherwise.

### GetBuyDateOk

`func (o *GroupVehicle) GetBuyDateOk() (*time.Time, bool)`

GetBuyDateOk returns a tuple with the BuyDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuyDate

`func (o *GroupVehicle) SetBuyDate(v time.Time)`

SetBuyDate sets BuyDate field to given value.


### GetColor1R

`func (o *GroupVehicle) GetColor1R() int32`

GetColor1R returns the Color1R field if non-nil, zero value otherwise.

### GetColor1ROk

`func (o *GroupVehicle) GetColor1ROk() (*int32, bool)`

GetColor1ROk returns a tuple with the Color1R field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor1R

`func (o *GroupVehicle) SetColor1R(v int32)`

SetColor1R sets Color1R field to given value.


### GetColor1G

`func (o *GroupVehicle) GetColor1G() int32`

GetColor1G returns the Color1G field if non-nil, zero value otherwise.

### GetColor1GOk

`func (o *GroupVehicle) GetColor1GOk() (*int32, bool)`

GetColor1GOk returns a tuple with the Color1G field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor1G

`func (o *GroupVehicle) SetColor1G(v int32)`

SetColor1G sets Color1G field to given value.


### GetColor1B

`func (o *GroupVehicle) GetColor1B() int32`

GetColor1B returns the Color1B field if non-nil, zero value otherwise.

### GetColor1BOk

`func (o *GroupVehicle) GetColor1BOk() (*int32, bool)`

GetColor1BOk returns a tuple with the Color1B field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor1B

`func (o *GroupVehicle) SetColor1B(v int32)`

SetColor1B sets Color1B field to given value.


### GetColor2R

`func (o *GroupVehicle) GetColor2R() int32`

GetColor2R returns the Color2R field if non-nil, zero value otherwise.

### GetColor2ROk

`func (o *GroupVehicle) GetColor2ROk() (*int32, bool)`

GetColor2ROk returns a tuple with the Color2R field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor2R

`func (o *GroupVehicle) SetColor2R(v int32)`

SetColor2R sets Color2R field to given value.


### GetColor2G

`func (o *GroupVehicle) GetColor2G() int32`

GetColor2G returns the Color2G field if non-nil, zero value otherwise.

### GetColor2GOk

`func (o *GroupVehicle) GetColor2GOk() (*int32, bool)`

GetColor2GOk returns a tuple with the Color2G field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor2G

`func (o *GroupVehicle) SetColor2G(v int32)`

SetColor2G sets Color2G field to given value.


### GetColor2B

`func (o *GroupVehicle) GetColor2B() int32`

GetColor2B returns the Color2B field if non-nil, zero value otherwise.

### GetColor2BOk

`func (o *GroupVehicle) GetColor2BOk() (*int32, bool)`

GetColor2BOk returns a tuple with the Color2B field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor2B

`func (o *GroupVehicle) SetColor2B(v int32)`

SetColor2B sets Color2B field to given value.


### GetSpoilers

`func (o *GroupVehicle) GetSpoilers() int32`

GetSpoilers returns the Spoilers field if non-nil, zero value otherwise.

### GetSpoilersOk

`func (o *GroupVehicle) GetSpoilersOk() (*int32, bool)`

GetSpoilersOk returns a tuple with the Spoilers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpoilers

`func (o *GroupVehicle) SetSpoilers(v int32)`

SetSpoilers sets Spoilers field to given value.


### GetFrontBumper

`func (o *GroupVehicle) GetFrontBumper() int32`

GetFrontBumper returns the FrontBumper field if non-nil, zero value otherwise.

### GetFrontBumperOk

`func (o *GroupVehicle) GetFrontBumperOk() (*int32, bool)`

GetFrontBumperOk returns a tuple with the FrontBumper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrontBumper

`func (o *GroupVehicle) SetFrontBumper(v int32)`

SetFrontBumper sets FrontBumper field to given value.


### GetRearBumper

`func (o *GroupVehicle) GetRearBumper() int32`

GetRearBumper returns the RearBumper field if non-nil, zero value otherwise.

### GetRearBumperOk

`func (o *GroupVehicle) GetRearBumperOk() (*int32, bool)`

GetRearBumperOk returns a tuple with the RearBumper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRearBumper

`func (o *GroupVehicle) SetRearBumper(v int32)`

SetRearBumper sets RearBumper field to given value.


### GetSideSkirt

`func (o *GroupVehicle) GetSideSkirt() int32`

GetSideSkirt returns the SideSkirt field if non-nil, zero value otherwise.

### GetSideSkirtOk

`func (o *GroupVehicle) GetSideSkirtOk() (*int32, bool)`

GetSideSkirtOk returns a tuple with the SideSkirt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSideSkirt

`func (o *GroupVehicle) SetSideSkirt(v int32)`

SetSideSkirt sets SideSkirt field to given value.


### GetExhaust

`func (o *GroupVehicle) GetExhaust() int32`

GetExhaust returns the Exhaust field if non-nil, zero value otherwise.

### GetExhaustOk

`func (o *GroupVehicle) GetExhaustOk() (*int32, bool)`

GetExhaustOk returns a tuple with the Exhaust field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExhaust

`func (o *GroupVehicle) SetExhaust(v int32)`

SetExhaust sets Exhaust field to given value.


### GetFrame

`func (o *GroupVehicle) GetFrame() int32`

GetFrame returns the Frame field if non-nil, zero value otherwise.

### GetFrameOk

`func (o *GroupVehicle) GetFrameOk() (*int32, bool)`

GetFrameOk returns a tuple with the Frame field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrame

`func (o *GroupVehicle) SetFrame(v int32)`

SetFrame sets Frame field to given value.


### GetGrille

`func (o *GroupVehicle) GetGrille() int32`

GetGrille returns the Grille field if non-nil, zero value otherwise.

### GetGrilleOk

`func (o *GroupVehicle) GetGrilleOk() (*int32, bool)`

GetGrilleOk returns a tuple with the Grille field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrille

`func (o *GroupVehicle) SetGrille(v int32)`

SetGrille sets Grille field to given value.


### GetHood

`func (o *GroupVehicle) GetHood() int32`

GetHood returns the Hood field if non-nil, zero value otherwise.

### GetHoodOk

`func (o *GroupVehicle) GetHoodOk() (*int32, bool)`

GetHoodOk returns a tuple with the Hood field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHood

`func (o *GroupVehicle) SetHood(v int32)`

SetHood sets Hood field to given value.


### GetFender

`func (o *GroupVehicle) GetFender() int32`

GetFender returns the Fender field if non-nil, zero value otherwise.

### GetFenderOk

`func (o *GroupVehicle) GetFenderOk() (*int32, bool)`

GetFenderOk returns a tuple with the Fender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFender

`func (o *GroupVehicle) SetFender(v int32)`

SetFender sets Fender field to given value.


### GetRightFender

`func (o *GroupVehicle) GetRightFender() int32`

GetRightFender returns the RightFender field if non-nil, zero value otherwise.

### GetRightFenderOk

`func (o *GroupVehicle) GetRightFenderOk() (*int32, bool)`

GetRightFenderOk returns a tuple with the RightFender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRightFender

`func (o *GroupVehicle) SetRightFender(v int32)`

SetRightFender sets RightFender field to given value.


### GetRoof

`func (o *GroupVehicle) GetRoof() int32`

GetRoof returns the Roof field if non-nil, zero value otherwise.

### GetRoofOk

`func (o *GroupVehicle) GetRoofOk() (*int32, bool)`

GetRoofOk returns a tuple with the Roof field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoof

`func (o *GroupVehicle) SetRoof(v int32)`

SetRoof sets Roof field to given value.


### GetEngine

`func (o *GroupVehicle) GetEngine() int32`

GetEngine returns the Engine field if non-nil, zero value otherwise.

### GetEngineOk

`func (o *GroupVehicle) GetEngineOk() (*int32, bool)`

GetEngineOk returns a tuple with the Engine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngine

`func (o *GroupVehicle) SetEngine(v int32)`

SetEngine sets Engine field to given value.


### GetBrakes

`func (o *GroupVehicle) GetBrakes() int32`

GetBrakes returns the Brakes field if non-nil, zero value otherwise.

### GetBrakesOk

`func (o *GroupVehicle) GetBrakesOk() (*int32, bool)`

GetBrakesOk returns a tuple with the Brakes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrakes

`func (o *GroupVehicle) SetBrakes(v int32)`

SetBrakes sets Brakes field to given value.


### GetTransmission

`func (o *GroupVehicle) GetTransmission() int32`

GetTransmission returns the Transmission field if non-nil, zero value otherwise.

### GetTransmissionOk

`func (o *GroupVehicle) GetTransmissionOk() (*int32, bool)`

GetTransmissionOk returns a tuple with the Transmission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransmission

`func (o *GroupVehicle) SetTransmission(v int32)`

SetTransmission sets Transmission field to given value.


### GetHorns

`func (o *GroupVehicle) GetHorns() int32`

GetHorns returns the Horns field if non-nil, zero value otherwise.

### GetHornsOk

`func (o *GroupVehicle) GetHornsOk() (*int32, bool)`

GetHornsOk returns a tuple with the Horns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHorns

`func (o *GroupVehicle) SetHorns(v int32)`

SetHorns sets Horns field to given value.


### GetSuspension

`func (o *GroupVehicle) GetSuspension() int32`

GetSuspension returns the Suspension field if non-nil, zero value otherwise.

### GetSuspensionOk

`func (o *GroupVehicle) GetSuspensionOk() (*int32, bool)`

GetSuspensionOk returns a tuple with the Suspension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuspension

`func (o *GroupVehicle) SetSuspension(v int32)`

SetSuspension sets Suspension field to given value.


### GetArmor

`func (o *GroupVehicle) GetArmor() int32`

GetArmor returns the Armor field if non-nil, zero value otherwise.

### GetArmorOk

`func (o *GroupVehicle) GetArmorOk() (*int32, bool)`

GetArmorOk returns a tuple with the Armor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArmor

`func (o *GroupVehicle) SetArmor(v int32)`

SetArmor sets Armor field to given value.


### GetTurbo

`func (o *GroupVehicle) GetTurbo() int32`

GetTurbo returns the Turbo field if non-nil, zero value otherwise.

### GetTurboOk

`func (o *GroupVehicle) GetTurboOk() (*int32, bool)`

GetTurboOk returns a tuple with the Turbo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTurbo

`func (o *GroupVehicle) SetTurbo(v int32)`

SetTurbo sets Turbo field to given value.


### GetXenon

`func (o *GroupVehicle) GetXenon() int32`

GetXenon returns the Xenon field if non-nil, zero value otherwise.

### GetXenonOk

`func (o *GroupVehicle) GetXenonOk() (*int32, bool)`

GetXenonOk returns a tuple with the Xenon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetXenon

`func (o *GroupVehicle) SetXenon(v int32)`

SetXenon sets Xenon field to given value.


### GetFrontWheels

`func (o *GroupVehicle) GetFrontWheels() int32`

GetFrontWheels returns the FrontWheels field if non-nil, zero value otherwise.

### GetFrontWheelsOk

`func (o *GroupVehicle) GetFrontWheelsOk() (*int32, bool)`

GetFrontWheelsOk returns a tuple with the FrontWheels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrontWheels

`func (o *GroupVehicle) SetFrontWheels(v int32)`

SetFrontWheels sets FrontWheels field to given value.


### GetBackWheels

`func (o *GroupVehicle) GetBackWheels() int32`

GetBackWheels returns the BackWheels field if non-nil, zero value otherwise.

### GetBackWheelsOk

`func (o *GroupVehicle) GetBackWheelsOk() (*int32, bool)`

GetBackWheelsOk returns a tuple with the BackWheels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackWheels

`func (o *GroupVehicle) SetBackWheels(v int32)`

SetBackWheels sets BackWheels field to given value.


### GetPlateholders

`func (o *GroupVehicle) GetPlateholders() int32`

GetPlateholders returns the Plateholders field if non-nil, zero value otherwise.

### GetPlateholdersOk

`func (o *GroupVehicle) GetPlateholdersOk() (*int32, bool)`

GetPlateholdersOk returns a tuple with the Plateholders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlateholders

`func (o *GroupVehicle) SetPlateholders(v int32)`

SetPlateholders sets Plateholders field to given value.


### GetTrimDesign

`func (o *GroupVehicle) GetTrimDesign() int32`

GetTrimDesign returns the TrimDesign field if non-nil, zero value otherwise.

### GetTrimDesignOk

`func (o *GroupVehicle) GetTrimDesignOk() (*int32, bool)`

GetTrimDesignOk returns a tuple with the TrimDesign field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrimDesign

`func (o *GroupVehicle) SetTrimDesign(v int32)`

SetTrimDesign sets TrimDesign field to given value.


### GetOrnaments

`func (o *GroupVehicle) GetOrnaments() int32`

GetOrnaments returns the Ornaments field if non-nil, zero value otherwise.

### GetOrnamentsOk

`func (o *GroupVehicle) GetOrnamentsOk() (*int32, bool)`

GetOrnamentsOk returns a tuple with the Ornaments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrnaments

`func (o *GroupVehicle) SetOrnaments(v int32)`

SetOrnaments sets Ornaments field to given value.


### GetDialDesign

`func (o *GroupVehicle) GetDialDesign() int32`

GetDialDesign returns the DialDesign field if non-nil, zero value otherwise.

### GetDialDesignOk

`func (o *GroupVehicle) GetDialDesignOk() (*int32, bool)`

GetDialDesignOk returns a tuple with the DialDesign field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDialDesign

`func (o *GroupVehicle) SetDialDesign(v int32)`

SetDialDesign sets DialDesign field to given value.


### GetSteeringWheel

`func (o *GroupVehicle) GetSteeringWheel() int32`

GetSteeringWheel returns the SteeringWheel field if non-nil, zero value otherwise.

### GetSteeringWheelOk

`func (o *GroupVehicle) GetSteeringWheelOk() (*int32, bool)`

GetSteeringWheelOk returns a tuple with the SteeringWheel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSteeringWheel

`func (o *GroupVehicle) SetSteeringWheel(v int32)`

SetSteeringWheel sets SteeringWheel field to given value.


### GetShiftLever

`func (o *GroupVehicle) GetShiftLever() int32`

GetShiftLever returns the ShiftLever field if non-nil, zero value otherwise.

### GetShiftLeverOk

`func (o *GroupVehicle) GetShiftLeverOk() (*int32, bool)`

GetShiftLeverOk returns a tuple with the ShiftLever field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShiftLever

`func (o *GroupVehicle) SetShiftLever(v int32)`

SetShiftLever sets ShiftLever field to given value.


### GetPlaques

`func (o *GroupVehicle) GetPlaques() int32`

GetPlaques returns the Plaques field if non-nil, zero value otherwise.

### GetPlaquesOk

`func (o *GroupVehicle) GetPlaquesOk() (*int32, bool)`

GetPlaquesOk returns a tuple with the Plaques field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlaques

`func (o *GroupVehicle) SetPlaques(v int32)`

SetPlaques sets Plaques field to given value.


### GetHydraulics

`func (o *GroupVehicle) GetHydraulics() int32`

GetHydraulics returns the Hydraulics field if non-nil, zero value otherwise.

### GetHydraulicsOk

`func (o *GroupVehicle) GetHydraulicsOk() (*int32, bool)`

GetHydraulicsOk returns a tuple with the Hydraulics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHydraulics

`func (o *GroupVehicle) SetHydraulics(v int32)`

SetHydraulics sets Hydraulics field to given value.


### GetLivery

`func (o *GroupVehicle) GetLivery() int32`

GetLivery returns the Livery field if non-nil, zero value otherwise.

### GetLiveryOk

`func (o *GroupVehicle) GetLiveryOk() (*int32, bool)`

GetLiveryOk returns a tuple with the Livery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLivery

`func (o *GroupVehicle) SetLivery(v int32)`

SetLivery sets Livery field to given value.


### GetPlate

`func (o *GroupVehicle) GetPlate() int32`

GetPlate returns the Plate field if non-nil, zero value otherwise.

### GetPlateOk

`func (o *GroupVehicle) GetPlateOk() (*int32, bool)`

GetPlateOk returns a tuple with the Plate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlate

`func (o *GroupVehicle) SetPlate(v int32)`

SetPlate sets Plate field to given value.


### GetWindowTint

`func (o *GroupVehicle) GetWindowTint() int32`

GetWindowTint returns the WindowTint field if non-nil, zero value otherwise.

### GetWindowTintOk

`func (o *GroupVehicle) GetWindowTintOk() (*int32, bool)`

GetWindowTintOk returns a tuple with the WindowTint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowTint

`func (o *GroupVehicle) SetWindowTint(v int32)`

SetWindowTint sets WindowTint field to given value.


### GetModName

`func (o *GroupVehicle) GetModName() string`

GetModName returns the ModName field if non-nil, zero value otherwise.

### GetModNameOk

`func (o *GroupVehicle) GetModNameOk() (*string, bool)`

GetModNameOk returns a tuple with the ModName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModName

`func (o *GroupVehicle) SetModName(v string)`

SetModName sets ModName field to given value.


### GetInteriorColor

`func (o *GroupVehicle) GetInteriorColor() int32`

GetInteriorColor returns the InteriorColor field if non-nil, zero value otherwise.

### GetInteriorColorOk

`func (o *GroupVehicle) GetInteriorColorOk() (*int32, bool)`

GetInteriorColorOk returns a tuple with the InteriorColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInteriorColor

`func (o *GroupVehicle) SetInteriorColor(v int32)`

SetInteriorColor sets InteriorColor field to given value.


### GetChipTuning

`func (o *GroupVehicle) GetChipTuning() int32`

GetChipTuning returns the ChipTuning field if non-nil, zero value otherwise.

### GetChipTuningOk

`func (o *GroupVehicle) GetChipTuningOk() (*int32, bool)`

GetChipTuningOk returns a tuple with the ChipTuning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChipTuning

`func (o *GroupVehicle) SetChipTuning(v int32)`

SetChipTuning sets ChipTuning field to given value.


### GetPaintArt

`func (o *GroupVehicle) GetPaintArt() int32`

GetPaintArt returns the PaintArt field if non-nil, zero value otherwise.

### GetPaintArtOk

`func (o *GroupVehicle) GetPaintArtOk() (*int32, bool)`

GetPaintArtOk returns a tuple with the PaintArt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaintArt

`func (o *GroupVehicle) SetPaintArt(v int32)`

SetPaintArt sets PaintArt field to given value.


### GetWheelColor

`func (o *GroupVehicle) GetWheelColor() int32`

GetWheelColor returns the WheelColor field if non-nil, zero value otherwise.

### GetWheelColorOk

`func (o *GroupVehicle) GetWheelColorOk() (*int32, bool)`

GetWheelColorOk returns a tuple with the WheelColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWheelColor

`func (o *GroupVehicle) SetWheelColor(v int32)`

SetWheelColor sets WheelColor field to given value.


### GetWheelType

`func (o *GroupVehicle) GetWheelType() int32`

GetWheelType returns the WheelType field if non-nil, zero value otherwise.

### GetWheelTypeOk

`func (o *GroupVehicle) GetWheelTypeOk() (*int32, bool)`

GetWheelTypeOk returns a tuple with the WheelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWheelType

`func (o *GroupVehicle) SetWheelType(v int32)`

SetWheelType sets WheelType field to given value.


### GetSpawnGarage

`func (o *GroupVehicle) GetSpawnGarage() int32`

GetSpawnGarage returns the SpawnGarage field if non-nil, zero value otherwise.

### GetSpawnGarageOk

`func (o *GroupVehicle) GetSpawnGarageOk() (*int32, bool)`

GetSpawnGarageOk returns a tuple with the SpawnGarage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpawnGarage

`func (o *GroupVehicle) SetSpawnGarage(v int32)`

SetSpawnGarage sets SpawnGarage field to given value.


### GetLastDriver

`func (o *GroupVehicle) GetLastDriver() string`

GetLastDriver returns the LastDriver field if non-nil, zero value otherwise.

### GetLastDriverOk

`func (o *GroupVehicle) GetLastDriverOk() (*string, bool)`

GetLastDriverOk returns a tuple with the LastDriver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastDriver

`func (o *GroupVehicle) SetLastDriver(v string)`

SetLastDriver sets LastDriver field to given value.


### GetPlateText

`func (o *GroupVehicle) GetPlateText() string`

GetPlateText returns the PlateText field if non-nil, zero value otherwise.

### GetPlateTextOk

`func (o *GroupVehicle) GetPlateTextOk() (*string, bool)`

GetPlateTextOk returns a tuple with the PlateText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlateText

`func (o *GroupVehicle) SetPlateText(v string)`

SetPlateText sets PlateText field to given value.


### GetFuel

`func (o *GroupVehicle) GetFuel() string`

GetFuel returns the Fuel field if non-nil, zero value otherwise.

### GetFuelOk

`func (o *GroupVehicle) GetFuelOk() (*string, bool)`

GetFuelOk returns a tuple with the Fuel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFuel

`func (o *GroupVehicle) SetFuel(v string)`

SetFuel sets Fuel field to given value.


### GetHealth

`func (o *GroupVehicle) GetHealth() int32`

GetHealth returns the Health field if non-nil, zero value otherwise.

### GetHealthOk

`func (o *GroupVehicle) GetHealthOk() (*int32, bool)`

GetHealthOk returns a tuple with the Health field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealth

`func (o *GroupVehicle) SetHealth(v int32)`

SetHealth sets Health field to given value.


### GetDirtLevel

`func (o *GroupVehicle) GetDirtLevel() string`

GetDirtLevel returns the DirtLevel field if non-nil, zero value otherwise.

### GetDirtLevelOk

`func (o *GroupVehicle) GetDirtLevelOk() (*string, bool)`

GetDirtLevelOk returns a tuple with the DirtLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirtLevel

`func (o *GroupVehicle) SetDirtLevel(v string)`

SetDirtLevel sets DirtLevel field to given value.


### GetPermission

`func (o *GroupVehicle) GetPermission() string`

GetPermission returns the Permission field if non-nil, zero value otherwise.

### GetPermissionOk

`func (o *GroupVehicle) GetPermissionOk() (*string, bool)`

GetPermissionOk returns a tuple with the Permission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermission

`func (o *GroupVehicle) SetPermission(v string)`

SetPermission sets Permission field to given value.

### HasPermission

`func (o *GroupVehicle) HasPermission() bool`

HasPermission returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


