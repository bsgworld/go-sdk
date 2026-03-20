# OtpTemplateListResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**List** | Pointer to [**[]TwoFaTemplateResource**](TwoFaTemplateResource.md) |  | [optional] 
**Total** | Pointer to **int32** | A total number of templates that meet the search conditions. | [optional] 

## Methods

### NewOtpTemplateListResponseData

`func NewOtpTemplateListResponseData() *OtpTemplateListResponseData`

NewOtpTemplateListResponseData instantiates a new OtpTemplateListResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOtpTemplateListResponseDataWithDefaults

`func NewOtpTemplateListResponseDataWithDefaults() *OtpTemplateListResponseData`

NewOtpTemplateListResponseDataWithDefaults instantiates a new OtpTemplateListResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetList

`func (o *OtpTemplateListResponseData) GetList() []TwoFaTemplateResource`

GetList returns the List field if non-nil, zero value otherwise.

### GetListOk

`func (o *OtpTemplateListResponseData) GetListOk() (*[]TwoFaTemplateResource, bool)`

GetListOk returns a tuple with the List field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetList

`func (o *OtpTemplateListResponseData) SetList(v []TwoFaTemplateResource)`

SetList sets List field to given value.

### HasList

`func (o *OtpTemplateListResponseData) HasList() bool`

HasList returns a boolean if a field has been set.

### GetTotal

`func (o *OtpTemplateListResponseData) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OtpTemplateListResponseData) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OtpTemplateListResponseData) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *OtpTemplateListResponseData) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


