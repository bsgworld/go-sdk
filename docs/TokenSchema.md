# TokenSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bearer** | Pointer to **string** | Token for authorization of API queries. | [optional] 

## Methods

### NewTokenSchema

`func NewTokenSchema() *TokenSchema`

NewTokenSchema instantiates a new TokenSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTokenSchemaWithDefaults

`func NewTokenSchemaWithDefaults() *TokenSchema`

NewTokenSchemaWithDefaults instantiates a new TokenSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBearer

`func (o *TokenSchema) GetBearer() string`

GetBearer returns the Bearer field if non-nil, zero value otherwise.

### GetBearerOk

`func (o *TokenSchema) GetBearerOk() (*string, bool)`

GetBearerOk returns a tuple with the Bearer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBearer

`func (o *TokenSchema) SetBearer(v string)`

SetBearer sets Bearer field to given value.

### HasBearer

`func (o *TokenSchema) HasBearer() bool`

HasBearer returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


