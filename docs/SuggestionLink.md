# SuggestionLink

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Suggestion type | 
**Text** | **string** | text of the button | 
**Url** | **string** | A link to go through a click on the button. The link should start with http/https.  If you need to add a button to unsubscribe the user from the mailing list, you can specify a link in the format http://nosms.cc/XXXX – the Platform will generate an Unsubscribe link for this action when sending the message. When the user clicks on the unsubscribe button, the user’s number will be added to the RCS email stop list. | 
**PostbackData** | Pointer to **string** | Extra data to send on callback_url when user click on the button | [optional] 

## Methods

### NewSuggestionLink

`func NewSuggestionLink(type_ string, text string, url string, ) *SuggestionLink`

NewSuggestionLink instantiates a new SuggestionLink object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSuggestionLinkWithDefaults

`func NewSuggestionLinkWithDefaults() *SuggestionLink`

NewSuggestionLinkWithDefaults instantiates a new SuggestionLink object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *SuggestionLink) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SuggestionLink) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SuggestionLink) SetType(v string)`

SetType sets Type field to given value.


### GetText

`func (o *SuggestionLink) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *SuggestionLink) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *SuggestionLink) SetText(v string)`

SetText sets Text field to given value.


### GetUrl

`func (o *SuggestionLink) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *SuggestionLink) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *SuggestionLink) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetPostbackData

`func (o *SuggestionLink) GetPostbackData() string`

GetPostbackData returns the PostbackData field if non-nil, zero value otherwise.

### GetPostbackDataOk

`func (o *SuggestionLink) GetPostbackDataOk() (*string, bool)`

GetPostbackDataOk returns a tuple with the PostbackData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostbackData

`func (o *SuggestionLink) SetPostbackData(v string)`

SetPostbackData sets PostbackData field to given value.

### HasPostbackData

`func (o *SuggestionLink) HasPostbackData() bool`

HasPostbackData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


