# MetaPage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | Pointer to **int32** | Total items count at all of the pages | [optional] 
**Limit** | Pointer to **int32** | Limit items at one page | [optional] 
**Offset** | Pointer to **int32** | Get items starting at offset | [optional] [default to 0]

## Methods

### NewMetaPage

`func NewMetaPage() *MetaPage`

NewMetaPage instantiates a new MetaPage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMetaPageWithDefaults

`func NewMetaPageWithDefaults() *MetaPage`

NewMetaPageWithDefaults instantiates a new MetaPage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *MetaPage) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *MetaPage) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *MetaPage) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *MetaPage) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetLimit

`func (o *MetaPage) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *MetaPage) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *MetaPage) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *MetaPage) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetOffset

`func (o *MetaPage) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *MetaPage) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *MetaPage) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *MetaPage) HasOffset() bool`

HasOffset returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


