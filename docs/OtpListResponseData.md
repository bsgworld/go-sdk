# OtpListResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**List** | Pointer to [**[]TwoFactorAuthenticationMessagesResource**](TwoFactorAuthenticationMessagesResource.md) |  | [optional] 
**Total** | Pointer to **int32** | The total number of authentications. | [optional] 

## Methods

### NewOtpListResponseData

`func NewOtpListResponseData() *OtpListResponseData`

NewOtpListResponseData instantiates a new OtpListResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOtpListResponseDataWithDefaults

`func NewOtpListResponseDataWithDefaults() *OtpListResponseData`

NewOtpListResponseDataWithDefaults instantiates a new OtpListResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetList

`func (o *OtpListResponseData) GetList() []TwoFactorAuthenticationMessagesResource`

GetList returns the List field if non-nil, zero value otherwise.

### GetListOk

`func (o *OtpListResponseData) GetListOk() (*[]TwoFactorAuthenticationMessagesResource, bool)`

GetListOk returns a tuple with the List field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetList

`func (o *OtpListResponseData) SetList(v []TwoFactorAuthenticationMessagesResource)`

SetList sets List field to given value.

### HasList

`func (o *OtpListResponseData) HasList() bool`

HasList returns a boolean if a field has been set.

### GetTotal

`func (o *OtpListResponseData) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *OtpListResponseData) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *OtpListResponseData) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *OtpListResponseData) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


