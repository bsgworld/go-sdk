# ViberCreateRequestMessagesInnerOptionsViber

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | Pointer to **string** | Button click URL (required if caption or img is set) | [optional] 
**Caption** | Pointer to **string** | Button caption (required if action or img is set) | [optional] 
**Img** | Pointer to **string** | Image URL (requires action and caption) | [optional] 
**AltRoute** | Pointer to [**ViberCreateRequestMessagesInnerOptionsViberAltRoute**](ViberCreateRequestMessagesInnerOptionsViberAltRoute.md) |  | [optional] 

## Methods

### NewViberCreateRequestMessagesInnerOptionsViber

`func NewViberCreateRequestMessagesInnerOptionsViber() *ViberCreateRequestMessagesInnerOptionsViber`

NewViberCreateRequestMessagesInnerOptionsViber instantiates a new ViberCreateRequestMessagesInnerOptionsViber object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberCreateRequestMessagesInnerOptionsViberWithDefaults

`func NewViberCreateRequestMessagesInnerOptionsViberWithDefaults() *ViberCreateRequestMessagesInnerOptionsViber`

NewViberCreateRequestMessagesInnerOptionsViberWithDefaults instantiates a new ViberCreateRequestMessagesInnerOptionsViber object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *ViberCreateRequestMessagesInnerOptionsViber) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *ViberCreateRequestMessagesInnerOptionsViber) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *ViberCreateRequestMessagesInnerOptionsViber) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *ViberCreateRequestMessagesInnerOptionsViber) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetCaption

`func (o *ViberCreateRequestMessagesInnerOptionsViber) GetCaption() string`

GetCaption returns the Caption field if non-nil, zero value otherwise.

### GetCaptionOk

`func (o *ViberCreateRequestMessagesInnerOptionsViber) GetCaptionOk() (*string, bool)`

GetCaptionOk returns a tuple with the Caption field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaption

`func (o *ViberCreateRequestMessagesInnerOptionsViber) SetCaption(v string)`

SetCaption sets Caption field to given value.

### HasCaption

`func (o *ViberCreateRequestMessagesInnerOptionsViber) HasCaption() bool`

HasCaption returns a boolean if a field has been set.

### GetImg

`func (o *ViberCreateRequestMessagesInnerOptionsViber) GetImg() string`

GetImg returns the Img field if non-nil, zero value otherwise.

### GetImgOk

`func (o *ViberCreateRequestMessagesInnerOptionsViber) GetImgOk() (*string, bool)`

GetImgOk returns a tuple with the Img field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImg

`func (o *ViberCreateRequestMessagesInnerOptionsViber) SetImg(v string)`

SetImg sets Img field to given value.

### HasImg

`func (o *ViberCreateRequestMessagesInnerOptionsViber) HasImg() bool`

HasImg returns a boolean if a field has been set.

### GetAltRoute

`func (o *ViberCreateRequestMessagesInnerOptionsViber) GetAltRoute() ViberCreateRequestMessagesInnerOptionsViberAltRoute`

GetAltRoute returns the AltRoute field if non-nil, zero value otherwise.

### GetAltRouteOk

`func (o *ViberCreateRequestMessagesInnerOptionsViber) GetAltRouteOk() (*ViberCreateRequestMessagesInnerOptionsViberAltRoute, bool)`

GetAltRouteOk returns a tuple with the AltRoute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAltRoute

`func (o *ViberCreateRequestMessagesInnerOptionsViber) SetAltRoute(v ViberCreateRequestMessagesInnerOptionsViberAltRoute)`

SetAltRoute sets AltRoute field to given value.

### HasAltRoute

`func (o *ViberCreateRequestMessagesInnerOptionsViber) HasAltRoute() bool`

HasAltRoute returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


