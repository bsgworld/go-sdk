# SmsSendIndividualRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Messages** | [**[]IndividualMessageData**](IndividualMessageData.md) |  | 
**TariffCode** | Pointer to **int32** | Tariff code null by default. Your can pass specified one if you have several. For more information please visit the [account prices](https://app.bsg.world/prices/sms) | [optional] 
**Validity** | Pointer to **int32** | validity time in hours. The default is 72 hours. Integer from 1 to 72 | [optional] [default to 72]
**StartAt** | Pointer to **int32** | validity time in hours. The default is 72 hours. Integer from 1 to 72 | [optional] [default to 72]
**CallbackUrl** | Pointer to **interface{}** | Link to get the delivery status of messages. If this parameter is specified in the method, it will take precedence over the value specified in the “Callback URL” field in the Personal Area. | [optional] 

## Methods

### NewSmsSendIndividualRequest

`func NewSmsSendIndividualRequest(messages []IndividualMessageData, ) *SmsSendIndividualRequest`

NewSmsSendIndividualRequest instantiates a new SmsSendIndividualRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsSendIndividualRequestWithDefaults

`func NewSmsSendIndividualRequestWithDefaults() *SmsSendIndividualRequest`

NewSmsSendIndividualRequestWithDefaults instantiates a new SmsSendIndividualRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessages

`func (o *SmsSendIndividualRequest) GetMessages() []IndividualMessageData`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *SmsSendIndividualRequest) GetMessagesOk() (*[]IndividualMessageData, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *SmsSendIndividualRequest) SetMessages(v []IndividualMessageData)`

SetMessages sets Messages field to given value.


### GetTariffCode

`func (o *SmsSendIndividualRequest) GetTariffCode() int32`

GetTariffCode returns the TariffCode field if non-nil, zero value otherwise.

### GetTariffCodeOk

`func (o *SmsSendIndividualRequest) GetTariffCodeOk() (*int32, bool)`

GetTariffCodeOk returns a tuple with the TariffCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariffCode

`func (o *SmsSendIndividualRequest) SetTariffCode(v int32)`

SetTariffCode sets TariffCode field to given value.

### HasTariffCode

`func (o *SmsSendIndividualRequest) HasTariffCode() bool`

HasTariffCode returns a boolean if a field has been set.

### GetValidity

`func (o *SmsSendIndividualRequest) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *SmsSendIndividualRequest) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *SmsSendIndividualRequest) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *SmsSendIndividualRequest) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### GetStartAt

`func (o *SmsSendIndividualRequest) GetStartAt() int32`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *SmsSendIndividualRequest) GetStartAtOk() (*int32, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *SmsSendIndividualRequest) SetStartAt(v int32)`

SetStartAt sets StartAt field to given value.

### HasStartAt

`func (o *SmsSendIndividualRequest) HasStartAt() bool`

HasStartAt returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *SmsSendIndividualRequest) GetCallbackUrl() interface{}`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *SmsSendIndividualRequest) GetCallbackUrlOk() (*interface{}, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *SmsSendIndividualRequest) SetCallbackUrl(v interface{})`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *SmsSendIndividualRequest) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### SetCallbackUrlNil

`func (o *SmsSendIndividualRequest) SetCallbackUrlNil(b bool)`

 SetCallbackUrlNil sets the value for CallbackUrl to be an explicit nil

### UnsetCallbackUrl
`func (o *SmsSendIndividualRequest) UnsetCallbackUrl()`

UnsetCallbackUrl ensures that no value is present for CallbackUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


