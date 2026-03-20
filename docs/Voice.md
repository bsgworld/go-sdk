# Voice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sender** | Pointer to **string** |  | [optional] 
**Text** | **string** |  | 
**Category** | **string** |  | 
**Voice** | Pointer to **NullableString** |  | [optional] 
**Lang** | Pointer to **NullableString** | Language or locale, like \&quot;en\&quot; or \&quot;en_UK) | [optional] 

## Methods

### NewVoice

`func NewVoice(text string, category string, ) *Voice`

NewVoice instantiates a new Voice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVoiceWithDefaults

`func NewVoiceWithDefaults() *Voice`

NewVoiceWithDefaults instantiates a new Voice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSender

`func (o *Voice) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *Voice) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *Voice) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *Voice) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetText

`func (o *Voice) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *Voice) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *Voice) SetText(v string)`

SetText sets Text field to given value.


### GetCategory

`func (o *Voice) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *Voice) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *Voice) SetCategory(v string)`

SetCategory sets Category field to given value.


### GetVoice

`func (o *Voice) GetVoice() string`

GetVoice returns the Voice field if non-nil, zero value otherwise.

### GetVoiceOk

`func (o *Voice) GetVoiceOk() (*string, bool)`

GetVoiceOk returns a tuple with the Voice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoice

`func (o *Voice) SetVoice(v string)`

SetVoice sets Voice field to given value.

### HasVoice

`func (o *Voice) HasVoice() bool`

HasVoice returns a boolean if a field has been set.

### SetVoiceNil

`func (o *Voice) SetVoiceNil(b bool)`

 SetVoiceNil sets the value for Voice to be an explicit nil

### UnsetVoice
`func (o *Voice) UnsetVoice()`

UnsetVoice ensures that no value is present for Voice, not even an explicit nil
### GetLang

`func (o *Voice) GetLang() string`

GetLang returns the Lang field if non-nil, zero value otherwise.

### GetLangOk

`func (o *Voice) GetLangOk() (*string, bool)`

GetLangOk returns a tuple with the Lang field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLang

`func (o *Voice) SetLang(v string)`

SetLang sets Lang field to given value.

### HasLang

`func (o *Voice) HasLang() bool`

HasLang returns a boolean if a field has been set.

### SetLangNil

`func (o *Voice) SetLangNil(b bool)`

 SetLangNil sets the value for Lang to be an explicit nil

### UnsetLang
`func (o *Voice) UnsetLang()`

UnsetLang ensures that no value is present for Lang, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


