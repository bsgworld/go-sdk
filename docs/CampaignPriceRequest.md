# CampaignPriceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sender** | **string** | Sender’s name: from 3 to 11 characters for the sender’s alphanumeric name (Latin letters, symbols, numbers, spaces); 3 to 15 characters for the sender’s numeric name. To setup senders visit the [account](https://app.bsg.world/sms/senders) | 
**Text** | **string** | Message text to send | 
**TariffCode** | Pointer to **int32** | Tariff code null by default. Your can pass specified one if you have several. For more information please visit the [account prices](https://app.bsg.world/prices/sms) | [optional] 
**Groups** | Pointer to **[]int32** |  | [optional] 
**Messages** | Pointer to [**[]CampaignPriceRequestMessagesItem**](CampaignPriceRequestMessagesItem.md) |  | [optional] 

## Methods

### NewCampaignPriceRequest

`func NewCampaignPriceRequest(sender string, text string, ) *CampaignPriceRequest`

NewCampaignPriceRequest instantiates a new CampaignPriceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCampaignPriceRequestWithDefaults

`func NewCampaignPriceRequestWithDefaults() *CampaignPriceRequest`

NewCampaignPriceRequestWithDefaults instantiates a new CampaignPriceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSender

`func (o *CampaignPriceRequest) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *CampaignPriceRequest) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *CampaignPriceRequest) SetSender(v string)`

SetSender sets Sender field to given value.


### GetText

`func (o *CampaignPriceRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *CampaignPriceRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *CampaignPriceRequest) SetText(v string)`

SetText sets Text field to given value.


### GetTariffCode

`func (o *CampaignPriceRequest) GetTariffCode() int32`

GetTariffCode returns the TariffCode field if non-nil, zero value otherwise.

### GetTariffCodeOk

`func (o *CampaignPriceRequest) GetTariffCodeOk() (*int32, bool)`

GetTariffCodeOk returns a tuple with the TariffCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariffCode

`func (o *CampaignPriceRequest) SetTariffCode(v int32)`

SetTariffCode sets TariffCode field to given value.

### HasTariffCode

`func (o *CampaignPriceRequest) HasTariffCode() bool`

HasTariffCode returns a boolean if a field has been set.

### GetGroups

`func (o *CampaignPriceRequest) GetGroups() []int32`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *CampaignPriceRequest) GetGroupsOk() (*[]int32, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *CampaignPriceRequest) SetGroups(v []int32)`

SetGroups sets Groups field to given value.

### HasGroups

`func (o *CampaignPriceRequest) HasGroups() bool`

HasGroups returns a boolean if a field has been set.

### GetMessages

`func (o *CampaignPriceRequest) GetMessages() []CampaignPriceRequestMessagesItem`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *CampaignPriceRequest) GetMessagesOk() (*[]CampaignPriceRequestMessagesItem, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *CampaignPriceRequest) SetMessages(v []CampaignPriceRequestMessagesItem)`

SetMessages sets Messages field to given value.

### HasMessages

`func (o *CampaignPriceRequest) HasMessages() bool`

HasMessages returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


