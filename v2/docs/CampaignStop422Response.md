# CampaignStop422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | Invalid campaign status  The campaign must be in one of following status to be able to stop: \&quot;scheduled\&quot;, \&quot;sending\&quot;, \&quot;paused\&quot;, \&quot;moderation\&quot; | [optional] 
**Errors** | Pointer to **[]interface{}** | errors | [optional] 

## Methods

### NewCampaignStop422Response

`func NewCampaignStop422Response() *CampaignStop422Response`

NewCampaignStop422Response instantiates a new CampaignStop422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCampaignStop422ResponseWithDefaults

`func NewCampaignStop422ResponseWithDefaults() *CampaignStop422Response`

NewCampaignStop422ResponseWithDefaults instantiates a new CampaignStop422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *CampaignStop422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CampaignStop422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CampaignStop422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *CampaignStop422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *CampaignStop422Response) GetErrors() []interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *CampaignStop422Response) GetErrorsOk() (*[]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *CampaignStop422Response) SetErrors(v []interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *CampaignStop422Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


