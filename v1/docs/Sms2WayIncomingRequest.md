# Sms2WayIncomingRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StartDate** | **time.Time** | Start date and time for message retrieval (Y-m-d H:i:s format) | 
**EndDate** | **time.Time** | End date and time for message retrieval (Y-m-d H:i:s format) | 
**Sender** | Pointer to **NullableString** | Filter by specific sender (optional) | [optional] 

## Methods

### NewSms2WayIncomingRequest

`func NewSms2WayIncomingRequest(startDate time.Time, endDate time.Time, ) *Sms2WayIncomingRequest`

NewSms2WayIncomingRequest instantiates a new Sms2WayIncomingRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSms2WayIncomingRequestWithDefaults

`func NewSms2WayIncomingRequestWithDefaults() *Sms2WayIncomingRequest`

NewSms2WayIncomingRequestWithDefaults instantiates a new Sms2WayIncomingRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStartDate

`func (o *Sms2WayIncomingRequest) GetStartDate() time.Time`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *Sms2WayIncomingRequest) GetStartDateOk() (*time.Time, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *Sms2WayIncomingRequest) SetStartDate(v time.Time)`

SetStartDate sets StartDate field to given value.


### GetEndDate

`func (o *Sms2WayIncomingRequest) GetEndDate() time.Time`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *Sms2WayIncomingRequest) GetEndDateOk() (*time.Time, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *Sms2WayIncomingRequest) SetEndDate(v time.Time)`

SetEndDate sets EndDate field to given value.


### GetSender

`func (o *Sms2WayIncomingRequest) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *Sms2WayIncomingRequest) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *Sms2WayIncomingRequest) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *Sms2WayIncomingRequest) HasSender() bool`

HasSender returns a boolean if a field has been set.

### SetSenderNil

`func (o *Sms2WayIncomingRequest) SetSenderNil(b bool)`

 SetSenderNil sets the value for Sender to be an explicit nil

### UnsetSender
`func (o *Sms2WayIncomingRequest) UnsetSender()`

UnsetSender ensures that no value is present for Sender, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


