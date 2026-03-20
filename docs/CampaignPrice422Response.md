# CampaignPrice422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | The given data was invalid. It can be one of the following:  - **The given data was invalid.** Detailed error is described in errors field. - **Tariff not found**  This error can occur when the tariff identifier is specified incorrectly or the specified tariff is not present in the system. Please ensure that you are using the correct tariff identifier and try again. For more information please visit the [account prices](https://app.bsg.world/prices/sms)   | [optional] 
**Errors** | Pointer to **[]interface{}** | errors | [optional] 

## Methods

### NewCampaignPrice422Response

`func NewCampaignPrice422Response() *CampaignPrice422Response`

NewCampaignPrice422Response instantiates a new CampaignPrice422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCampaignPrice422ResponseWithDefaults

`func NewCampaignPrice422ResponseWithDefaults() *CampaignPrice422Response`

NewCampaignPrice422ResponseWithDefaults instantiates a new CampaignPrice422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *CampaignPrice422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CampaignPrice422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CampaignPrice422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *CampaignPrice422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *CampaignPrice422Response) GetErrors() []interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *CampaignPrice422Response) GetErrorsOk() (*[]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *CampaignPrice422Response) SetErrors(v []interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *CampaignPrice422Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


