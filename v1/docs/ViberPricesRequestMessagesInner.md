# ViberPricesRequestMessagesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | Viber message text (required) | 
**AlphaName** | **string** | Viber sender name (required, must be pre-registered) | 
**To** | [**[]ViberPricesRequestMessagesInnerToInner**](ViberPricesRequestMessagesInnerToInner.md) | Recipients array for price calculation | 

## Methods

### NewViberPricesRequestMessagesInner

`func NewViberPricesRequestMessagesInner(text string, alphaName string, to []ViberPricesRequestMessagesInnerToInner, ) *ViberPricesRequestMessagesInner`

NewViberPricesRequestMessagesInner instantiates a new ViberPricesRequestMessagesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberPricesRequestMessagesInnerWithDefaults

`func NewViberPricesRequestMessagesInnerWithDefaults() *ViberPricesRequestMessagesInner`

NewViberPricesRequestMessagesInnerWithDefaults instantiates a new ViberPricesRequestMessagesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *ViberPricesRequestMessagesInner) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *ViberPricesRequestMessagesInner) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *ViberPricesRequestMessagesInner) SetText(v string)`

SetText sets Text field to given value.


### GetAlphaName

`func (o *ViberPricesRequestMessagesInner) GetAlphaName() string`

GetAlphaName returns the AlphaName field if non-nil, zero value otherwise.

### GetAlphaNameOk

`func (o *ViberPricesRequestMessagesInner) GetAlphaNameOk() (*string, bool)`

GetAlphaNameOk returns a tuple with the AlphaName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlphaName

`func (o *ViberPricesRequestMessagesInner) SetAlphaName(v string)`

SetAlphaName sets AlphaName field to given value.


### GetTo

`func (o *ViberPricesRequestMessagesInner) GetTo() []ViberPricesRequestMessagesInnerToInner`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *ViberPricesRequestMessagesInner) GetToOk() (*[]ViberPricesRequestMessagesInnerToInner, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *ViberPricesRequestMessagesInner) SetTo(v []ViberPricesRequestMessagesInnerToInner)`

SetTo sets To field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


