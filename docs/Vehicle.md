# Vehicle

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ID** | **int32** |  | 
**CharacterID** | **int32** |  | 
**Hash** | **string** |  | 
**PosX** | **string** |  | 
**PosY** | **string** |  | 
**PosZ** | **string** |  | 
**RotX** | **string** |  | 
**RotY** | **string** |  | 
**RotZ** | **string** |  | 
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
**NeonStateLeft** | **int32** |  | 
**NeonStateRight** | **int32** |  | 
**NeonStateFront** | **int32** |  | 
**NeonStateBack** | **int32** |  | 
**NeonStateColorR** | **int32** |  | 
**NeonStateColorG** | **int32** |  | 
**NeonStateColorB** | **int32** |  | 
**Fuel** | **string** |  | 
**Repair** | **int32** |  | 
**Distance** | **string** |  | 
**Garage** | **int32** |  | 
**Health** | **int32** |  | 
**DirtLevel** | **string** |  | 
**InteriorColor** | **int32** |  | 
**ChipTuning** | **int32** |  | 
**PaintArt** | **int32** |  | 
**WheelColor** | **int32** |  | 
**WheelType** | **int32** |  | 
**PlateText** | **string** |  | 
**Insurance** | **string** |  | 
**InsuranceExpiry** | **int32** |  | 

## Methods

### NewVehicle

`func NewVehicle(iD int32, characterID int32, hash string, posX string, posY string, posZ string, rotX string, rotY string, rotZ string, buyDate time.Time, color1R int32, color1G int32, color1B int32, color2R int32, color2G int32, color2B int32, spoilers int32, frontBumper int32, rearBumper int32, sideSkirt int32, exhaust int32, frame int32, grille int32, hood int32, fender int32, rightFender int32, roof int32, engine int32, brakes int32, transmission int32, horns int32, suspension int32, armor int32, turbo int32, xenon int32, frontWheels int32, backWheels int32, plateholders int32, trimDesign int32, ornaments int32, dialDesign int32, steeringWheel int32, shiftLever int32, plaques int32, hydraulics int32, livery int32, plate int32, windowTint int32, neonStateLeft int32, neonStateRight int32, neonStateFront int32, neonStateBack int32, neonStateColorR int32, neonStateColorG int32, neonStateColorB int32, fuel string, repair int32, distance string, garage int32, health int32, dirtLevel string, interiorColor int32, chipTuning int32, paintArt int32, wheelColor int32, wheelType int32, plateText string, insurance string, insuranceExpiry int32, ) *Vehicle`

NewVehicle instantiates a new Vehicle object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVehicleWithDefaults

`func NewVehicleWithDefaults() *Vehicle`

NewVehicleWithDefaults instantiates a new Vehicle object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetID

`func (o *Vehicle) GetID() int32`

GetID returns the ID field if non-nil, zero value otherwise.

### GetIDOk

`func (o *Vehicle) GetIDOk() (*int32, bool)`

GetIDOk returns a tuple with the ID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetID

`func (o *Vehicle) SetID(v int32)`

SetID sets ID field to given value.


### GetCharacterID

`func (o *Vehicle) GetCharacterID() int32`

GetCharacterID returns the CharacterID field if non-nil, zero value otherwise.

### GetCharacterIDOk

`func (o *Vehicle) GetCharacterIDOk() (*int32, bool)`

GetCharacterIDOk returns a tuple with the CharacterID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacterID

`func (o *Vehicle) SetCharacterID(v int32)`

SetCharacterID sets CharacterID field to given value.


### GetHash

`func (o *Vehicle) GetHash() string`

GetHash returns the Hash field if non-nil, zero value otherwise.

### GetHashOk

`func (o *Vehicle) GetHashOk() (*string, bool)`

GetHashOk returns a tuple with the Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHash

`func (o *Vehicle) SetHash(v string)`

SetHash sets Hash field to given value.


### GetPosX

`func (o *Vehicle) GetPosX() string`

GetPosX returns the PosX field if non-nil, zero value otherwise.

### GetPosXOk

`func (o *Vehicle) GetPosXOk() (*string, bool)`

GetPosXOk returns a tuple with the PosX field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosX

`func (o *Vehicle) SetPosX(v string)`

SetPosX sets PosX field to given value.


### GetPosY

`func (o *Vehicle) GetPosY() string`

GetPosY returns the PosY field if non-nil, zero value otherwise.

### GetPosYOk

`func (o *Vehicle) GetPosYOk() (*string, bool)`

GetPosYOk returns a tuple with the PosY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosY

`func (o *Vehicle) SetPosY(v string)`

SetPosY sets PosY field to given value.


### GetPosZ

`func (o *Vehicle) GetPosZ() string`

GetPosZ returns the PosZ field if non-nil, zero value otherwise.

### GetPosZOk

`func (o *Vehicle) GetPosZOk() (*string, bool)`

GetPosZOk returns a tuple with the PosZ field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosZ

`func (o *Vehicle) SetPosZ(v string)`

SetPosZ sets PosZ field to given value.


### GetRotX

`func (o *Vehicle) GetRotX() string`

GetRotX returns the RotX field if non-nil, zero value otherwise.

### GetRotXOk

`func (o *Vehicle) GetRotXOk() (*string, bool)`

GetRotXOk returns a tuple with the RotX field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRotX

`func (o *Vehicle) SetRotX(v string)`

SetRotX sets RotX field to given value.


### GetRotY

`func (o *Vehicle) GetRotY() string`

GetRotY returns the RotY field if non-nil, zero value otherwise.

### GetRotYOk

`func (o *Vehicle) GetRotYOk() (*string, bool)`

GetRotYOk returns a tuple with the RotY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRotY

`func (o *Vehicle) SetRotY(v string)`

SetRotY sets RotY field to given value.


### GetRotZ

`func (o *Vehicle) GetRotZ() string`

GetRotZ returns the RotZ field if non-nil, zero value otherwise.

### GetRotZOk

`func (o *Vehicle) GetRotZOk() (*string, bool)`

GetRotZOk returns a tuple with the RotZ field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRotZ

`func (o *Vehicle) SetRotZ(v string)`

SetRotZ sets RotZ field to given value.


### GetBuyDate

`func (o *Vehicle) GetBuyDate() time.Time`

GetBuyDate returns the BuyDate field if non-nil, zero value otherwise.

### GetBuyDateOk

`func (o *Vehicle) GetBuyDateOk() (*time.Time, bool)`

GetBuyDateOk returns a tuple with the BuyDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuyDate

`func (o *Vehicle) SetBuyDate(v time.Time)`

SetBuyDate sets BuyDate field to given value.


### GetColor1R

`func (o *Vehicle) GetColor1R() int32`

GetColor1R returns the Color1R field if non-nil, zero value otherwise.

### GetColor1ROk

`func (o *Vehicle) GetColor1ROk() (*int32, bool)`

GetColor1ROk returns a tuple with the Color1R field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor1R

`func (o *Vehicle) SetColor1R(v int32)`

SetColor1R sets Color1R field to given value.


### GetColor1G

`func (o *Vehicle) GetColor1G() int32`

GetColor1G returns the Color1G field if non-nil, zero value otherwise.

### GetColor1GOk

`func (o *Vehicle) GetColor1GOk() (*int32, bool)`

GetColor1GOk returns a tuple with the Color1G field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor1G

`func (o *Vehicle) SetColor1G(v int32)`

SetColor1G sets Color1G field to given value.


### GetColor1B

`func (o *Vehicle) GetColor1B() int32`

GetColor1B returns the Color1B field if non-nil, zero value otherwise.

### GetColor1BOk

`func (o *Vehicle) GetColor1BOk() (*int32, bool)`

GetColor1BOk returns a tuple with the Color1B field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor1B

`func (o *Vehicle) SetColor1B(v int32)`

SetColor1B sets Color1B field to given value.


### GetColor2R

`func (o *Vehicle) GetColor2R() int32`

GetColor2R returns the Color2R field if non-nil, zero value otherwise.

### GetColor2ROk

`func (o *Vehicle) GetColor2ROk() (*int32, bool)`

GetColor2ROk returns a tuple with the Color2R field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor2R

`func (o *Vehicle) SetColor2R(v int32)`

SetColor2R sets Color2R field to given value.


### GetColor2G

`func (o *Vehicle) GetColor2G() int32`

GetColor2G returns the Color2G field if non-nil, zero value otherwise.

### GetColor2GOk

`func (o *Vehicle) GetColor2GOk() (*int32, bool)`

GetColor2GOk returns a tuple with the Color2G field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor2G

`func (o *Vehicle) SetColor2G(v int32)`

SetColor2G sets Color2G field to given value.


### GetColor2B

`func (o *Vehicle) GetColor2B() int32`

GetColor2B returns the Color2B field if non-nil, zero value otherwise.

### GetColor2BOk

`func (o *Vehicle) GetColor2BOk() (*int32, bool)`

GetColor2BOk returns a tuple with the Color2B field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor2B

`func (o *Vehicle) SetColor2B(v int32)`

SetColor2B sets Color2B field to given value.


### GetSpoilers

`func (o *Vehicle) GetSpoilers() int32`

GetSpoilers returns the Spoilers field if non-nil, zero value otherwise.

### GetSpoilersOk

`func (o *Vehicle) GetSpoilersOk() (*int32, bool)`

GetSpoilersOk returns a tuple with the Spoilers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpoilers

`func (o *Vehicle) SetSpoilers(v int32)`

SetSpoilers sets Spoilers field to given value.


### GetFrontBumper

`func (o *Vehicle) GetFrontBumper() int32`

GetFrontBumper returns the FrontBumper field if non-nil, zero value otherwise.

### GetFrontBumperOk

`func (o *Vehicle) GetFrontBumperOk() (*int32, bool)`

GetFrontBumperOk returns a tuple with the FrontBumper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrontBumper

`func (o *Vehicle) SetFrontBumper(v int32)`

SetFrontBumper sets FrontBumper field to given value.


### GetRearBumper

`func (o *Vehicle) GetRearBumper() int32`

GetRearBumper returns the RearBumper field if non-nil, zero value otherwise.

### GetRearBumperOk

`func (o *Vehicle) GetRearBumperOk() (*int32, bool)`

GetRearBumperOk returns a tuple with the RearBumper field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRearBumper

`func (o *Vehicle) SetRearBumper(v int32)`

SetRearBumper sets RearBumper field to given value.


### GetSideSkirt

`func (o *Vehicle) GetSideSkirt() int32`

GetSideSkirt returns the SideSkirt field if non-nil, zero value otherwise.

### GetSideSkirtOk

`func (o *Vehicle) GetSideSkirtOk() (*int32, bool)`

GetSideSkirtOk returns a tuple with the SideSkirt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSideSkirt

`func (o *Vehicle) SetSideSkirt(v int32)`

SetSideSkirt sets SideSkirt field to given value.


### GetExhaust

`func (o *Vehicle) GetExhaust() int32`

GetExhaust returns the Exhaust field if non-nil, zero value otherwise.

### GetExhaustOk

`func (o *Vehicle) GetExhaustOk() (*int32, bool)`

GetExhaustOk returns a tuple with the Exhaust field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExhaust

`func (o *Vehicle) SetExhaust(v int32)`

SetExhaust sets Exhaust field to given value.


### GetFrame

`func (o *Vehicle) GetFrame() int32`

GetFrame returns the Frame field if non-nil, zero value otherwise.

### GetFrameOk

`func (o *Vehicle) GetFrameOk() (*int32, bool)`

GetFrameOk returns a tuple with the Frame field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrame

`func (o *Vehicle) SetFrame(v int32)`

SetFrame sets Frame field to given value.


### GetGrille

`func (o *Vehicle) GetGrille() int32`

GetGrille returns the Grille field if non-nil, zero value otherwise.

### GetGrilleOk

`func (o *Vehicle) GetGrilleOk() (*int32, bool)`

GetGrilleOk returns a tuple with the Grille field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrille

`func (o *Vehicle) SetGrille(v int32)`

SetGrille sets Grille field to given value.


### GetHood

`func (o *Vehicle) GetHood() int32`

GetHood returns the Hood field if non-nil, zero value otherwise.

### GetHoodOk

`func (o *Vehicle) GetHoodOk() (*int32, bool)`

GetHoodOk returns a tuple with the Hood field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHood

`func (o *Vehicle) SetHood(v int32)`

SetHood sets Hood field to given value.


### GetFender

`func (o *Vehicle) GetFender() int32`

GetFender returns the Fender field if non-nil, zero value otherwise.

### GetFenderOk

`func (o *Vehicle) GetFenderOk() (*int32, bool)`

GetFenderOk returns a tuple with the Fender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFender

`func (o *Vehicle) SetFender(v int32)`

SetFender sets Fender field to given value.


### GetRightFender

`func (o *Vehicle) GetRightFender() int32`

GetRightFender returns the RightFender field if non-nil, zero value otherwise.

### GetRightFenderOk

`func (o *Vehicle) GetRightFenderOk() (*int32, bool)`

GetRightFenderOk returns a tuple with the RightFender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRightFender

`func (o *Vehicle) SetRightFender(v int32)`

SetRightFender sets RightFender field to given value.


### GetRoof

`func (o *Vehicle) GetRoof() int32`

GetRoof returns the Roof field if non-nil, zero value otherwise.

### GetRoofOk

`func (o *Vehicle) GetRoofOk() (*int32, bool)`

GetRoofOk returns a tuple with the Roof field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoof

`func (o *Vehicle) SetRoof(v int32)`

SetRoof sets Roof field to given value.


### GetEngine

`func (o *Vehicle) GetEngine() int32`

GetEngine returns the Engine field if non-nil, zero value otherwise.

### GetEngineOk

`func (o *Vehicle) GetEngineOk() (*int32, bool)`

GetEngineOk returns a tuple with the Engine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngine

`func (o *Vehicle) SetEngine(v int32)`

SetEngine sets Engine field to given value.


### GetBrakes

`func (o *Vehicle) GetBrakes() int32`

GetBrakes returns the Brakes field if non-nil, zero value otherwise.

### GetBrakesOk

`func (o *Vehicle) GetBrakesOk() (*int32, bool)`

GetBrakesOk returns a tuple with the Brakes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrakes

`func (o *Vehicle) SetBrakes(v int32)`

SetBrakes sets Brakes field to given value.


### GetTransmission

`func (o *Vehicle) GetTransmission() int32`

GetTransmission returns the Transmission field if non-nil, zero value otherwise.

### GetTransmissionOk

`func (o *Vehicle) GetTransmissionOk() (*int32, bool)`

GetTransmissionOk returns a tuple with the Transmission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransmission

`func (o *Vehicle) SetTransmission(v int32)`

SetTransmission sets Transmission field to given value.


### GetHorns

`func (o *Vehicle) GetHorns() int32`

GetHorns returns the Horns field if non-nil, zero value otherwise.

### GetHornsOk

`func (o *Vehicle) GetHornsOk() (*int32, bool)`

GetHornsOk returns a tuple with the Horns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHorns

`func (o *Vehicle) SetHorns(v int32)`

SetHorns sets Horns field to given value.


### GetSuspension

`func (o *Vehicle) GetSuspension() int32`

GetSuspension returns the Suspension field if non-nil, zero value otherwise.

### GetSuspensionOk

`func (o *Vehicle) GetSuspensionOk() (*int32, bool)`

GetSuspensionOk returns a tuple with the Suspension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuspension

`func (o *Vehicle) SetSuspension(v int32)`

SetSuspension sets Suspension field to given value.


### GetArmor

`func (o *Vehicle) GetArmor() int32`

GetArmor returns the Armor field if non-nil, zero value otherwise.

### GetArmorOk

`func (o *Vehicle) GetArmorOk() (*int32, bool)`

GetArmorOk returns a tuple with the Armor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArmor

`func (o *Vehicle) SetArmor(v int32)`

SetArmor sets Armor field to given value.


### GetTurbo

`func (o *Vehicle) GetTurbo() int32`

GetTurbo returns the Turbo field if non-nil, zero value otherwise.

### GetTurboOk

`func (o *Vehicle) GetTurboOk() (*int32, bool)`

GetTurboOk returns a tuple with the Turbo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTurbo

`func (o *Vehicle) SetTurbo(v int32)`

SetTurbo sets Turbo field to given value.


### GetXenon

`func (o *Vehicle) GetXenon() int32`

GetXenon returns the Xenon field if non-nil, zero value otherwise.

### GetXenonOk

`func (o *Vehicle) GetXenonOk() (*int32, bool)`

GetXenonOk returns a tuple with the Xenon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetXenon

`func (o *Vehicle) SetXenon(v int32)`

SetXenon sets Xenon field to given value.


### GetFrontWheels

`func (o *Vehicle) GetFrontWheels() int32`

GetFrontWheels returns the FrontWheels field if non-nil, zero value otherwise.

### GetFrontWheelsOk

`func (o *Vehicle) GetFrontWheelsOk() (*int32, bool)`

GetFrontWheelsOk returns a tuple with the FrontWheels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrontWheels

`func (o *Vehicle) SetFrontWheels(v int32)`

SetFrontWheels sets FrontWheels field to given value.


### GetBackWheels

`func (o *Vehicle) GetBackWheels() int32`

GetBackWheels returns the BackWheels field if non-nil, zero value otherwise.

### GetBackWheelsOk

`func (o *Vehicle) GetBackWheelsOk() (*int32, bool)`

GetBackWheelsOk returns a tuple with the BackWheels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackWheels

`func (o *Vehicle) SetBackWheels(v int32)`

SetBackWheels sets BackWheels field to given value.


### GetPlateholders

`func (o *Vehicle) GetPlateholders() int32`

GetPlateholders returns the Plateholders field if non-nil, zero value otherwise.

### GetPlateholdersOk

`func (o *Vehicle) GetPlateholdersOk() (*int32, bool)`

GetPlateholdersOk returns a tuple with the Plateholders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlateholders

`func (o *Vehicle) SetPlateholders(v int32)`

SetPlateholders sets Plateholders field to given value.


### GetTrimDesign

`func (o *Vehicle) GetTrimDesign() int32`

GetTrimDesign returns the TrimDesign field if non-nil, zero value otherwise.

### GetTrimDesignOk

`func (o *Vehicle) GetTrimDesignOk() (*int32, bool)`

GetTrimDesignOk returns a tuple with the TrimDesign field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrimDesign

`func (o *Vehicle) SetTrimDesign(v int32)`

SetTrimDesign sets TrimDesign field to given value.


### GetOrnaments

`func (o *Vehicle) GetOrnaments() int32`

GetOrnaments returns the Ornaments field if non-nil, zero value otherwise.

### GetOrnamentsOk

`func (o *Vehicle) GetOrnamentsOk() (*int32, bool)`

GetOrnamentsOk returns a tuple with the Ornaments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrnaments

`func (o *Vehicle) SetOrnaments(v int32)`

SetOrnaments sets Ornaments field to given value.


### GetDialDesign

`func (o *Vehicle) GetDialDesign() int32`

GetDialDesign returns the DialDesign field if non-nil, zero value otherwise.

### GetDialDesignOk

`func (o *Vehicle) GetDialDesignOk() (*int32, bool)`

GetDialDesignOk returns a tuple with the DialDesign field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDialDesign

`func (o *Vehicle) SetDialDesign(v int32)`

SetDialDesign sets DialDesign field to given value.


### GetSteeringWheel

`func (o *Vehicle) GetSteeringWheel() int32`

GetSteeringWheel returns the SteeringWheel field if non-nil, zero value otherwise.

### GetSteeringWheelOk

`func (o *Vehicle) GetSteeringWheelOk() (*int32, bool)`

GetSteeringWheelOk returns a tuple with the SteeringWheel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSteeringWheel

`func (o *Vehicle) SetSteeringWheel(v int32)`

SetSteeringWheel sets SteeringWheel field to given value.


### GetShiftLever

`func (o *Vehicle) GetShiftLever() int32`

GetShiftLever returns the ShiftLever field if non-nil, zero value otherwise.

### GetShiftLeverOk

`func (o *Vehicle) GetShiftLeverOk() (*int32, bool)`

GetShiftLeverOk returns a tuple with the ShiftLever field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShiftLever

`func (o *Vehicle) SetShiftLever(v int32)`

SetShiftLever sets ShiftLever field to given value.


### GetPlaques

`func (o *Vehicle) GetPlaques() int32`

GetPlaques returns the Plaques field if non-nil, zero value otherwise.

### GetPlaquesOk

`func (o *Vehicle) GetPlaquesOk() (*int32, bool)`

GetPlaquesOk returns a tuple with the Plaques field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlaques

`func (o *Vehicle) SetPlaques(v int32)`

SetPlaques sets Plaques field to given value.


### GetHydraulics

`func (o *Vehicle) GetHydraulics() int32`

GetHydraulics returns the Hydraulics field if non-nil, zero value otherwise.

### GetHydraulicsOk

`func (o *Vehicle) GetHydraulicsOk() (*int32, bool)`

GetHydraulicsOk returns a tuple with the Hydraulics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHydraulics

`func (o *Vehicle) SetHydraulics(v int32)`

SetHydraulics sets Hydraulics field to given value.


### GetLivery

`func (o *Vehicle) GetLivery() int32`

GetLivery returns the Livery field if non-nil, zero value otherwise.

### GetLiveryOk

`func (o *Vehicle) GetLiveryOk() (*int32, bool)`

GetLiveryOk returns a tuple with the Livery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLivery

`func (o *Vehicle) SetLivery(v int32)`

SetLivery sets Livery field to given value.


### GetPlate

`func (o *Vehicle) GetPlate() int32`

GetPlate returns the Plate field if non-nil, zero value otherwise.

### GetPlateOk

`func (o *Vehicle) GetPlateOk() (*int32, bool)`

GetPlateOk returns a tuple with the Plate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlate

`func (o *Vehicle) SetPlate(v int32)`

SetPlate sets Plate field to given value.


### GetWindowTint

`func (o *Vehicle) GetWindowTint() int32`

GetWindowTint returns the WindowTint field if non-nil, zero value otherwise.

### GetWindowTintOk

`func (o *Vehicle) GetWindowTintOk() (*int32, bool)`

GetWindowTintOk returns a tuple with the WindowTint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowTint

`func (o *Vehicle) SetWindowTint(v int32)`

SetWindowTint sets WindowTint field to given value.


### GetNeonStateLeft

`func (o *Vehicle) GetNeonStateLeft() int32`

GetNeonStateLeft returns the NeonStateLeft field if non-nil, zero value otherwise.

### GetNeonStateLeftOk

`func (o *Vehicle) GetNeonStateLeftOk() (*int32, bool)`

GetNeonStateLeftOk returns a tuple with the NeonStateLeft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeonStateLeft

`func (o *Vehicle) SetNeonStateLeft(v int32)`

SetNeonStateLeft sets NeonStateLeft field to given value.


### GetNeonStateRight

`func (o *Vehicle) GetNeonStateRight() int32`

GetNeonStateRight returns the NeonStateRight field if non-nil, zero value otherwise.

### GetNeonStateRightOk

`func (o *Vehicle) GetNeonStateRightOk() (*int32, bool)`

GetNeonStateRightOk returns a tuple with the NeonStateRight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeonStateRight

`func (o *Vehicle) SetNeonStateRight(v int32)`

SetNeonStateRight sets NeonStateRight field to given value.


### GetNeonStateFront

`func (o *Vehicle) GetNeonStateFront() int32`

GetNeonStateFront returns the NeonStateFront field if non-nil, zero value otherwise.

### GetNeonStateFrontOk

`func (o *Vehicle) GetNeonStateFrontOk() (*int32, bool)`

GetNeonStateFrontOk returns a tuple with the NeonStateFront field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeonStateFront

`func (o *Vehicle) SetNeonStateFront(v int32)`

SetNeonStateFront sets NeonStateFront field to given value.


### GetNeonStateBack

`func (o *Vehicle) GetNeonStateBack() int32`

GetNeonStateBack returns the NeonStateBack field if non-nil, zero value otherwise.

### GetNeonStateBackOk

`func (o *Vehicle) GetNeonStateBackOk() (*int32, bool)`

GetNeonStateBackOk returns a tuple with the NeonStateBack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeonStateBack

`func (o *Vehicle) SetNeonStateBack(v int32)`

SetNeonStateBack sets NeonStateBack field to given value.


### GetNeonStateColorR

`func (o *Vehicle) GetNeonStateColorR() int32`

GetNeonStateColorR returns the NeonStateColorR field if non-nil, zero value otherwise.

### GetNeonStateColorROk

`func (o *Vehicle) GetNeonStateColorROk() (*int32, bool)`

GetNeonStateColorROk returns a tuple with the NeonStateColorR field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeonStateColorR

`func (o *Vehicle) SetNeonStateColorR(v int32)`

SetNeonStateColorR sets NeonStateColorR field to given value.


### GetNeonStateColorG

`func (o *Vehicle) GetNeonStateColorG() int32`

GetNeonStateColorG returns the NeonStateColorG field if non-nil, zero value otherwise.

### GetNeonStateColorGOk

`func (o *Vehicle) GetNeonStateColorGOk() (*int32, bool)`

GetNeonStateColorGOk returns a tuple with the NeonStateColorG field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeonStateColorG

`func (o *Vehicle) SetNeonStateColorG(v int32)`

SetNeonStateColorG sets NeonStateColorG field to given value.


### GetNeonStateColorB

`func (o *Vehicle) GetNeonStateColorB() int32`

GetNeonStateColorB returns the NeonStateColorB field if non-nil, zero value otherwise.

### GetNeonStateColorBOk

`func (o *Vehicle) GetNeonStateColorBOk() (*int32, bool)`

GetNeonStateColorBOk returns a tuple with the NeonStateColorB field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeonStateColorB

`func (o *Vehicle) SetNeonStateColorB(v int32)`

SetNeonStateColorB sets NeonStateColorB field to given value.


### GetFuel

`func (o *Vehicle) GetFuel() string`

GetFuel returns the Fuel field if non-nil, zero value otherwise.

### GetFuelOk

`func (o *Vehicle) GetFuelOk() (*string, bool)`

GetFuelOk returns a tuple with the Fuel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFuel

`func (o *Vehicle) SetFuel(v string)`

SetFuel sets Fuel field to given value.


### GetRepair

`func (o *Vehicle) GetRepair() int32`

GetRepair returns the Repair field if non-nil, zero value otherwise.

### GetRepairOk

`func (o *Vehicle) GetRepairOk() (*int32, bool)`

GetRepairOk returns a tuple with the Repair field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepair

`func (o *Vehicle) SetRepair(v int32)`

SetRepair sets Repair field to given value.


### GetDistance

`func (o *Vehicle) GetDistance() string`

GetDistance returns the Distance field if non-nil, zero value otherwise.

### GetDistanceOk

`func (o *Vehicle) GetDistanceOk() (*string, bool)`

GetDistanceOk returns a tuple with the Distance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDistance

`func (o *Vehicle) SetDistance(v string)`

SetDistance sets Distance field to given value.


### GetGarage

`func (o *Vehicle) GetGarage() int32`

GetGarage returns the Garage field if non-nil, zero value otherwise.

### GetGarageOk

`func (o *Vehicle) GetGarageOk() (*int32, bool)`

GetGarageOk returns a tuple with the Garage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGarage

`func (o *Vehicle) SetGarage(v int32)`

SetGarage sets Garage field to given value.


### GetHealth

`func (o *Vehicle) GetHealth() int32`

GetHealth returns the Health field if non-nil, zero value otherwise.

### GetHealthOk

`func (o *Vehicle) GetHealthOk() (*int32, bool)`

GetHealthOk returns a tuple with the Health field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealth

`func (o *Vehicle) SetHealth(v int32)`

SetHealth sets Health field to given value.


### GetDirtLevel

`func (o *Vehicle) GetDirtLevel() string`

GetDirtLevel returns the DirtLevel field if non-nil, zero value otherwise.

### GetDirtLevelOk

`func (o *Vehicle) GetDirtLevelOk() (*string, bool)`

GetDirtLevelOk returns a tuple with the DirtLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirtLevel

`func (o *Vehicle) SetDirtLevel(v string)`

SetDirtLevel sets DirtLevel field to given value.


### GetInteriorColor

`func (o *Vehicle) GetInteriorColor() int32`

GetInteriorColor returns the InteriorColor field if non-nil, zero value otherwise.

### GetInteriorColorOk

`func (o *Vehicle) GetInteriorColorOk() (*int32, bool)`

GetInteriorColorOk returns a tuple with the InteriorColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInteriorColor

`func (o *Vehicle) SetInteriorColor(v int32)`

SetInteriorColor sets InteriorColor field to given value.


### GetChipTuning

`func (o *Vehicle) GetChipTuning() int32`

GetChipTuning returns the ChipTuning field if non-nil, zero value otherwise.

### GetChipTuningOk

`func (o *Vehicle) GetChipTuningOk() (*int32, bool)`

GetChipTuningOk returns a tuple with the ChipTuning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChipTuning

`func (o *Vehicle) SetChipTuning(v int32)`

SetChipTuning sets ChipTuning field to given value.


### GetPaintArt

`func (o *Vehicle) GetPaintArt() int32`

GetPaintArt returns the PaintArt field if non-nil, zero value otherwise.

### GetPaintArtOk

`func (o *Vehicle) GetPaintArtOk() (*int32, bool)`

GetPaintArtOk returns a tuple with the PaintArt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaintArt

`func (o *Vehicle) SetPaintArt(v int32)`

SetPaintArt sets PaintArt field to given value.


### GetWheelColor

`func (o *Vehicle) GetWheelColor() int32`

GetWheelColor returns the WheelColor field if non-nil, zero value otherwise.

### GetWheelColorOk

`func (o *Vehicle) GetWheelColorOk() (*int32, bool)`

GetWheelColorOk returns a tuple with the WheelColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWheelColor

`func (o *Vehicle) SetWheelColor(v int32)`

SetWheelColor sets WheelColor field to given value.


### GetWheelType

`func (o *Vehicle) GetWheelType() int32`

GetWheelType returns the WheelType field if non-nil, zero value otherwise.

### GetWheelTypeOk

`func (o *Vehicle) GetWheelTypeOk() (*int32, bool)`

GetWheelTypeOk returns a tuple with the WheelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWheelType

`func (o *Vehicle) SetWheelType(v int32)`

SetWheelType sets WheelType field to given value.


### GetPlateText

`func (o *Vehicle) GetPlateText() string`

GetPlateText returns the PlateText field if non-nil, zero value otherwise.

### GetPlateTextOk

`func (o *Vehicle) GetPlateTextOk() (*string, bool)`

GetPlateTextOk returns a tuple with the PlateText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlateText

`func (o *Vehicle) SetPlateText(v string)`

SetPlateText sets PlateText field to given value.


### GetInsurance

`func (o *Vehicle) GetInsurance() string`

GetInsurance returns the Insurance field if non-nil, zero value otherwise.

### GetInsuranceOk

`func (o *Vehicle) GetInsuranceOk() (*string, bool)`

GetInsuranceOk returns a tuple with the Insurance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsurance

`func (o *Vehicle) SetInsurance(v string)`

SetInsurance sets Insurance field to given value.


### GetInsuranceExpiry

`func (o *Vehicle) GetInsuranceExpiry() int32`

GetInsuranceExpiry returns the InsuranceExpiry field if non-nil, zero value otherwise.

### GetInsuranceExpiryOk

`func (o *Vehicle) GetInsuranceExpiryOk() (*int32, bool)`

GetInsuranceExpiryOk returns a tuple with the InsuranceExpiry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsuranceExpiry

`func (o *Vehicle) SetInsuranceExpiry(v int32)`

SetInsuranceExpiry sets InsuranceExpiry field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


