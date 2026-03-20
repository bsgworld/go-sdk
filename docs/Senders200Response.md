# Senders200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]SenderSchema**](SenderSchema.md) |  | [optional] 
**Total** | Pointer to **int32** | Total items count at all of the pages | [optional] 

## Methods

### NewSenders200Response

`func NewSenders200Response() *Senders200Response`

NewSenders200Response instantiates a new Senders200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenders200ResponseWithDefaults

`func NewSenders200ResponseWithDefaults() *Senders200Response`

NewSenders200ResponseWithDefaults instantiates a new Senders200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *Senders200Response) GetData() []SenderSchema`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *Senders200Response) GetDataOk() (*[]SenderSchema, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *Senders200Response) SetData(v []SenderSchema)`

SetData sets Data field to given value.

### HasData

`func (o *Senders200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetTotal

`func (o *Senders200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *Senders200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *Senders200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *Senders200Response) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


