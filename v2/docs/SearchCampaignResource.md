# SearchCampaignResource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]CampaignSchema**](CampaignSchema.md) | list of campaigns | [optional] 
**Meta** | Pointer to [**Meta**](Meta.md) |  | [optional] 

## Methods

### NewSearchCampaignResource

`func NewSearchCampaignResource() *SearchCampaignResource`

NewSearchCampaignResource instantiates a new SearchCampaignResource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchCampaignResourceWithDefaults

`func NewSearchCampaignResourceWithDefaults() *SearchCampaignResource`

NewSearchCampaignResourceWithDefaults instantiates a new SearchCampaignResource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *SearchCampaignResource) GetData() []CampaignSchema`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SearchCampaignResource) GetDataOk() (*[]CampaignSchema, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SearchCampaignResource) SetData(v []CampaignSchema)`

SetData sets Data field to given value.

### HasData

`func (o *SearchCampaignResource) HasData() bool`

HasData returns a boolean if a field has been set.

### GetMeta

`func (o *SearchCampaignResource) GetMeta() Meta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *SearchCampaignResource) GetMetaOk() (*Meta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *SearchCampaignResource) SetMeta(v Meta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *SearchCampaignResource) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


