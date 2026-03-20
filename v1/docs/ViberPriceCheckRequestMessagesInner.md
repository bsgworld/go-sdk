# ViberPriceCheckRequestMessagesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | Viber message text (required) | 
**AlphaName** | **string** | Viber sender name (required, must be pre-registered) | 
**To** | [**[]ViberPriceCheckRequestMessagesInnerToInner**](ViberPriceCheckRequestMessagesInnerToInner.md) | Recipients array (required) | 
**IsPromotional** | Pointer to **int32** | Optional. Message type: 1 &#x3D; promotional, 0 &#x3D; transactional. May affect pricing. | [optional] [default to 1]
**CallbackUrl** | Pointer to **string** | Optional. URL for receiving delivery reports (ignored for price check, but accepted for compatibility) | [optional] 
**ScheduledDatetime** | Pointer to **time.Time** | Optional. Schedule message for future delivery (ignored for price check, but accepted for compatibility) | [optional] 
**Options** | Pointer to [**ViberPriceCheckRequestMessagesInnerOptions**](ViberPriceCheckRequestMessagesInnerOptions.md) |  | [optional] 

## Methods

### NewViberPriceCheckRequestMessagesInner

`func NewViberPriceCheckRequestMessagesInner(text string, alphaName string, to []ViberPriceCheckRequestMessagesInnerToInner, ) *ViberPriceCheckRequestMessagesInner`

NewViberPriceCheckRequestMessagesInner instantiates a new ViberPriceCheckRequestMessagesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberPriceCheckRequestMessagesInnerWithDefaults

`func NewViberPriceCheckRequestMessagesInnerWithDefaults() *ViberPriceCheckRequestMessagesInner`

NewViberPriceCheckRequestMessagesInnerWithDefaults instantiates a new ViberPriceCheckRequestMessagesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *ViberPriceCheckRequestMessagesInner) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *ViberPriceCheckRequestMessagesInner) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *ViberPriceCheckRequestMessagesInner) SetText(v string)`

SetText sets Text field to given value.


### GetAlphaName

`func (o *ViberPriceCheckRequestMessagesInner) GetAlphaName() string`

GetAlphaName returns the AlphaName field if non-nil, zero value otherwise.

### GetAlphaNameOk

`func (o *ViberPriceCheckRequestMessagesInner) GetAlphaNameOk() (*string, bool)`

GetAlphaNameOk returns a tuple with the AlphaName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlphaName

`func (o *ViberPriceCheckRequestMessagesInner) SetAlphaName(v string)`

SetAlphaName sets AlphaName field to given value.


### GetTo

`func (o *ViberPriceCheckRequestMessagesInner) GetTo() []ViberPriceCheckRequestMessagesInnerToInner`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *ViberPriceCheckRequestMessagesInner) GetToOk() (*[]ViberPriceCheckRequestMessagesInnerToInner, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *ViberPriceCheckRequestMessagesInner) SetTo(v []ViberPriceCheckRequestMessagesInnerToInner)`

SetTo sets To field to given value.


### GetIsPromotional

`func (o *ViberPriceCheckRequestMessagesInner) GetIsPromotional() int32`

GetIsPromotional returns the IsPromotional field if non-nil, zero value otherwise.

### GetIsPromotionalOk

`func (o *ViberPriceCheckRequestMessagesInner) GetIsPromotionalOk() (*int32, bool)`

GetIsPromotionalOk returns a tuple with the IsPromotional field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPromotional

`func (o *ViberPriceCheckRequestMessagesInner) SetIsPromotional(v int32)`

SetIsPromotional sets IsPromotional field to given value.

### HasIsPromotional

`func (o *ViberPriceCheckRequestMessagesInner) HasIsPromotional() bool`

HasIsPromotional returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *ViberPriceCheckRequestMessagesInner) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *ViberPriceCheckRequestMessagesInner) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *ViberPriceCheckRequestMessagesInner) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *ViberPriceCheckRequestMessagesInner) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### GetScheduledDatetime

`func (o *ViberPriceCheckRequestMessagesInner) GetScheduledDatetime() time.Time`

GetScheduledDatetime returns the ScheduledDatetime field if non-nil, zero value otherwise.

### GetScheduledDatetimeOk

`func (o *ViberPriceCheckRequestMessagesInner) GetScheduledDatetimeOk() (*time.Time, bool)`

GetScheduledDatetimeOk returns a tuple with the ScheduledDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledDatetime

`func (o *ViberPriceCheckRequestMessagesInner) SetScheduledDatetime(v time.Time)`

SetScheduledDatetime sets ScheduledDatetime field to given value.

### HasScheduledDatetime

`func (o *ViberPriceCheckRequestMessagesInner) HasScheduledDatetime() bool`

HasScheduledDatetime returns a boolean if a field has been set.

### GetOptions

`func (o *ViberPriceCheckRequestMessagesInner) GetOptions() ViberPriceCheckRequestMessagesInnerOptions`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *ViberPriceCheckRequestMessagesInner) GetOptionsOk() (*ViberPriceCheckRequestMessagesInnerOptions, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *ViberPriceCheckRequestMessagesInner) SetOptions(v ViberPriceCheckRequestMessagesInnerOptions)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *ViberPriceCheckRequestMessagesInner) HasOptions() bool`

HasOptions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


