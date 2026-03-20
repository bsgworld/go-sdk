# ViberCreateRequestMessagesInnerOptionsViberAltRoute

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Originator** | **string** | SMS sender name for fallback | 
**Text** | **string** | SMS text for fallback | 
**CallbackUrl** | Pointer to **string** | Callback URL for SMS fallback | [optional] 
**Reference** | Pointer to **string** | Reference for SMS fallback | [optional] 

## Methods

### NewViberCreateRequestMessagesInnerOptionsViberAltRoute

`func NewViberCreateRequestMessagesInnerOptionsViberAltRoute(originator string, text string, ) *ViberCreateRequestMessagesInnerOptionsViberAltRoute`

NewViberCreateRequestMessagesInnerOptionsViberAltRoute instantiates a new ViberCreateRequestMessagesInnerOptionsViberAltRoute object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberCreateRequestMessagesInnerOptionsViberAltRouteWithDefaults

`func NewViberCreateRequestMessagesInnerOptionsViberAltRouteWithDefaults() *ViberCreateRequestMessagesInnerOptionsViberAltRoute`

NewViberCreateRequestMessagesInnerOptionsViberAltRouteWithDefaults instantiates a new ViberCreateRequestMessagesInnerOptionsViberAltRoute object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOriginator

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) GetOriginator() string`

GetOriginator returns the Originator field if non-nil, zero value otherwise.

### GetOriginatorOk

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) GetOriginatorOk() (*string, bool)`

GetOriginatorOk returns a tuple with the Originator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginator

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) SetOriginator(v string)`

SetOriginator sets Originator field to given value.


### GetText

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) SetText(v string)`

SetText sets Text field to given value.


### GetCallbackUrl

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### GetReference

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *ViberCreateRequestMessagesInnerOptionsViberAltRoute) HasReference() bool`

HasReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


