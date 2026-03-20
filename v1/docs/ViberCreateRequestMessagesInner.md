# ViberCreateRequestMessagesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | Viber message text (required) | 
**AlphaName** | **string** | Viber sender name (required, must be pre-registered) | 
**To** | [**[]ViberCreateRequestMessagesInnerToInner**](ViberCreateRequestMessagesInnerToInner.md) | Recipients array (required) | 
**IsPromotional** | Pointer to **int32** | Message type: 1 &#x3D; promotional, 0 &#x3D; transactional | [optional] [default to 1]
**CallbackUrl** | Pointer to **string** | URL for receiving delivery reports | [optional] 
**ScheduledDatetime** | Pointer to **time.Time** | Schedule message for future delivery (UTC) | [optional] 
**Options** | Pointer to [**ViberCreateRequestMessagesInnerOptions**](ViberCreateRequestMessagesInnerOptions.md) |  | [optional] 

## Methods

### NewViberCreateRequestMessagesInner

`func NewViberCreateRequestMessagesInner(text string, alphaName string, to []ViberCreateRequestMessagesInnerToInner, ) *ViberCreateRequestMessagesInner`

NewViberCreateRequestMessagesInner instantiates a new ViberCreateRequestMessagesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberCreateRequestMessagesInnerWithDefaults

`func NewViberCreateRequestMessagesInnerWithDefaults() *ViberCreateRequestMessagesInner`

NewViberCreateRequestMessagesInnerWithDefaults instantiates a new ViberCreateRequestMessagesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *ViberCreateRequestMessagesInner) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *ViberCreateRequestMessagesInner) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *ViberCreateRequestMessagesInner) SetText(v string)`

SetText sets Text field to given value.


### GetAlphaName

`func (o *ViberCreateRequestMessagesInner) GetAlphaName() string`

GetAlphaName returns the AlphaName field if non-nil, zero value otherwise.

### GetAlphaNameOk

`func (o *ViberCreateRequestMessagesInner) GetAlphaNameOk() (*string, bool)`

GetAlphaNameOk returns a tuple with the AlphaName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlphaName

`func (o *ViberCreateRequestMessagesInner) SetAlphaName(v string)`

SetAlphaName sets AlphaName field to given value.


### GetTo

`func (o *ViberCreateRequestMessagesInner) GetTo() []ViberCreateRequestMessagesInnerToInner`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *ViberCreateRequestMessagesInner) GetToOk() (*[]ViberCreateRequestMessagesInnerToInner, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *ViberCreateRequestMessagesInner) SetTo(v []ViberCreateRequestMessagesInnerToInner)`

SetTo sets To field to given value.


### GetIsPromotional

`func (o *ViberCreateRequestMessagesInner) GetIsPromotional() int32`

GetIsPromotional returns the IsPromotional field if non-nil, zero value otherwise.

### GetIsPromotionalOk

`func (o *ViberCreateRequestMessagesInner) GetIsPromotionalOk() (*int32, bool)`

GetIsPromotionalOk returns a tuple with the IsPromotional field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPromotional

`func (o *ViberCreateRequestMessagesInner) SetIsPromotional(v int32)`

SetIsPromotional sets IsPromotional field to given value.

### HasIsPromotional

`func (o *ViberCreateRequestMessagesInner) HasIsPromotional() bool`

HasIsPromotional returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *ViberCreateRequestMessagesInner) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *ViberCreateRequestMessagesInner) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *ViberCreateRequestMessagesInner) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *ViberCreateRequestMessagesInner) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### GetScheduledDatetime

`func (o *ViberCreateRequestMessagesInner) GetScheduledDatetime() time.Time`

GetScheduledDatetime returns the ScheduledDatetime field if non-nil, zero value otherwise.

### GetScheduledDatetimeOk

`func (o *ViberCreateRequestMessagesInner) GetScheduledDatetimeOk() (*time.Time, bool)`

GetScheduledDatetimeOk returns a tuple with the ScheduledDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledDatetime

`func (o *ViberCreateRequestMessagesInner) SetScheduledDatetime(v time.Time)`

SetScheduledDatetime sets ScheduledDatetime field to given value.

### HasScheduledDatetime

`func (o *ViberCreateRequestMessagesInner) HasScheduledDatetime() bool`

HasScheduledDatetime returns a boolean if a field has been set.

### GetOptions

`func (o *ViberCreateRequestMessagesInner) GetOptions() ViberCreateRequestMessagesInnerOptions`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *ViberCreateRequestMessagesInner) GetOptionsOk() (*ViberCreateRequestMessagesInnerOptions, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *ViberCreateRequestMessagesInner) SetOptions(v ViberCreateRequestMessagesInnerOptions)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *ViberCreateRequestMessagesInner) HasOptions() bool`

HasOptions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


