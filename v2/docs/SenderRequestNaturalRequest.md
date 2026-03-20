# SenderRequestNaturalRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CountryCode** | **string** | Country code according to ISO 3166-1 alpha-2 standard | 
**Type** | [**SenderRequestType**](SenderRequestType.md) |  | [default to SMS]
**Sender** | **string** | Sender name.   Up to 11 Latin letters or digits, up to 15 – only digits. To setup senders visit the [account](https://app.bsg.world/sms/senders) or use [sender api](#tag/Senders) | 
**Name** | **string** | Last name, first name, and middle name | 
**CodeOfCompany** | **string** | National registration code of Company (ЄДРПОУ for Ukraine) | 
**Description** | **string** | Service description | 
**InformingPurpose** | **string** | Purpose of informing | 
**SiteUrl** | Pointer to **string** | Website URL of your service | [optional] 
**Comment** | Pointer to **NullableString** | any additional information | [optional] 

## Methods

### NewSenderRequestNaturalRequest

`func NewSenderRequestNaturalRequest(countryCode string, type_ SenderRequestType, sender string, name string, codeOfCompany string, description string, informingPurpose string, ) *SenderRequestNaturalRequest`

NewSenderRequestNaturalRequest instantiates a new SenderRequestNaturalRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenderRequestNaturalRequestWithDefaults

`func NewSenderRequestNaturalRequestWithDefaults() *SenderRequestNaturalRequest`

NewSenderRequestNaturalRequestWithDefaults instantiates a new SenderRequestNaturalRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCountryCode

`func (o *SenderRequestNaturalRequest) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *SenderRequestNaturalRequest) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *SenderRequestNaturalRequest) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetType

`func (o *SenderRequestNaturalRequest) GetType() SenderRequestType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SenderRequestNaturalRequest) GetTypeOk() (*SenderRequestType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SenderRequestNaturalRequest) SetType(v SenderRequestType)`

SetType sets Type field to given value.


### GetSender

`func (o *SenderRequestNaturalRequest) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SenderRequestNaturalRequest) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SenderRequestNaturalRequest) SetSender(v string)`

SetSender sets Sender field to given value.


### GetName

`func (o *SenderRequestNaturalRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SenderRequestNaturalRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SenderRequestNaturalRequest) SetName(v string)`

SetName sets Name field to given value.


### GetCodeOfCompany

`func (o *SenderRequestNaturalRequest) GetCodeOfCompany() string`

GetCodeOfCompany returns the CodeOfCompany field if non-nil, zero value otherwise.

### GetCodeOfCompanyOk

`func (o *SenderRequestNaturalRequest) GetCodeOfCompanyOk() (*string, bool)`

GetCodeOfCompanyOk returns a tuple with the CodeOfCompany field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeOfCompany

`func (o *SenderRequestNaturalRequest) SetCodeOfCompany(v string)`

SetCodeOfCompany sets CodeOfCompany field to given value.


### GetDescription

`func (o *SenderRequestNaturalRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SenderRequestNaturalRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SenderRequestNaturalRequest) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetInformingPurpose

`func (o *SenderRequestNaturalRequest) GetInformingPurpose() string`

GetInformingPurpose returns the InformingPurpose field if non-nil, zero value otherwise.

### GetInformingPurposeOk

`func (o *SenderRequestNaturalRequest) GetInformingPurposeOk() (*string, bool)`

GetInformingPurposeOk returns a tuple with the InformingPurpose field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInformingPurpose

`func (o *SenderRequestNaturalRequest) SetInformingPurpose(v string)`

SetInformingPurpose sets InformingPurpose field to given value.


### GetSiteUrl

`func (o *SenderRequestNaturalRequest) GetSiteUrl() string`

GetSiteUrl returns the SiteUrl field if non-nil, zero value otherwise.

### GetSiteUrlOk

`func (o *SenderRequestNaturalRequest) GetSiteUrlOk() (*string, bool)`

GetSiteUrlOk returns a tuple with the SiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteUrl

`func (o *SenderRequestNaturalRequest) SetSiteUrl(v string)`

SetSiteUrl sets SiteUrl field to given value.

### HasSiteUrl

`func (o *SenderRequestNaturalRequest) HasSiteUrl() bool`

HasSiteUrl returns a boolean if a field has been set.

### GetComment

`func (o *SenderRequestNaturalRequest) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *SenderRequestNaturalRequest) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *SenderRequestNaturalRequest) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *SenderRequestNaturalRequest) HasComment() bool`

HasComment returns a boolean if a field has been set.

### SetCommentNil

`func (o *SenderRequestNaturalRequest) SetCommentNil(b bool)`

 SetCommentNil sets the value for Comment to be an explicit nil

### UnsetComment
`func (o *SenderRequestNaturalRequest) UnsetComment()`

UnsetComment ensures that no value is present for Comment, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


