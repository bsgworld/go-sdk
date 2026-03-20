# CreateJobParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Job creation type | 
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

### NewCreateJobParams

`func NewCreateJobParams(type_ string, timeInFrom time.Time, timeInTo time.Time, ) *CreateJobParams`

NewCreateJobParams instantiates a new CreateJobParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateJobParamsWithDefaults

`func NewCreateJobParamsWithDefaults() *CreateJobParams`

NewCreateJobParamsWithDefaults instantiates a new CreateJobParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CreateJobParams) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateJobParams) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateJobParams) SetType(v string)`

SetType sets Type field to given value.


### GetTimeInFrom

`func (o *CreateJobParams) GetTimeInFrom() time.Time`

GetTimeInFrom returns the TimeInFrom field if non-nil, zero value otherwise.

### GetTimeInFromOk

`func (o *CreateJobParams) GetTimeInFromOk() (*time.Time, bool)`

GetTimeInFromOk returns a tuple with the TimeInFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeInFrom

`func (o *CreateJobParams) SetTimeInFrom(v time.Time)`

SetTimeInFrom sets TimeInFrom field to given value.


### GetTimeInTo

`func (o *CreateJobParams) GetTimeInTo() time.Time`

GetTimeInTo returns the TimeInTo field if non-nil, zero value otherwise.

### GetTimeInToOk

`func (o *CreateJobParams) GetTimeInToOk() (*time.Time, bool)`

GetTimeInToOk returns a tuple with the TimeInTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeInTo

`func (o *CreateJobParams) SetTimeInTo(v time.Time)`

SetTimeInTo sets TimeInTo field to given value.


### GetTimeSentFrom

`func (o *CreateJobParams) GetTimeSentFrom() time.Time`

GetTimeSentFrom returns the TimeSentFrom field if non-nil, zero value otherwise.

### GetTimeSentFromOk

`func (o *CreateJobParams) GetTimeSentFromOk() (*time.Time, bool)`

GetTimeSentFromOk returns a tuple with the TimeSentFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSentFrom

`func (o *CreateJobParams) SetTimeSentFrom(v time.Time)`

SetTimeSentFrom sets TimeSentFrom field to given value.

### HasTimeSentFrom

`func (o *CreateJobParams) HasTimeSentFrom() bool`

HasTimeSentFrom returns a boolean if a field has been set.

### GetTimeSentTo

`func (o *CreateJobParams) GetTimeSentTo() time.Time`

GetTimeSentTo returns the TimeSentTo field if non-nil, zero value otherwise.

### GetTimeSentToOk

`func (o *CreateJobParams) GetTimeSentToOk() (*time.Time, bool)`

GetTimeSentToOk returns a tuple with the TimeSentTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSentTo

`func (o *CreateJobParams) SetTimeSentTo(v time.Time)`

SetTimeSentTo sets TimeSentTo field to given value.

### HasTimeSentTo

`func (o *CreateJobParams) HasTimeSentTo() bool`

HasTimeSentTo returns a boolean if a field has been set.

### GetPhones

`func (o *CreateJobParams) GetPhones() []int32`

GetPhones returns the Phones field if non-nil, zero value otherwise.

### GetPhonesOk

`func (o *CreateJobParams) GetPhonesOk() (*[]int32, bool)`

GetPhonesOk returns a tuple with the Phones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhones

`func (o *CreateJobParams) SetPhones(v []int32)`

SetPhones sets Phones field to given value.

### HasPhones

`func (o *CreateJobParams) HasPhones() bool`

HasPhones returns a boolean if a field has been set.

### GetSender

`func (o *CreateJobParams) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *CreateJobParams) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *CreateJobParams) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *CreateJobParams) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetSource

`func (o *CreateJobParams) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CreateJobParams) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CreateJobParams) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *CreateJobParams) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetCountry

`func (o *CreateJobParams) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *CreateJobParams) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *CreateJobParams) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *CreateJobParams) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetOperatorId

`func (o *CreateJobParams) GetOperatorId() string`

GetOperatorId returns the OperatorId field if non-nil, zero value otherwise.

### GetOperatorIdOk

`func (o *CreateJobParams) GetOperatorIdOk() (*string, bool)`

GetOperatorIdOk returns a tuple with the OperatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperatorId

`func (o *CreateJobParams) SetOperatorId(v string)`

SetOperatorId sets OperatorId field to given value.

### HasOperatorId

`func (o *CreateJobParams) HasOperatorId() bool`

HasOperatorId returns a boolean if a field has been set.

### GetStatus

`func (o *CreateJobParams) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateJobParams) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateJobParams) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreateJobParams) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSlClicks

`func (o *CreateJobParams) GetSlClicks() string`

GetSlClicks returns the SlClicks field if non-nil, zero value otherwise.

### GetSlClicksOk

`func (o *CreateJobParams) GetSlClicksOk() (*string, bool)`

GetSlClicksOk returns a tuple with the SlClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlClicks

`func (o *CreateJobParams) SetSlClicks(v string)`

SetSlClicks sets SlClicks field to given value.

### HasSlClicks

`func (o *CreateJobParams) HasSlClicks() bool`

HasSlClicks returns a boolean if a field has been set.

### GetSlClicksComp

`func (o *CreateJobParams) GetSlClicksComp() string`

GetSlClicksComp returns the SlClicksComp field if non-nil, zero value otherwise.

### GetSlClicksCompOk

`func (o *CreateJobParams) GetSlClicksCompOk() (*string, bool)`

GetSlClicksCompOk returns a tuple with the SlClicksComp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlClicksComp

`func (o *CreateJobParams) SetSlClicksComp(v string)`

SetSlClicksComp sets SlClicksComp field to given value.

### HasSlClicksComp

`func (o *CreateJobParams) HasSlClicksComp() bool`

HasSlClicksComp returns a boolean if a field has been set.

### GetSlClicksCount

`func (o *CreateJobParams) GetSlClicksCount() string`

GetSlClicksCount returns the SlClicksCount field if non-nil, zero value otherwise.

### GetSlClicksCountOk

`func (o *CreateJobParams) GetSlClicksCountOk() (*string, bool)`

GetSlClicksCountOk returns a tuple with the SlClicksCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlClicksCount

`func (o *CreateJobParams) SetSlClicksCount(v string)`

SetSlClicksCount sets SlClicksCount field to given value.

### HasSlClicksCount

`func (o *CreateJobParams) HasSlClicksCount() bool`

HasSlClicksCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


