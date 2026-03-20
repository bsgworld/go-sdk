# Telegram

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sender** | Pointer to **string** |  | [optional] 
**Text** | **NullableString** |  | 

## Methods

### NewTelegram

`func NewTelegram(text NullableString, ) *Telegram`

NewTelegram instantiates a new Telegram object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTelegramWithDefaults

`func NewTelegramWithDefaults() *Telegram`

NewTelegramWithDefaults instantiates a new Telegram object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSender

`func (o *Telegram) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *Telegram) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *Telegram) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *Telegram) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetText

`func (o *Telegram) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *Telegram) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *Telegram) SetText(v string)`

SetText sets Text field to given value.


### SetTextNil

`func (o *Telegram) SetTextNil(b bool)`

 SetTextNil sets the value for Text to be an explicit nil

### UnsetText
`func (o *Telegram) UnsetText()`

UnsetText ensures that no value is present for Text, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


