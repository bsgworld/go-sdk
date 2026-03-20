# StatJobsCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Job creation type | 
**MessageId** | **[]int32** | Message Ids | 
**TimeInFrom** | **time.Time** | Datetime when messages were received on the platform | 
**TimeInTo** | **time.Time** | Datetime when messages were received on the platform | 
**TimeSentFrom** | Pointer to **time.Time** | Time of sending messages from the platform “from” | [optional] 
**TimeSentTo** | Pointer to **time.Time** | Time of sending messages from the platform “to” | [optional] 
**Phones** | Pointer to **[]int32** | phone list | [optional] 
**Sender** | Pointer to **string** | Source from where the message came to the platform | [optional] 
**Source** | Pointer to **string** | Source from where the message came to the platform | [optional] 
**Country** | Pointer to **string** | The name of the country for search | [optional] 
**OperatorId** | Pointer to **string** | Indication of the country operator | [optional] 
**Status** | Pointer to **string** | The status of the messages to display | [optional] 
**SlClicks** | Pointer to **string** | The field is available only to the clients who have enabled Short URL service | [optional] 
**SlClicksComp** | Pointer to **string** | Comparison operator with the clicks count value | [optional] 
**SlClicksCount** | Pointer to **string** | Comparison operator with the clicks count value | [optional] 

## Methods

### NewStatJobsCreateRequest

`func NewStatJobsCreateRequest(type_ string, messageId []int32, timeInFrom time.Time, timeInTo time.Time, ) *StatJobsCreateRequest`

NewStatJobsCreateRequest instantiates a new StatJobsCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatJobsCreateRequestWithDefaults

`func NewStatJobsCreateRequestWithDefaults() *StatJobsCreateRequest`

NewStatJobsCreateRequestWithDefaults instantiates a new StatJobsCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *StatJobsCreateRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *StatJobsCreateRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *StatJobsCreateRequest) SetType(v string)`

SetType sets Type field to given value.


### GetMessageId

`func (o *StatJobsCreateRequest) GetMessageId() []int32`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *StatJobsCreateRequest) GetMessageIdOk() (*[]int32, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *StatJobsCreateRequest) SetMessageId(v []int32)`

SetMessageId sets MessageId field to given value.


### GetTimeInFrom

`func (o *StatJobsCreateRequest) GetTimeInFrom() time.Time`

GetTimeInFrom returns the TimeInFrom field if non-nil, zero value otherwise.

### GetTimeInFromOk

`func (o *StatJobsCreateRequest) GetTimeInFromOk() (*time.Time, bool)`

GetTimeInFromOk returns a tuple with the TimeInFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeInFrom

`func (o *StatJobsCreateRequest) SetTimeInFrom(v time.Time)`

SetTimeInFrom sets TimeInFrom field to given value.


### GetTimeInTo

`func (o *StatJobsCreateRequest) GetTimeInTo() time.Time`

GetTimeInTo returns the TimeInTo field if non-nil, zero value otherwise.

### GetTimeInToOk

`func (o *StatJobsCreateRequest) GetTimeInToOk() (*time.Time, bool)`

GetTimeInToOk returns a tuple with the TimeInTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeInTo

`func (o *StatJobsCreateRequest) SetTimeInTo(v time.Time)`

SetTimeInTo sets TimeInTo field to given value.


### GetTimeSentFrom

`func (o *StatJobsCreateRequest) GetTimeSentFrom() time.Time`

GetTimeSentFrom returns the TimeSentFrom field if non-nil, zero value otherwise.

### GetTimeSentFromOk

`func (o *StatJobsCreateRequest) GetTimeSentFromOk() (*time.Time, bool)`

GetTimeSentFromOk returns a tuple with the TimeSentFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSentFrom

`func (o *StatJobsCreateRequest) SetTimeSentFrom(v time.Time)`

SetTimeSentFrom sets TimeSentFrom field to given value.

### HasTimeSentFrom

`func (o *StatJobsCreateRequest) HasTimeSentFrom() bool`

HasTimeSentFrom returns a boolean if a field has been set.

### GetTimeSentTo

`func (o *StatJobsCreateRequest) GetTimeSentTo() time.Time`

GetTimeSentTo returns the TimeSentTo field if non-nil, zero value otherwise.

### GetTimeSentToOk

`func (o *StatJobsCreateRequest) GetTimeSentToOk() (*time.Time, bool)`

GetTimeSentToOk returns a tuple with the TimeSentTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSentTo

`func (o *StatJobsCreateRequest) SetTimeSentTo(v time.Time)`

SetTimeSentTo sets TimeSentTo field to given value.

### HasTimeSentTo

`func (o *StatJobsCreateRequest) HasTimeSentTo() bool`

HasTimeSentTo returns a boolean if a field has been set.

### GetPhones

`func (o *StatJobsCreateRequest) GetPhones() []int32`

GetPhones returns the Phones field if non-nil, zero value otherwise.

### GetPhonesOk

`func (o *StatJobsCreateRequest) GetPhonesOk() (*[]int32, bool)`

GetPhonesOk returns a tuple with the Phones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhones

`func (o *StatJobsCreateRequest) SetPhones(v []int32)`

SetPhones sets Phones field to given value.

### HasPhones

`func (o *StatJobsCreateRequest) HasPhones() bool`

HasPhones returns a boolean if a field has been set.

### GetSender

`func (o *StatJobsCreateRequest) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *StatJobsCreateRequest) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *StatJobsCreateRequest) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *StatJobsCreateRequest) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetSource

`func (o *StatJobsCreateRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *StatJobsCreateRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *StatJobsCreateRequest) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *StatJobsCreateRequest) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetCountry

`func (o *StatJobsCreateRequest) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *StatJobsCreateRequest) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *StatJobsCreateRequest) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *StatJobsCreateRequest) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetOperatorId

`func (o *StatJobsCreateRequest) GetOperatorId() string`

GetOperatorId returns the OperatorId field if non-nil, zero value otherwise.

### GetOperatorIdOk

`func (o *StatJobsCreateRequest) GetOperatorIdOk() (*string, bool)`

GetOperatorIdOk returns a tuple with the OperatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatorId

`func (o *StatJobsCreateRequest) SetOperatorId(v string)`

SetOperatorId sets OperatorId field to given value.

### HasOperatorId

`func (o *StatJobsCreateRequest) HasOperatorId() bool`

HasOperatorId returns a boolean if a field has been set.

### GetStatus

`func (o *StatJobsCreateRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *StatJobsCreateRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *StatJobsCreateRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *StatJobsCreateRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSlClicks

`func (o *StatJobsCreateRequest) GetSlClicks() string`

GetSlClicks returns the SlClicks field if non-nil, zero value otherwise.

### GetSlClicksOk

`func (o *StatJobsCreateRequest) GetSlClicksOk() (*string, bool)`

GetSlClicksOk returns a tuple with the SlClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlClicks

`func (o *StatJobsCreateRequest) SetSlClicks(v string)`

SetSlClicks sets SlClicks field to given value.

### HasSlClicks

`func (o *StatJobsCreateRequest) HasSlClicks() bool`

HasSlClicks returns a boolean if a field has been set.

### GetSlClicksComp

`func (o *StatJobsCreateRequest) GetSlClicksComp() string`

GetSlClicksComp returns the SlClicksComp field if non-nil, zero value otherwise.

### GetSlClicksCompOk

`func (o *StatJobsCreateRequest) GetSlClicksCompOk() (*string, bool)`

GetSlClicksCompOk returns a tuple with the SlClicksComp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlClicksComp

`func (o *StatJobsCreateRequest) SetSlClicksComp(v string)`

SetSlClicksComp sets SlClicksComp field to given value.

### HasSlClicksComp

`func (o *StatJobsCreateRequest) HasSlClicksComp() bool`

HasSlClicksComp returns a boolean if a field has been set.

### GetSlClicksCount

`func (o *StatJobsCreateRequest) GetSlClicksCount() string`

GetSlClicksCount returns the SlClicksCount field if non-nil, zero value otherwise.

### GetSlClicksCountOk

`func (o *StatJobsCreateRequest) GetSlClicksCountOk() (*string, bool)`

GetSlClicksCountOk returns a tuple with the SlClicksCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlClicksCount

`func (o *StatJobsCreateRequest) SetSlClicksCount(v string)`

SetSlClicksCount sets SlClicksCount field to given value.

### HasSlClicksCount

`func (o *StatJobsCreateRequest) HasSlClicksCount() bool`

HasSlClicksCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


