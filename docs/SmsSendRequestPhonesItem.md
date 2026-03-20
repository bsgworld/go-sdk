# SmsSendRequestPhonesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Number** | **int32** | Phone number without leading plus, just digits | 
**ReferenceId** | Pointer to **string** | external unique ID. String up to 32 characters containing only alpha numeric characters.  **Please note:** messages with duplicate reference_id will be rejected | [optional] 

## Methods

### NewSmsSendRequestPhonesItem

`func NewSmsSendRequestPhonesItem(number int32, ) *SmsSendRequestPhonesItem`

NewSmsSendRequestPhonesItem instantiates a new SmsSendRequestPhonesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsSendRequestPhonesItemWithDefaults

`func NewSmsSendRequestPhonesItemWithDefaults() *SmsSendRequestPhonesItem`

NewSmsSendRequestPhonesItemWithDefaults instantiates a new SmsSendRequestPhonesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNumber

`func (o *SmsSendRequestPhonesItem) GetNumber() int32`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *SmsSendRequestPhonesItem) GetNumberOk() (*int32, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *SmsSendRequestPhonesItem) SetNumber(v int32)`

SetNumber sets Number field to given value.


### GetReferenceId

`func (o *SmsSendRequestPhonesItem) GetReferenceId() string`

GetReferenceId returns the ReferenceId field if non-nil, zero value otherwise.

### GetReferenceIdOk

`func (o *SmsSendRequestPhonesItem) GetReferenceIdOk() (*string, bool)`

GetReferenceIdOk returns a tuple with the ReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceId

`func (o *SmsSendRequestPhonesItem) SetReferenceId(v string)`

SetReferenceId sets ReferenceId field to given value.

### HasReferenceId

`func (o *SmsSendRequestPhonesItem) HasReferenceId() bool`

HasReferenceId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


