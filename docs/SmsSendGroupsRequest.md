# SmsSendGroupsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Groups** | Pointer to **[]int32** | one or several contact list id to send messages. id of the lists can be obtained: using the Get [lists API](#tag/Contact-List) in your account [Contact Book → Lists](https://app.bsg.world/addressbook/lists) | [optional] 
**Sender** | **string** | Sender’s name: from 3 to 11 characters for the sender’s alphanumeric name (Latin letters, symbols, numbers, spaces); 3 to 15 characters for the sender’s numeric name. To setup senders visit the [account](https://app.bsg.world/sms/senders) | 
**Text** | **string** | SMS text, max length is 765 chars for GSM 7-bit encoding (Latin), and 355 for UCS-2 | 
**TariffCode** | Pointer to **int32** | Tariff code null by default. Your can pass specified one if you have several. For more information please visit the [account prices](https://app.bsg.world/prices/sms) | [optional] 
**Validity** | Pointer to **int32** | validity time in hours. The default is 72 hours. Integer from 1 to 72 | [optional] [default to 72]
**StartAt** | Pointer to **time.Time** | Start sending the messages at | [optional] 
**ShortLinks** | Pointer to [**[]ShortLink**](ShortLink.md) |  | [optional] 
**Transliterate** | Pointer to **bool** | apply transliteration to sms text if it necessary | [optional] [default to false]
**CallbackUrl** | Pointer to **interface{}** | Link to get the delivery status of messages. If this parameter is specified in the method, it will take precedence over the value specified in the “Callback URL” field in the Personal Area. | [optional] 

## Methods

### NewSmsSendGroupsRequest

`func NewSmsSendGroupsRequest(sender string, text string, ) *SmsSendGroupsRequest`

NewSmsSendGroupsRequest instantiates a new SmsSendGroupsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsSendGroupsRequestWithDefaults

`func NewSmsSendGroupsRequestWithDefaults() *SmsSendGroupsRequest`

NewSmsSendGroupsRequestWithDefaults instantiates a new SmsSendGroupsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroups

`func (o *SmsSendGroupsRequest) GetGroups() []int32`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *SmsSendGroupsRequest) GetGroupsOk() (*[]int32, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *SmsSendGroupsRequest) SetGroups(v []int32)`

SetGroups sets Groups field to given value.

### HasGroups

`func (o *SmsSendGroupsRequest) HasGroups() bool`

HasGroups returns a boolean if a field has been set.

### GetSender

`func (o *SmsSendGroupsRequest) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SmsSendGroupsRequest) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SmsSendGroupsRequest) SetSender(v string)`

SetSender sets Sender field to given value.


### GetText

`func (o *SmsSendGroupsRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *SmsSendGroupsRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *SmsSendGroupsRequest) SetText(v string)`

SetText sets Text field to given value.


### GetTariffCode

`func (o *SmsSendGroupsRequest) GetTariffCode() int32`

GetTariffCode returns the TariffCode field if non-nil, zero value otherwise.

### GetTariffCodeOk

`func (o *SmsSendGroupsRequest) GetTariffCodeOk() (*int32, bool)`

GetTariffCodeOk returns a tuple with the TariffCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariffCode

`func (o *SmsSendGroupsRequest) SetTariffCode(v int32)`

SetTariffCode sets TariffCode field to given value.

### HasTariffCode

`func (o *SmsSendGroupsRequest) HasTariffCode() bool`

HasTariffCode returns a boolean if a field has been set.

### GetValidity

`func (o *SmsSendGroupsRequest) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *SmsSendGroupsRequest) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *SmsSendGroupsRequest) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *SmsSendGroupsRequest) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### GetStartAt

`func (o *SmsSendGroupsRequest) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *SmsSendGroupsRequest) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *SmsSendGroupsRequest) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.

### HasStartAt

`func (o *SmsSendGroupsRequest) HasStartAt() bool`

HasStartAt returns a boolean if a field has been set.

### GetShortLinks

`func (o *SmsSendGroupsRequest) GetShortLinks() []ShortLink`

GetShortLinks returns the ShortLinks field if non-nil, zero value otherwise.

### GetShortLinksOk

`func (o *SmsSendGroupsRequest) GetShortLinksOk() (*[]ShortLink, bool)`

GetShortLinksOk returns a tuple with the ShortLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortLinks

`func (o *SmsSendGroupsRequest) SetShortLinks(v []ShortLink)`

SetShortLinks sets ShortLinks field to given value.

### HasShortLinks

`func (o *SmsSendGroupsRequest) HasShortLinks() bool`

HasShortLinks returns a boolean if a field has been set.

### GetTransliterate

`func (o *SmsSendGroupsRequest) GetTransliterate() bool`

GetTransliterate returns the Transliterate field if non-nil, zero value otherwise.

### GetTransliterateOk

`func (o *SmsSendGroupsRequest) GetTransliterateOk() (*bool, bool)`

GetTransliterateOk returns a tuple with the Transliterate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransliterate

`func (o *SmsSendGroupsRequest) SetTransliterate(v bool)`

SetTransliterate sets Transliterate field to given value.

### HasTransliterate

`func (o *SmsSendGroupsRequest) HasTransliterate() bool`

HasTransliterate returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *SmsSendGroupsRequest) GetCallbackUrl() interface{}`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *SmsSendGroupsRequest) GetCallbackUrlOk() (*interface{}, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *SmsSendGroupsRequest) SetCallbackUrl(v interface{})`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *SmsSendGroupsRequest) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### SetCallbackUrlNil

`func (o *SmsSendGroupsRequest) SetCallbackUrlNil(b bool)`

 SetCallbackUrlNil sets the value for CallbackUrl to be an explicit nil

### UnsetCallbackUrl
`func (o *SmsSendGroupsRequest) UnsetCallbackUrl()`

UnsetCallbackUrl ensures that no value is present for CallbackUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


