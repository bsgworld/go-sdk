# MessageApiSchemaAlternativeChannels

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sms** | Pointer to [**MessageApiSchemaAlternativeChannelsSmsDetails**](MessageApiSchemaAlternativeChannelsSmsDetails.md) |  | [optional] 
**Viber** | Pointer to [**MessageApiSchemaAlternativeChannelsViberDetails**](MessageApiSchemaAlternativeChannelsViberDetails.md) |  | [optional] 

## Methods

### NewMessageApiSchemaAlternativeChannels

`func NewMessageApiSchemaAlternativeChannels() *MessageApiSchemaAlternativeChannels`

NewMessageApiSchemaAlternativeChannels instantiates a new MessageApiSchemaAlternativeChannels object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageApiSchemaAlternativeChannelsWithDefaults

`func NewMessageApiSchemaAlternativeChannelsWithDefaults() *MessageApiSchemaAlternativeChannels`

NewMessageApiSchemaAlternativeChannelsWithDefaults instantiates a new MessageApiSchemaAlternativeChannels object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSms

`func (o *MessageApiSchemaAlternativeChannels) GetSms() MessageApiSchemaAlternativeChannelsSmsDetails`

GetSms returns the Sms field if non-nil, zero value otherwise.

### GetSmsOk

`func (o *MessageApiSchemaAlternativeChannels) GetSmsOk() (*MessageApiSchemaAlternativeChannelsSmsDetails, bool)`

GetSmsOk returns a tuple with the Sms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSms

`func (o *MessageApiSchemaAlternativeChannels) SetSms(v MessageApiSchemaAlternativeChannelsSmsDetails)`

SetSms sets Sms field to given value.

### HasSms

`func (o *MessageApiSchemaAlternativeChannels) HasSms() bool`

HasSms returns a boolean if a field has been set.

### GetViber

`func (o *MessageApiSchemaAlternativeChannels) GetViber() MessageApiSchemaAlternativeChannelsViberDetails`

GetViber returns the Viber field if non-nil, zero value otherwise.

### GetViberOk

`func (o *MessageApiSchemaAlternativeChannels) GetViberOk() (*MessageApiSchemaAlternativeChannelsViberDetails, bool)`

GetViberOk returns a tuple with the Viber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViber

`func (o *MessageApiSchemaAlternativeChannels) SetViber(v MessageApiSchemaAlternativeChannelsViberDetails)`

SetViber sets Viber field to given value.

### HasViber

`func (o *MessageApiSchemaAlternativeChannels) HasViber() bool`

HasViber returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


