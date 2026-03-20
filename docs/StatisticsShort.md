# StatisticsShort

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Delivered** | Pointer to **int32** | messages that already delivered | [optional] 
**Sent** | Pointer to **int32** | messages that already sent | [optional] 

## Methods

### NewStatisticsShort

`func NewStatisticsShort() *StatisticsShort`

NewStatisticsShort instantiates a new StatisticsShort object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStatisticsShortWithDefaults

`func NewStatisticsShortWithDefaults() *StatisticsShort`

NewStatisticsShortWithDefaults instantiates a new StatisticsShort object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDelivered

`func (o *StatisticsShort) GetDelivered() int32`

GetDelivered returns the Delivered field if non-nil, zero value otherwise.

### GetDeliveredOk

`func (o *StatisticsShort) GetDeliveredOk() (*int32, bool)`

GetDeliveredOk returns a tuple with the Delivered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivered

`func (o *StatisticsShort) SetDelivered(v int32)`

SetDelivered sets Delivered field to given value.

### HasDelivered

`func (o *StatisticsShort) HasDelivered() bool`

HasDelivered returns a boolean if a field has been set.

### GetSent

`func (o *StatisticsShort) GetSent() int32`

GetSent returns the Sent field if non-nil, zero value otherwise.

### GetSentOk

`func (o *StatisticsShort) GetSentOk() (*int32, bool)`

GetSentOk returns a tuple with the Sent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSent

`func (o *StatisticsShort) SetSent(v int32)`

SetSent sets Sent field to given value.

### HasSent

`func (o *StatisticsShort) HasSent() bool`

HasSent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


