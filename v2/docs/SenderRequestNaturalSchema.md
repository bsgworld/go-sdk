# SenderRequestNaturalSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Number of the application for Sender registration | [optional] 
**Name** | Pointer to **string** | Last name, first name, and middle name | [optional] 
**Status** | Pointer to [**SenderRequestStatus**](SenderRequestStatus.md) |  | [optional] 
**Type** | Pointer to [**SenderRequestType**](SenderRequestType.md) |  | [optional] [default to SMS]
**CreatedAt** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 
**CountryCode** | Pointer to **string** | Country code according to ISO 3166-1 alpha-2 standard | [optional] 
**Sender** | Pointer to **string** | Sender name.   Up to 11 Latin letters or digits, up to 15 – only digits. To setup senders visit the [account](https://app.bsg.world/sms/senders) or use [sender api](#tag/Senders) | [optional] 
**CodeOfCompany** | Pointer to **string** | National registration code of Company (ЄДРПОУ for Ukraine) | [optional] 
**SiteUrl** | Pointer to **string** | Website URL of your service | [optional] 
**InformingPurpose** | Pointer to **string** | Purpose of informing | [optional] 
**Comment** | Pointer to **NullableString** | any additional information | [optional] 
**Description** | Pointer to **string** | Service description | [optional] 

## Methods

### NewSenderRequestNaturalSchema

`func NewSenderRequestNaturalSchema() *SenderRequestNaturalSchema`

NewSenderRequestNaturalSchema instantiates a new SenderRequestNaturalSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenderRequestNaturalSchemaWithDefaults

`func NewSenderRequestNaturalSchemaWithDefaults() *SenderRequestNaturalSchema`

NewSenderRequestNaturalSchemaWithDefaults instantiates a new SenderRequestNaturalSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SenderRequestNaturalSchema) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SenderRequestNaturalSchema) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SenderRequestNaturalSchema) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *SenderRequestNaturalSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *SenderRequestNaturalSchema) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SenderRequestNaturalSchema) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SenderRequestNaturalSchema) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SenderRequestNaturalSchema) HasName() bool`

HasName returns a boolean if a field has been set.

### GetStatus

`func (o *SenderRequestNaturalSchema) GetStatus() SenderRequestStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SenderRequestNaturalSchema) GetStatusOk() (*SenderRequestStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SenderRequestNaturalSchema) SetStatus(v SenderRequestStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SenderRequestNaturalSchema) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *SenderRequestNaturalSchema) GetType() SenderRequestType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SenderRequestNaturalSchema) GetTypeOk() (*SenderRequestType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SenderRequestNaturalSchema) SetType(v SenderRequestType)`

SetType sets Type field to given value.

### HasType

`func (o *SenderRequestNaturalSchema) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCreatedAt

`func (o *SenderRequestNaturalSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SenderRequestNaturalSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SenderRequestNaturalSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *SenderRequestNaturalSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetCountryCode

`func (o *SenderRequestNaturalSchema) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *SenderRequestNaturalSchema) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *SenderRequestNaturalSchema) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *SenderRequestNaturalSchema) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetSender

`func (o *SenderRequestNaturalSchema) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SenderRequestNaturalSchema) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SenderRequestNaturalSchema) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *SenderRequestNaturalSchema) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetCodeOfCompany

`func (o *SenderRequestNaturalSchema) GetCodeOfCompany() string`

GetCodeOfCompany returns the CodeOfCompany field if non-nil, zero value otherwise.

### GetCodeOfCompanyOk

`func (o *SenderRequestNaturalSchema) GetCodeOfCompanyOk() (*string, bool)`

GetCodeOfCompanyOk returns a tuple with the CodeOfCompany field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeOfCompany

`func (o *SenderRequestNaturalSchema) SetCodeOfCompany(v string)`

SetCodeOfCompany sets CodeOfCompany field to given value.

### HasCodeOfCompany

`func (o *SenderRequestNaturalSchema) HasCodeOfCompany() bool`

HasCodeOfCompany returns a boolean if a field has been set.

### GetSiteUrl

`func (o *SenderRequestNaturalSchema) GetSiteUrl() string`

GetSiteUrl returns the SiteUrl field if non-nil, zero value otherwise.

### GetSiteUrlOk

`func (o *SenderRequestNaturalSchema) GetSiteUrlOk() (*string, bool)`

GetSiteUrlOk returns a tuple with the SiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteUrl

`func (o *SenderRequestNaturalSchema) SetSiteUrl(v string)`

SetSiteUrl sets SiteUrl field to given value.

### HasSiteUrl

`func (o *SenderRequestNaturalSchema) HasSiteUrl() bool`

HasSiteUrl returns a boolean if a field has been set.

### GetInformingPurpose

`func (o *SenderRequestNaturalSchema) GetInformingPurpose() string`

GetInformingPurpose returns the InformingPurpose field if non-nil, zero value otherwise.

### GetInformingPurposeOk

`func (o *SenderRequestNaturalSchema) GetInformingPurposeOk() (*string, bool)`

GetInformingPurposeOk returns a tuple with the InformingPurpose field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInformingPurpose

`func (o *SenderRequestNaturalSchema) SetInformingPurpose(v string)`

SetInformingPurpose sets InformingPurpose field to given value.

### HasInformingPurpose

`func (o *SenderRequestNaturalSchema) HasInformingPurpose() bool`

HasInformingPurpose returns a boolean if a field has been set.

### GetComment

`func (o *SenderRequestNaturalSchema) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *SenderRequestNaturalSchema) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *SenderRequestNaturalSchema) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *SenderRequestNaturalSchema) HasComment() bool`

HasComment returns a boolean if a field has been set.

### SetCommentNil

`func (o *SenderRequestNaturalSchema) SetCommentNil(b bool)`

 SetCommentNil sets the value for Comment to be an explicit nil

### UnsetComment
`func (o *SenderRequestNaturalSchema) UnsetComment()`

UnsetComment ensures that no value is present for Comment, not even an explicit nil
### GetDescription

`func (o *SenderRequestNaturalSchema) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SenderRequestNaturalSchema) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SenderRequestNaturalSchema) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SenderRequestNaturalSchema) HasDescription() bool`

HasDescription returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


