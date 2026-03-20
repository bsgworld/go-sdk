# SenderRequestLegalSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Number of the application for Sender registration | [optional] 
**Sender** | Pointer to **string** | Sender name.   Up to 11 Latin letters or digits, up to 15 – only digits. To setup senders visit the [account](https://app.bsg.world/sms/senders) or use [sender api](#tag/Senders) | [optional] 
**LegalName** | Pointer to **string** | Legal entity name | [optional] 
**Address** | Pointer to **string** | Legal Address | [optional] 
**Status** | Pointer to [**SenderRequestStatus**](SenderRequestStatus.md) |  | [optional] 
**Type** | Pointer to [**SenderRequestType**](SenderRequestType.md) |  | [optional] [default to SMS]
**CreatedAt** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 
**CountryCode** | Pointer to **string** | Country code according to ISO 3166-1 alpha-2 standard | [optional] 
**CodeOfCompany** | Pointer to **string** | National registration code of Company (ЄДРПОУ for Ukraine) | [optional] 
**TaxNumber** | Pointer to **string** | Taxpayer number | [optional] 
**SiteUrl** | Pointer to **string** | Website URL of your service | [optional] 
**InformingPurpose** | Pointer to **string** | Purpose of informing | [optional] 
**Comment** | Pointer to **NullableString** | any additional information | [optional] 
**Description** | Pointer to **string** | Service description | [optional] 

## Methods

### NewSenderRequestLegalSchema

`func NewSenderRequestLegalSchema() *SenderRequestLegalSchema`

NewSenderRequestLegalSchema instantiates a new SenderRequestLegalSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenderRequestLegalSchemaWithDefaults

`func NewSenderRequestLegalSchemaWithDefaults() *SenderRequestLegalSchema`

NewSenderRequestLegalSchemaWithDefaults instantiates a new SenderRequestLegalSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SenderRequestLegalSchema) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SenderRequestLegalSchema) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SenderRequestLegalSchema) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *SenderRequestLegalSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSender

`func (o *SenderRequestLegalSchema) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SenderRequestLegalSchema) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SenderRequestLegalSchema) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *SenderRequestLegalSchema) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetLegalName

`func (o *SenderRequestLegalSchema) GetLegalName() string`

GetLegalName returns the LegalName field if non-nil, zero value otherwise.

### GetLegalNameOk

`func (o *SenderRequestLegalSchema) GetLegalNameOk() (*string, bool)`

GetLegalNameOk returns a tuple with the LegalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalName

`func (o *SenderRequestLegalSchema) SetLegalName(v string)`

SetLegalName sets LegalName field to given value.

### HasLegalName

`func (o *SenderRequestLegalSchema) HasLegalName() bool`

HasLegalName returns a boolean if a field has been set.

### GetAddress

`func (o *SenderRequestLegalSchema) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *SenderRequestLegalSchema) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *SenderRequestLegalSchema) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *SenderRequestLegalSchema) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetStatus

`func (o *SenderRequestLegalSchema) GetStatus() SenderRequestStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SenderRequestLegalSchema) GetStatusOk() (*SenderRequestStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SenderRequestLegalSchema) SetStatus(v SenderRequestStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SenderRequestLegalSchema) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *SenderRequestLegalSchema) GetType() SenderRequestType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SenderRequestLegalSchema) GetTypeOk() (*SenderRequestType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SenderRequestLegalSchema) SetType(v SenderRequestType)`

SetType sets Type field to given value.

### HasType

`func (o *SenderRequestLegalSchema) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCreatedAt

`func (o *SenderRequestLegalSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SenderRequestLegalSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SenderRequestLegalSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *SenderRequestLegalSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetCountryCode

`func (o *SenderRequestLegalSchema) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *SenderRequestLegalSchema) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *SenderRequestLegalSchema) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *SenderRequestLegalSchema) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetCodeOfCompany

`func (o *SenderRequestLegalSchema) GetCodeOfCompany() string`

GetCodeOfCompany returns the CodeOfCompany field if non-nil, zero value otherwise.

### GetCodeOfCompanyOk

`func (o *SenderRequestLegalSchema) GetCodeOfCompanyOk() (*string, bool)`

GetCodeOfCompanyOk returns a tuple with the CodeOfCompany field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeOfCompany

`func (o *SenderRequestLegalSchema) SetCodeOfCompany(v string)`

SetCodeOfCompany sets CodeOfCompany field to given value.

### HasCodeOfCompany

`func (o *SenderRequestLegalSchema) HasCodeOfCompany() bool`

HasCodeOfCompany returns a boolean if a field has been set.

### GetTaxNumber

`func (o *SenderRequestLegalSchema) GetTaxNumber() string`

GetTaxNumber returns the TaxNumber field if non-nil, zero value otherwise.

### GetTaxNumberOk

`func (o *SenderRequestLegalSchema) GetTaxNumberOk() (*string, bool)`

GetTaxNumberOk returns a tuple with the TaxNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxNumber

`func (o *SenderRequestLegalSchema) SetTaxNumber(v string)`

SetTaxNumber sets TaxNumber field to given value.

### HasTaxNumber

`func (o *SenderRequestLegalSchema) HasTaxNumber() bool`

HasTaxNumber returns a boolean if a field has been set.

### GetSiteUrl

`func (o *SenderRequestLegalSchema) GetSiteUrl() string`

GetSiteUrl returns the SiteUrl field if non-nil, zero value otherwise.

### GetSiteUrlOk

`func (o *SenderRequestLegalSchema) GetSiteUrlOk() (*string, bool)`

GetSiteUrlOk returns a tuple with the SiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteUrl

`func (o *SenderRequestLegalSchema) SetSiteUrl(v string)`

SetSiteUrl sets SiteUrl field to given value.

### HasSiteUrl

`func (o *SenderRequestLegalSchema) HasSiteUrl() bool`

HasSiteUrl returns a boolean if a field has been set.

### GetInformingPurpose

`func (o *SenderRequestLegalSchema) GetInformingPurpose() string`

GetInformingPurpose returns the InformingPurpose field if non-nil, zero value otherwise.

### GetInformingPurposeOk

`func (o *SenderRequestLegalSchema) GetInformingPurposeOk() (*string, bool)`

GetInformingPurposeOk returns a tuple with the InformingPurpose field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInformingPurpose

`func (o *SenderRequestLegalSchema) SetInformingPurpose(v string)`

SetInformingPurpose sets InformingPurpose field to given value.

### HasInformingPurpose

`func (o *SenderRequestLegalSchema) HasInformingPurpose() bool`

HasInformingPurpose returns a boolean if a field has been set.

### GetComment

`func (o *SenderRequestLegalSchema) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *SenderRequestLegalSchema) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *SenderRequestLegalSchema) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *SenderRequestLegalSchema) HasComment() bool`

HasComment returns a boolean if a field has been set.

### SetCommentNil

`func (o *SenderRequestLegalSchema) SetCommentNil(b bool)`

 SetCommentNil sets the value for Comment to be an explicit nil

### UnsetComment
`func (o *SenderRequestLegalSchema) UnsetComment()`

UnsetComment ensures that no value is present for Comment, not even an explicit nil
### GetDescription

`func (o *SenderRequestLegalSchema) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SenderRequestLegalSchema) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SenderRequestLegalSchema) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SenderRequestLegalSchema) HasDescription() bool`

HasDescription returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


