# GetMessages200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]MessageApiSchema**](MessageApiSchema.md) |  | [optional] 
**Meta** | Pointer to [**Meta**](Meta.md) |  | [optional] 

## Methods

### NewGetMessages200Response

`func NewGetMessages200Response() *GetMessages200Response`

NewGetMessages200Response instantiates a new GetMessages200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetMessages200ResponseWithDefaults

`func NewGetMessages200ResponseWithDefaults() *GetMessages200Response`

NewGetMessages200ResponseWithDefaults instantiates a new GetMessages200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetMessages200Response) GetData() []MessageApiSchema`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetMessages200Response) GetDataOk() (*[]MessageApiSchema, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetMessages200Response) SetData(v []MessageApiSchema)`

SetData sets Data field to given value.

### HasData

`func (o *GetMessages200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetMeta

`func (o *GetMessages200Response) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetMessages200Response) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetMessages200Response) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetMessages200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


