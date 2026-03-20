# Suggestion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Suggestion type | 
**Text** | **string** | text of the button | 
**Url** | **string** | A link to go through a click on the button. The link should start with http/https.  If you need to add a button to unsubscribe the user from the mailing list, you can specify a link in the format http://nosms.cc/XXXX – the Platform will generate an Unsubscribe link for this action when sending the message. When the user clicks on the unsubscribe button, the user’s number will be added to the RCS email stop list. | 
**PostbackData** | Pointer to **string** | Extra data to send on callback_url when user click on the button | [optional] 
**Phone** | **string** | Phone number to call with a click of a button. 9 – 15 characters (the length must take into account the country code and phone number, the phone number is indicated without +). When sending RCS messages to the country of Ukraine, the phone number to call via the button must be a Ukrainian number | 

## Methods

### NewSuggestion

`func NewSuggestion(type_ string, text string, url string, phone string, ) *Suggestion`

NewSuggestion instantiates a new Suggestion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuggestionWithDefaults

`func NewSuggestionWithDefaults() *Suggestion`

NewSuggestionWithDefaults instantiates a new Suggestion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *Suggestion) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Suggestion) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Suggestion) SetType(v string)`

SetType sets Type field to given value.


### GetText

`func (o *Suggestion) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *Suggestion) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *Suggestion) SetText(v string)`

SetText sets Text field to given value.


### GetUrl

`func (o *Suggestion) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *Suggestion) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *Suggestion) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetPostbackData

`func (o *Suggestion) GetPostbackData() string`

GetPostbackData returns the PostbackData field if non-nil, zero value otherwise.

### GetPostbackDataOk

`func (o *Suggestion) GetPostbackDataOk() (*string, bool)`

GetPostbackDataOk returns a tuple with the PostbackData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostbackData

`func (o *Suggestion) SetPostbackData(v string)`

SetPostbackData sets PostbackData field to given value.

### HasPostbackData

`func (o *Suggestion) HasPostbackData() bool`

HasPostbackData returns a boolean if a field has been set.

### GetPhone

`func (o *Suggestion) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *Suggestion) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *Suggestion) SetPhone(v string)`

SetPhone sets Phone field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


