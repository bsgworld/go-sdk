# RcsMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Phone** | [**Phone**](Phone.md) |  | 
**Sender** | **string** |  | 
**Options** | [**Options**](Options.md) |  | 
**AlternativeChannel** | Pointer to [**AlternativeChannel**](AlternativeChannel.md) |  | [optional] 
**CallbackUrl** | Pointer to **interface{}** | Link to get the delivery status of messages. If this parameter is specified in the method, it will take precedence over the value specified in the “Callback URL” field in the Personal Area. | [optional] 
**TariffCode** | Pointer to **NullableInt32** |  | [optional] 
**ValiditySeconds** | Pointer to **NullableInt32** | Validity period in seconds. If not set, field \&quot;validity\&quot; is used | [optional] 
**Validity** | Pointer to **NullableInt32** | Validity period in hours | [optional] [default to 72]
**AddToContactBook** | Pointer to **bool** |  | [optional] [default to true]
**CheckStopList** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewRcsMessage

`func NewRcsMessage(phone Phone, sender string, options Options, ) *RcsMessage`

NewRcsMessage instantiates a new RcsMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRcsMessageWithDefaults

`func NewRcsMessageWithDefaults() *RcsMessage`

NewRcsMessageWithDefaults instantiates a new RcsMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhone

`func (o *RcsMessage) GetPhone() Phone`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *RcsMessage) GetPhoneOk() (*Phone, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *RcsMessage) SetPhone(v Phone)`

SetPhone sets Phone field to given value.


### GetSender

`func (o *RcsMessage) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *RcsMessage) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *RcsMessage) SetSender(v string)`

SetSender sets Sender field to given value.


### GetOptions

`func (o *RcsMessage) GetOptions() Options`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *RcsMessage) GetOptionsOk() (*Options, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *RcsMessage) SetOptions(v Options)`

SetOptions sets Options field to given value.


### GetAlternativeChannel

`func (o *RcsMessage) GetAlternativeChannel() AlternativeChannel`

GetAlternativeChannel returns the AlternativeChannel field if non-nil, zero value otherwise.

### GetAlternativeChannelOk

`func (o *RcsMessage) GetAlternativeChannelOk() (*AlternativeChannel, bool)`

GetAlternativeChannelOk returns a tuple with the AlternativeChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternativeChannel

`func (o *RcsMessage) SetAlternativeChannel(v AlternativeChannel)`

SetAlternativeChannel sets AlternativeChannel field to given value.

### HasAlternativeChannel

`func (o *RcsMessage) HasAlternativeChannel() bool`

HasAlternativeChannel returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *RcsMessage) GetCallbackUrl() interface{}`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *RcsMessage) GetCallbackUrlOk() (*interface{}, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *RcsMessage) SetCallbackUrl(v interface{})`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *RcsMessage) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### SetCallbackUrlNil

`func (o *RcsMessage) SetCallbackUrlNil(b bool)`

 SetCallbackUrlNil sets the value for CallbackUrl to be an explicit nil

### UnsetCallbackUrl
`func (o *RcsMessage) UnsetCallbackUrl()`

UnsetCallbackUrl ensures that no value is present for CallbackUrl, not even an explicit nil
### GetTariffCode

`func (o *RcsMessage) GetTariffCode() int32`

GetTariffCode returns the TariffCode field if non-nil, zero value otherwise.

### GetTariffCodeOk

`func (o *RcsMessage) GetTariffCodeOk() (*int32, bool)`

GetTariffCodeOk returns a tuple with the TariffCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariffCode

`func (o *RcsMessage) SetTariffCode(v int32)`

SetTariffCode sets TariffCode field to given value.

### HasTariffCode

`func (o *RcsMessage) HasTariffCode() bool`

HasTariffCode returns a boolean if a field has been set.

### SetTariffCodeNil

`func (o *RcsMessage) SetTariffCodeNil(b bool)`

 SetTariffCodeNil sets the value for TariffCode to be an explicit nil

### UnsetTariffCode
`func (o *RcsMessage) UnsetTariffCode()`

UnsetTariffCode ensures that no value is present for TariffCode, not even an explicit nil
### GetValiditySeconds

`func (o *RcsMessage) GetValiditySeconds() int32`

GetValiditySeconds returns the ValiditySeconds field if non-nil, zero value otherwise.

### GetValiditySecondsOk

`func (o *RcsMessage) GetValiditySecondsOk() (*int32, bool)`

GetValiditySecondsOk returns a tuple with the ValiditySeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValiditySeconds

`func (o *RcsMessage) SetValiditySeconds(v int32)`

SetValiditySeconds sets ValiditySeconds field to given value.

### HasValiditySeconds

`func (o *RcsMessage) HasValiditySeconds() bool`

HasValiditySeconds returns a boolean if a field has been set.

### SetValiditySecondsNil

`func (o *RcsMessage) SetValiditySecondsNil(b bool)`

 SetValiditySecondsNil sets the value for ValiditySeconds to be an explicit nil

### UnsetValiditySeconds
`func (o *RcsMessage) UnsetValiditySeconds()`

UnsetValiditySeconds ensures that no value is present for ValiditySeconds, not even an explicit nil
### GetValidity

`func (o *RcsMessage) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *RcsMessage) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *RcsMessage) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *RcsMessage) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### SetValidityNil

`func (o *RcsMessage) SetValidityNil(b bool)`

 SetValidityNil sets the value for Validity to be an explicit nil

### UnsetValidity
`func (o *RcsMessage) UnsetValidity()`

UnsetValidity ensures that no value is present for Validity, not even an explicit nil
### GetAddToContactBook

`func (o *RcsMessage) GetAddToContactBook() bool`

GetAddToContactBook returns the AddToContactBook field if non-nil, zero value otherwise.

### GetAddToContactBookOk

`func (o *RcsMessage) GetAddToContactBookOk() (*bool, bool)`

GetAddToContactBookOk returns a tuple with the AddToContactBook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddToContactBook

`func (o *RcsMessage) SetAddToContactBook(v bool)`

SetAddToContactBook sets AddToContactBook field to given value.

### HasAddToContactBook

`func (o *RcsMessage) HasAddToContactBook() bool`

HasAddToContactBook returns a boolean if a field has been set.

### GetCheckStopList

`func (o *RcsMessage) GetCheckStopList() bool`

GetCheckStopList returns the CheckStopList field if non-nil, zero value otherwise.

### GetCheckStopListOk

`func (o *RcsMessage) GetCheckStopListOk() (*bool, bool)`

GetCheckStopListOk returns a tuple with the CheckStopList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckStopList

`func (o *RcsMessage) SetCheckStopList(v bool)`

SetCheckStopList sets CheckStopList field to given value.

### HasCheckStopList

`func (o *RcsMessage) HasCheckStopList() bool`

HasCheckStopList returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


