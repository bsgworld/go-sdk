# CreateJobMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Job creation type | 
**MessageId** | **[]int32** | Message Ids | 

## Methods

### NewCreateJobMessage

`func NewCreateJobMessage(type_ string, messageId []int32, ) *CreateJobMessage`

NewCreateJobMessage instantiates a new CreateJobMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateJobMessageWithDefaults

`func NewCreateJobMessageWithDefaults() *CreateJobMessage`

NewCreateJobMessageWithDefaults instantiates a new CreateJobMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CreateJobMessage) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateJobMessage) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateJobMessage) SetType(v string)`

SetType sets Type field to given value.


### GetMessageId

`func (o *CreateJobMessage) GetMessageId() []int32`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *CreateJobMessage) GetMessageIdOk() (*[]int32, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *CreateJobMessage) SetMessageId(v []int32)`

SetMessageId sets MessageId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


