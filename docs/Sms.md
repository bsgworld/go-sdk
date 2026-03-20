# Sms

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sender** | **string** | Sender’s name: from 3 to 11 characters for the sender’s alphanumeric name (Latin letters, symbols, numbers, spaces); 3 to 15 characters for the sender’s numeric name. To setup senders visit the [account](https://app.bsg.world/sms/senders) | 
**Text** | **string** | SMS text, max length is 765 chars for GSM 7-bit encoding (Latin), and 355 for UCS-2 | 
**UnsubscribeCaption** | Pointer to **string** | Caption before unsubscribe link. Space between caption and link is required. | [optional] 
**Transliterate** | Pointer to **bool** | apply transliteration to sms text if it necessary | [optional] [default to false]
**ShortLinks** | Pointer to [**[]ShortLink**](ShortLink.md) | $shortLinks | [optional] 

## Methods

### NewSms

`func NewSms(sender string, text string, ) *Sms`

NewSms instantiates a new Sms object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsWithDefaults

`func NewSmsWithDefaults() *Sms`

NewSmsWithDefaults instantiates a new Sms object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSender

`func (o *Sms) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *Sms) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *Sms) SetSender(v string)`

SetSender sets Sender field to given value.


### GetText

`func (o *Sms) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *Sms) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *Sms) SetText(v string)`

SetText sets Text field to given value.


### GetUnsubscribeCaption

`func (o *Sms) GetUnsubscribeCaption() string`

GetUnsubscribeCaption returns the UnsubscribeCaption field if non-nil, zero value otherwise.

### GetUnsubscribeCaptionOk

`func (o *Sms) GetUnsubscribeCaptionOk() (*string, bool)`

GetUnsubscribeCaptionOk returns a tuple with the UnsubscribeCaption field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnsubscribeCaption

`func (o *Sms) SetUnsubscribeCaption(v string)`

SetUnsubscribeCaption sets UnsubscribeCaption field to given value.

### HasUnsubscribeCaption

`func (o *Sms) HasUnsubscribeCaption() bool`

HasUnsubscribeCaption returns a boolean if a field has been set.

### GetTransliterate

`func (o *Sms) GetTransliterate() bool`

GetTransliterate returns the Transliterate field if non-nil, zero value otherwise.

### GetTransliterateOk

`func (o *Sms) GetTransliterateOk() (*bool, bool)`

GetTransliterateOk returns a tuple with the Transliterate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransliterate

`func (o *Sms) SetTransliterate(v bool)`

SetTransliterate sets Transliterate field to given value.

### HasTransliterate

`func (o *Sms) HasTransliterate() bool`

HasTransliterate returns a boolean if a field has been set.

### GetShortLinks

`func (o *Sms) GetShortLinks() []ShortLink`

GetShortLinks returns the ShortLinks field if non-nil, zero value otherwise.

### GetShortLinksOk

`func (o *Sms) GetShortLinksOk() (*[]ShortLink, bool)`

GetShortLinksOk returns a tuple with the ShortLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortLinks

`func (o *Sms) SetShortLinks(v []ShortLink)`

SetShortLinks sets ShortLinks field to given value.

### HasShortLinks

`func (o *Sms) HasShortLinks() bool`

HasShortLinks returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


