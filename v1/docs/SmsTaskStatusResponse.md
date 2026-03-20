# SmsTaskStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code: 0 for success, 30 for \&quot;Task not found\&quot; | 
**ErrorDescription** | **string** | Human-readable error description | 
**Originator** | Pointer to **string** | Sender name used for messages in this task | [optional] 
**Body** | Pointer to **string** | Message text for bulk task | [optional] 
**Validity** | Pointer to **int32** | Message validity period in hours (max 3660 hours &#x3D; ~5 months) | [optional] 
**Totalprice** | Pointer to **float32** | Total cost for all messages in task | [optional] 
**Currency** | Pointer to **string** | Currency code according to ISO-4217 | [optional] 
**Sent** | Pointer to **int32** | Number of messages submitted to operators | [optional] 
**Total** | Pointer to **int32** | Total number of messages in task | [optional] 
**Queued** | Pointer to **int32** | Number of messages still in queue | [optional] 
**Accepted** | Pointer to **int32** | Number of messages accepted by operators | [optional] 
**Enroute** | Pointer to **int32** | Number of messages en route to destination | [optional] 
**Delivered** | Pointer to **int32** | Number of successfully delivered messages | [optional] 
**Expired** | Pointer to **int32** | Number of expired messages | [optional] 
**Undeliverable** | Pointer to **int32** | Number of undeliverable messages | [optional] 
**Unknown** | Pointer to **int32** | Number of messages with unknown status | [optional] 

## Methods

### NewSmsTaskStatusResponse

`func NewSmsTaskStatusResponse(error_ int32, errorDescription string, ) *SmsTaskStatusResponse`

NewSmsTaskStatusResponse instantiates a new SmsTaskStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsTaskStatusResponseWithDefaults

`func NewSmsTaskStatusResponseWithDefaults() *SmsTaskStatusResponse`

NewSmsTaskStatusResponseWithDefaults instantiates a new SmsTaskStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *SmsTaskStatusResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *SmsTaskStatusResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *SmsTaskStatusResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *SmsTaskStatusResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *SmsTaskStatusResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *SmsTaskStatusResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetOriginator

`func (o *SmsTaskStatusResponse) GetOriginator() string`

GetOriginator returns the Originator field if non-nil, zero value otherwise.

### GetOriginatorOk

`func (o *SmsTaskStatusResponse) GetOriginatorOk() (*string, bool)`

GetOriginatorOk returns a tuple with the Originator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginator

`func (o *SmsTaskStatusResponse) SetOriginator(v string)`

SetOriginator sets Originator field to given value.

### HasOriginator

`func (o *SmsTaskStatusResponse) HasOriginator() bool`

HasOriginator returns a boolean if a field has been set.

### GetBody

`func (o *SmsTaskStatusResponse) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *SmsTaskStatusResponse) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *SmsTaskStatusResponse) SetBody(v string)`

SetBody sets Body field to given value.

### HasBody

`func (o *SmsTaskStatusResponse) HasBody() bool`

HasBody returns a boolean if a field has been set.

### GetValidity

`func (o *SmsTaskStatusResponse) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *SmsTaskStatusResponse) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *SmsTaskStatusResponse) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *SmsTaskStatusResponse) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### GetTotalprice

`func (o *SmsTaskStatusResponse) GetTotalprice() float32`

GetTotalprice returns the Totalprice field if non-nil, zero value otherwise.

### GetTotalpriceOk

`func (o *SmsTaskStatusResponse) GetTotalpriceOk() (*float32, bool)`

GetTotalpriceOk returns a tuple with the Totalprice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalprice

`func (o *SmsTaskStatusResponse) SetTotalprice(v float32)`

SetTotalprice sets Totalprice field to given value.

### HasTotalprice

`func (o *SmsTaskStatusResponse) HasTotalprice() bool`

HasTotalprice returns a boolean if a field has been set.

### GetCurrency

`func (o *SmsTaskStatusResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SmsTaskStatusResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SmsTaskStatusResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *SmsTaskStatusResponse) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetSent

`func (o *SmsTaskStatusResponse) GetSent() int32`

GetSent returns the Sent field if non-nil, zero value otherwise.

### GetSentOk

`func (o *SmsTaskStatusResponse) GetSentOk() (*int32, bool)`

GetSentOk returns a tuple with the Sent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSent

`func (o *SmsTaskStatusResponse) SetSent(v int32)`

SetSent sets Sent field to given value.

### HasSent

`func (o *SmsTaskStatusResponse) HasSent() bool`

HasSent returns a boolean if a field has been set.

### GetTotal

`func (o *SmsTaskStatusResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *SmsTaskStatusResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *SmsTaskStatusResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *SmsTaskStatusResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetQueued

`func (o *SmsTaskStatusResponse) GetQueued() int32`

GetQueued returns the Queued field if non-nil, zero value otherwise.

### GetQueuedOk

`func (o *SmsTaskStatusResponse) GetQueuedOk() (*int32, bool)`

GetQueuedOk returns a tuple with the Queued field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueued

`func (o *SmsTaskStatusResponse) SetQueued(v int32)`

SetQueued sets Queued field to given value.

### HasQueued

`func (o *SmsTaskStatusResponse) HasQueued() bool`

HasQueued returns a boolean if a field has been set.

### GetAccepted

`func (o *SmsTaskStatusResponse) GetAccepted() int32`

GetAccepted returns the Accepted field if non-nil, zero value otherwise.

### GetAcceptedOk

`func (o *SmsTaskStatusResponse) GetAcceptedOk() (*int32, bool)`

GetAcceptedOk returns a tuple with the Accepted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccepted

`func (o *SmsTaskStatusResponse) SetAccepted(v int32)`

SetAccepted sets Accepted field to given value.

### HasAccepted

`func (o *SmsTaskStatusResponse) HasAccepted() bool`

HasAccepted returns a boolean if a field has been set.

### GetEnroute

`func (o *SmsTaskStatusResponse) GetEnroute() int32`

GetEnroute returns the Enroute field if non-nil, zero value otherwise.

### GetEnrouteOk

`func (o *SmsTaskStatusResponse) GetEnrouteOk() (*int32, bool)`

GetEnrouteOk returns a tuple with the Enroute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnroute

`func (o *SmsTaskStatusResponse) SetEnroute(v int32)`

SetEnroute sets Enroute field to given value.

### HasEnroute

`func (o *SmsTaskStatusResponse) HasEnroute() bool`

HasEnroute returns a boolean if a field has been set.

### GetDelivered

`func (o *SmsTaskStatusResponse) GetDelivered() int32`

GetDelivered returns the Delivered field if non-nil, zero value otherwise.

### GetDeliveredOk

`func (o *SmsTaskStatusResponse) GetDeliveredOk() (*int32, bool)`

GetDeliveredOk returns a tuple with the Delivered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivered

`func (o *SmsTaskStatusResponse) SetDelivered(v int32)`

SetDelivered sets Delivered field to given value.

### HasDelivered

`func (o *SmsTaskStatusResponse) HasDelivered() bool`

HasDelivered returns a boolean if a field has been set.

### GetExpired

`func (o *SmsTaskStatusResponse) GetExpired() int32`

GetExpired returns the Expired field if non-nil, zero value otherwise.

### GetExpiredOk

`func (o *SmsTaskStatusResponse) GetExpiredOk() (*int32, bool)`

GetExpiredOk returns a tuple with the Expired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpired

`func (o *SmsTaskStatusResponse) SetExpired(v int32)`

SetExpired sets Expired field to given value.

### HasExpired

`func (o *SmsTaskStatusResponse) HasExpired() bool`

HasExpired returns a boolean if a field has been set.

### GetUndeliverable

`func (o *SmsTaskStatusResponse) GetUndeliverable() int32`

GetUndeliverable returns the Undeliverable field if non-nil, zero value otherwise.

### GetUndeliverableOk

`func (o *SmsTaskStatusResponse) GetUndeliverableOk() (*int32, bool)`

GetUndeliverableOk returns a tuple with the Undeliverable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUndeliverable

`func (o *SmsTaskStatusResponse) SetUndeliverable(v int32)`

SetUndeliverable sets Undeliverable field to given value.

### HasUndeliverable

`func (o *SmsTaskStatusResponse) HasUndeliverable() bool`

HasUndeliverable returns a boolean if a field has been set.

### GetUnknown

`func (o *SmsTaskStatusResponse) GetUnknown() int32`

GetUnknown returns the Unknown field if non-nil, zero value otherwise.

### GetUnknownOk

`func (o *SmsTaskStatusResponse) GetUnknownOk() (*int32, bool)`

GetUnknownOk returns a tuple with the Unknown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnknown

`func (o *SmsTaskStatusResponse) SetUnknown(v int32)`

SetUnknown sets Unknown field to given value.

### HasUnknown

`func (o *SmsTaskStatusResponse) HasUnknown() bool`

HasUnknown returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


