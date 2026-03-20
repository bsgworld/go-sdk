# SmsAltChannel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | SMS text, max length is 765 chars for GSM 7-bit encoding (Latin), and 355 for UCS-2 | 
**Sender** | **string** | Sender name.   Up to 11 Latin letters or digits, up to 15 – only digits. To setup senders visit the [account](https://app.bsg.world/sms/senders) or use [sender api](#tag/Senders) | 
**ValiditySeconds** | Pointer to **NullableInt32** | Validity period in seconds. If not set, validity field is used | [optional] 
**Validity** | Pointer to **int32** | validity time in hours. The default is 72 hours. Integer from 1 to 72 | [optional] [default to 72]
**CheckStopList** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewSmsAltChannel

`func NewSmsAltChannel(text string, sender string, ) *SmsAltChannel`

NewSmsAltChannel instantiates a new SmsAltChannel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsAltChannelWithDefaults

`func NewSmsAltChannelWithDefaults() *SmsAltChannel`

NewSmsAltChannelWithDefaults instantiates a new SmsAltChannel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *SmsAltChannel) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *SmsAltChannel) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *SmsAltChannel) SetText(v string)`

SetText sets Text field to given value.


### GetSender

`func (o *SmsAltChannel) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SmsAltChannel) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SmsAltChannel) SetSender(v string)`

SetSender sets Sender field to given value.


### GetValiditySeconds

`func (o *SmsAltChannel) GetValiditySeconds() int32`

GetValiditySeconds returns the ValiditySeconds field if non-nil, zero value otherwise.

### GetValiditySecondsOk

`func (o *SmsAltChannel) GetValiditySecondsOk() (*int32, bool)`

GetValiditySecondsOk returns a tuple with the ValiditySeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValiditySeconds

`func (o *SmsAltChannel) SetValiditySeconds(v int32)`

SetValiditySeconds sets ValiditySeconds field to given value.

### HasValiditySeconds

`func (o *SmsAltChannel) HasValiditySeconds() bool`

HasValiditySeconds returns a boolean if a field has been set.

### SetValiditySecondsNil

`func (o *SmsAltChannel) SetValiditySecondsNil(b bool)`

 SetValiditySecondsNil sets the value for ValiditySeconds to be an explicit nil

### UnsetValiditySeconds
`func (o *SmsAltChannel) UnsetValiditySeconds()`

UnsetValiditySeconds ensures that no value is present for ValiditySeconds, not even an explicit nil
### GetValidity

`func (o *SmsAltChannel) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *SmsAltChannel) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *SmsAltChannel) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *SmsAltChannel) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### GetCheckStopList

`func (o *SmsAltChannel) GetCheckStopList() bool`

GetCheckStopList returns the CheckStopList field if non-nil, zero value otherwise.

### GetCheckStopListOk

`func (o *SmsAltChannel) GetCheckStopListOk() (*bool, bool)`

GetCheckStopListOk returns a tuple with the CheckStopList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckStopList

`func (o *SmsAltChannel) SetCheckStopList(v bool)`

SetCheckStopList sets CheckStopList field to given value.

### HasCheckStopList

`func (o *SmsAltChannel) HasCheckStopList() bool`

HasCheckStopList returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


