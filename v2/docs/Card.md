# Card

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | Pointer to **string** | Message title | [optional] 
**Text** | Pointer to **string** | It is specified only for the “text” message type. RCS message text is up to 1000 characters. Can contain emojis (character count for emojis according to UTF-16 code points. Simple emojis take 2 code points, complex emojis take 4, Cyrillic emojis take 1). If the message contains a link in the format http://nosms.cc/XXXX, the System will generate an Unsubscribe link while sending the message  **Please note:** If the message contains a media object, the text parameter is optional and can be omitted | [optional] 
**Media** | Pointer to [**Media**](Media.md) |  | [optional] 
**Suggestions** | Pointer to [**[]Suggestion**](Suggestion.md) | An array of objects containing information about nested buttons. Only up to 2 buttons can be added to a card. | [optional] 

## Methods

### NewCard

`func NewCard() *Card`

NewCard instantiates a new Card object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCardWithDefaults

`func NewCardWithDefaults() *Card`

NewCardWithDefaults instantiates a new Card object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *Card) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Card) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Card) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *Card) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetText

`func (o *Card) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *Card) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *Card) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *Card) HasText() bool`

HasText returns a boolean if a field has been set.

### GetMedia

`func (o *Card) GetMedia() Media`

GetMedia returns the Media field if non-nil, zero value otherwise.

### GetMediaOk

`func (o *Card) GetMediaOk() (*Media, bool)`

GetMediaOk returns a tuple with the Media field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMedia

`func (o *Card) SetMedia(v Media)`

SetMedia sets Media field to given value.

### HasMedia

`func (o *Card) HasMedia() bool`

HasMedia returns a boolean if a field has been set.

### GetSuggestions

`func (o *Card) GetSuggestions() []Suggestion`

GetSuggestions returns the Suggestions field if non-nil, zero value otherwise.

### GetSuggestionsOk

`func (o *Card) GetSuggestionsOk() (*[]Suggestion, bool)`

GetSuggestionsOk returns a tuple with the Suggestions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestions

`func (o *Card) SetSuggestions(v []Suggestion)`

SetSuggestions sets Suggestions field to given value.

### HasSuggestions

`func (o *Card) HasSuggestions() bool`

HasSuggestions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


