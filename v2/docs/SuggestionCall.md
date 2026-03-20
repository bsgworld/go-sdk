# SuggestionCall

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Suggestion type | 
**Text** | **string** | text of the button | 
**Phone** | **string** | Phone number to call with a click of a button. 9 – 15 characters (the length must take into account the country code and phone number, the phone number is indicated without +). When sending RCS messages to the country of Ukraine, the phone number to call via the button must be a Ukrainian number | 
**PostbackData** | Pointer to **string** | Extra data to send on callback_url when user click on the button | [optional] 

## Methods

### NewSuggestionCall

`func NewSuggestionCall(type_ string, text string, phone string, ) *SuggestionCall`

NewSuggestionCall instantiates a new SuggestionCall object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuggestionCallWithDefaults

`func NewSuggestionCallWithDefaults() *SuggestionCall`

NewSuggestionCallWithDefaults instantiates a new SuggestionCall object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *SuggestionCall) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SuggestionCall) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SuggestionCall) SetType(v string)`

SetType sets Type field to given value.


### GetText

`func (o *SuggestionCall) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *SuggestionCall) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *SuggestionCall) SetText(v string)`

SetText sets Text field to given value.


### GetPhone

`func (o *SuggestionCall) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *SuggestionCall) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *SuggestionCall) SetPhone(v string)`

SetPhone sets Phone field to given value.


### GetPostbackData

`func (o *SuggestionCall) GetPostbackData() string`

GetPostbackData returns the PostbackData field if non-nil, zero value otherwise.

### GetPostbackDataOk

`func (o *SuggestionCall) GetPostbackDataOk() (*string, bool)`

GetPostbackDataOk returns a tuple with the PostbackData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostbackData

`func (o *SuggestionCall) SetPostbackData(v string)`

SetPostbackData sets PostbackData field to given value.

### HasPostbackData

`func (o *SuggestionCall) HasPostbackData() bool`

HasPostbackData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


