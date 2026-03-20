# SenderRequestLegalRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CountryCode** | **string** | Country code according to ISO 3166-1 alpha-2 standard | 
**Type** | [**SenderRequestType**](SenderRequestType.md) |  | [default to SMS]
**Sender** | **string** | Sender name.   Up to 11 Latin letters or digits, up to 15 – only digits. To setup senders visit the [account](https://app.bsg.world/sms/senders) or use [sender api](#tag/Senders) | 
**CodeOfCompany** | **string** | National registration code of Company (ЄДРПОУ for Ukraine) | 
**TaxNumber** | **string** | Taxpayer number | 
**Description** | **string** | Service description | 
**InformingPurpose** | **string** | Purpose of informing | 
**SiteUrl** | Pointer to **string** | Website URL of your service | [optional] 
**Comment** | Pointer to **NullableString** | any additional information | [optional] 
**LegalName** | Pointer to **string** | Legal entity name | [optional] 
**Address** | Pointer to **string** | Legal Address | [optional] 

## Methods

### NewSenderRequestLegalRequest

`func NewSenderRequestLegalRequest(countryCode string, type_ SenderRequestType, sender string, codeOfCompany string, taxNumber string, description string, informingPurpose string, ) *SenderRequestLegalRequest`

NewSenderRequestLegalRequest instantiates a new SenderRequestLegalRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenderRequestLegalRequestWithDefaults

`func NewSenderRequestLegalRequestWithDefaults() *SenderRequestLegalRequest`

NewSenderRequestLegalRequestWithDefaults instantiates a new SenderRequestLegalRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCountryCode

`func (o *SenderRequestLegalRequest) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *SenderRequestLegalRequest) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *SenderRequestLegalRequest) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetType

`func (o *SenderRequestLegalRequest) GetType() SenderRequestType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SenderRequestLegalRequest) GetTypeOk() (*SenderRequestType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SenderRequestLegalRequest) SetType(v SenderRequestType)`

SetType sets Type field to given value.


### GetSender

`func (o *SenderRequestLegalRequest) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SenderRequestLegalRequest) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SenderRequestLegalRequest) SetSender(v string)`

SetSender sets Sender field to given value.


### GetCodeOfCompany

`func (o *SenderRequestLegalRequest) GetCodeOfCompany() string`

GetCodeOfCompany returns the CodeOfCompany field if non-nil, zero value otherwise.

### GetCodeOfCompanyOk

`func (o *SenderRequestLegalRequest) GetCodeOfCompanyOk() (*string, bool)`

GetCodeOfCompanyOk returns a tuple with the CodeOfCompany field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeOfCompany

`func (o *SenderRequestLegalRequest) SetCodeOfCompany(v string)`

SetCodeOfCompany sets CodeOfCompany field to given value.


### GetTaxNumber

`func (o *SenderRequestLegalRequest) GetTaxNumber() string`

GetTaxNumber returns the TaxNumber field if non-nil, zero value otherwise.

### GetTaxNumberOk

`func (o *SenderRequestLegalRequest) GetTaxNumberOk() (*string, bool)`

GetTaxNumberOk returns a tuple with the TaxNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxNumber

`func (o *SenderRequestLegalRequest) SetTaxNumber(v string)`

SetTaxNumber sets TaxNumber field to given value.


### GetDescription

`func (o *SenderRequestLegalRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SenderRequestLegalRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SenderRequestLegalRequest) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetInformingPurpose

`func (o *SenderRequestLegalRequest) GetInformingPurpose() string`

GetInformingPurpose returns the InformingPurpose field if non-nil, zero value otherwise.

### GetInformingPurposeOk

`func (o *SenderRequestLegalRequest) GetInformingPurposeOk() (*string, bool)`

GetInformingPurposeOk returns a tuple with the InformingPurpose field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInformingPurpose

`func (o *SenderRequestLegalRequest) SetInformingPurpose(v string)`

SetInformingPurpose sets InformingPurpose field to given value.


### GetSiteUrl

`func (o *SenderRequestLegalRequest) GetSiteUrl() string`

GetSiteUrl returns the SiteUrl field if non-nil, zero value otherwise.

### GetSiteUrlOk

`func (o *SenderRequestLegalRequest) GetSiteUrlOk() (*string, bool)`

GetSiteUrlOk returns a tuple with the SiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteUrl

`func (o *SenderRequestLegalRequest) SetSiteUrl(v string)`

SetSiteUrl sets SiteUrl field to given value.

### HasSiteUrl

`func (o *SenderRequestLegalRequest) HasSiteUrl() bool`

HasSiteUrl returns a boolean if a field has been set.

### GetComment

`func (o *SenderRequestLegalRequest) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *SenderRequestLegalRequest) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *SenderRequestLegalRequest) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *SenderRequestLegalRequest) HasComment() bool`

HasComment returns a boolean if a field has been set.

### SetCommentNil

`func (o *SenderRequestLegalRequest) SetCommentNil(b bool)`

 SetCommentNil sets the value for Comment to be an explicit nil

### UnsetComment
`func (o *SenderRequestLegalRequest) UnsetComment()`

UnsetComment ensures that no value is present for Comment, not even an explicit nil
### GetLegalName

`func (o *SenderRequestLegalRequest) GetLegalName() string`

GetLegalName returns the LegalName field if non-nil, zero value otherwise.

### GetLegalNameOk

`func (o *SenderRequestLegalRequest) GetLegalNameOk() (*string, bool)`

GetLegalNameOk returns a tuple with the LegalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalName

`func (o *SenderRequestLegalRequest) SetLegalName(v string)`

SetLegalName sets LegalName field to given value.

### HasLegalName

`func (o *SenderRequestLegalRequest) HasLegalName() bool`

HasLegalName returns a boolean if a field has been set.

### GetAddress

`func (o *SenderRequestLegalRequest) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *SenderRequestLegalRequest) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *SenderRequestLegalRequest) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *SenderRequestLegalRequest) HasAddress() bool`

HasAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


