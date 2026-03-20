# SenderRequestSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Number of the application for Sender registration | [optional] 
**Sender** | Pointer to **string** | Sender name.   Up to 11 Latin letters or digits, up to 15 – only digits. To setup senders visit the [account](https://app.bsg.world/sms/senders) or use [sender api](#tag/Senders) | [optional] 
**Status** | Pointer to [**SenderRequestStatus**](SenderRequestStatus.md) |  | [optional] 
**CreatedAt** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 
**RegisteredAt** | Pointer to **NullableTime** | Sender registration date | [optional] 
**StatusChangedAt** | Pointer to **NullableTime** | Date and time when the status of the application for Sender registration changed. Format ISO 8601: yyyy-mm-dd hh:mm:ss | [optional] 
**CountryCode** | Pointer to **string** | Country code according to ISO 3166-1 alpha-2 standard | [optional] 
**CodeOfCompany** | Pointer to **string** | National registration code of Company (ЄДРПОУ for Ukraine) | [optional] 
**TaxNumber** | Pointer to **string** | Taxpayer number | [optional] 
**Type** | Pointer to [**SenderRequestType**](SenderRequestType.md) |  | [optional] [default to SMS]
**SiteUrl** | Pointer to **string** | Website URL of your service | [optional] 
**Name** | Pointer to **string** | Last name, first name, and middle name | [optional] 
**LegalName** | Pointer to **string** | Legal entity name | [optional] 
**Address** | Pointer to **string** | Legal Address | [optional] 
**InformingPurpose** | Pointer to **string** | Purpose of informing | [optional] 
**Comment** | Pointer to **NullableString** | any additional information | [optional] 
**RejectionReason** | Pointer to **NullableString** | Reason for rejecting the application for Sender registration. Displayed only for the “rejected” application status | [optional] 
**Description** | Pointer to **string** | Service description | [optional] 

## Methods

### NewSenderRequestSchema

`func NewSenderRequestSchema() *SenderRequestSchema`

NewSenderRequestSchema instantiates a new SenderRequestSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenderRequestSchemaWithDefaults

`func NewSenderRequestSchemaWithDefaults() *SenderRequestSchema`

NewSenderRequestSchemaWithDefaults instantiates a new SenderRequestSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SenderRequestSchema) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SenderRequestSchema) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SenderRequestSchema) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *SenderRequestSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSender

`func (o *SenderRequestSchema) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SenderRequestSchema) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SenderRequestSchema) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *SenderRequestSchema) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetStatus

`func (o *SenderRequestSchema) GetStatus() SenderRequestStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SenderRequestSchema) GetStatusOk() (*SenderRequestStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SenderRequestSchema) SetStatus(v SenderRequestStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SenderRequestSchema) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCreatedAt

`func (o *SenderRequestSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SenderRequestSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SenderRequestSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *SenderRequestSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetRegisteredAt

`func (o *SenderRequestSchema) GetRegisteredAt() time.Time`

GetRegisteredAt returns the RegisteredAt field if non-nil, zero value otherwise.

### GetRegisteredAtOk

`func (o *SenderRequestSchema) GetRegisteredAtOk() (*time.Time, bool)`

GetRegisteredAtOk returns a tuple with the RegisteredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisteredAt

`func (o *SenderRequestSchema) SetRegisteredAt(v time.Time)`

SetRegisteredAt sets RegisteredAt field to given value.

### HasRegisteredAt

`func (o *SenderRequestSchema) HasRegisteredAt() bool`

HasRegisteredAt returns a boolean if a field has been set.

### SetRegisteredAtNil

`func (o *SenderRequestSchema) SetRegisteredAtNil(b bool)`

 SetRegisteredAtNil sets the value for RegisteredAt to be an explicit nil

### UnsetRegisteredAt
`func (o *SenderRequestSchema) UnsetRegisteredAt()`

UnsetRegisteredAt ensures that no value is present for RegisteredAt, not even an explicit nil
### GetStatusChangedAt

`func (o *SenderRequestSchema) GetStatusChangedAt() time.Time`

GetStatusChangedAt returns the StatusChangedAt field if non-nil, zero value otherwise.

### GetStatusChangedAtOk

`func (o *SenderRequestSchema) GetStatusChangedAtOk() (*time.Time, bool)`

GetStatusChangedAtOk returns a tuple with the StatusChangedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusChangedAt

`func (o *SenderRequestSchema) SetStatusChangedAt(v time.Time)`

SetStatusChangedAt sets StatusChangedAt field to given value.

### HasStatusChangedAt

`func (o *SenderRequestSchema) HasStatusChangedAt() bool`

HasStatusChangedAt returns a boolean if a field has been set.

### SetStatusChangedAtNil

`func (o *SenderRequestSchema) SetStatusChangedAtNil(b bool)`

 SetStatusChangedAtNil sets the value for StatusChangedAt to be an explicit nil

### UnsetStatusChangedAt
`func (o *SenderRequestSchema) UnsetStatusChangedAt()`

UnsetStatusChangedAt ensures that no value is present for StatusChangedAt, not even an explicit nil
### GetCountryCode

`func (o *SenderRequestSchema) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *SenderRequestSchema) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *SenderRequestSchema) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *SenderRequestSchema) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetCodeOfCompany

`func (o *SenderRequestSchema) GetCodeOfCompany() string`

GetCodeOfCompany returns the CodeOfCompany field if non-nil, zero value otherwise.

### GetCodeOfCompanyOk

`func (o *SenderRequestSchema) GetCodeOfCompanyOk() (*string, bool)`

GetCodeOfCompanyOk returns a tuple with the CodeOfCompany field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeOfCompany

`func (o *SenderRequestSchema) SetCodeOfCompany(v string)`

SetCodeOfCompany sets CodeOfCompany field to given value.

### HasCodeOfCompany

`func (o *SenderRequestSchema) HasCodeOfCompany() bool`

HasCodeOfCompany returns a boolean if a field has been set.

### GetTaxNumber

`func (o *SenderRequestSchema) GetTaxNumber() string`

GetTaxNumber returns the TaxNumber field if non-nil, zero value otherwise.

### GetTaxNumberOk

`func (o *SenderRequestSchema) GetTaxNumberOk() (*string, bool)`

GetTaxNumberOk returns a tuple with the TaxNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxNumber

`func (o *SenderRequestSchema) SetTaxNumber(v string)`

SetTaxNumber sets TaxNumber field to given value.

### HasTaxNumber

`func (o *SenderRequestSchema) HasTaxNumber() bool`

HasTaxNumber returns a boolean if a field has been set.

### GetType

`func (o *SenderRequestSchema) GetType() SenderRequestType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SenderRequestSchema) GetTypeOk() (*SenderRequestType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SenderRequestSchema) SetType(v SenderRequestType)`

SetType sets Type field to given value.

### HasType

`func (o *SenderRequestSchema) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSiteUrl

`func (o *SenderRequestSchema) GetSiteUrl() string`

GetSiteUrl returns the SiteUrl field if non-nil, zero value otherwise.

### GetSiteUrlOk

`func (o *SenderRequestSchema) GetSiteUrlOk() (*string, bool)`

GetSiteUrlOk returns a tuple with the SiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSiteUrl

`func (o *SenderRequestSchema) SetSiteUrl(v string)`

SetSiteUrl sets SiteUrl field to given value.

### HasSiteUrl

`func (o *SenderRequestSchema) HasSiteUrl() bool`

HasSiteUrl returns a boolean if a field has been set.

### GetName

`func (o *SenderRequestSchema) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SenderRequestSchema) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SenderRequestSchema) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SenderRequestSchema) HasName() bool`

HasName returns a boolean if a field has been set.

### GetLegalName

`func (o *SenderRequestSchema) GetLegalName() string`

GetLegalName returns the LegalName field if non-nil, zero value otherwise.

### GetLegalNameOk

`func (o *SenderRequestSchema) GetLegalNameOk() (*string, bool)`

GetLegalNameOk returns a tuple with the LegalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalName

`func (o *SenderRequestSchema) SetLegalName(v string)`

SetLegalName sets LegalName field to given value.

### HasLegalName

`func (o *SenderRequestSchema) HasLegalName() bool`

HasLegalName returns a boolean if a field has been set.

### GetAddress

`func (o *SenderRequestSchema) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *SenderRequestSchema) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *SenderRequestSchema) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *SenderRequestSchema) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetInformingPurpose

`func (o *SenderRequestSchema) GetInformingPurpose() string`

GetInformingPurpose returns the InformingPurpose field if non-nil, zero value otherwise.

### GetInformingPurposeOk

`func (o *SenderRequestSchema) GetInformingPurposeOk() (*string, bool)`

GetInformingPurposeOk returns a tuple with the InformingPurpose field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInformingPurpose

`func (o *SenderRequestSchema) SetInformingPurpose(v string)`

SetInformingPurpose sets InformingPurpose field to given value.

### HasInformingPurpose

`func (o *SenderRequestSchema) HasInformingPurpose() bool`

HasInformingPurpose returns a boolean if a field has been set.

### GetComment

`func (o *SenderRequestSchema) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *SenderRequestSchema) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *SenderRequestSchema) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *SenderRequestSchema) HasComment() bool`

HasComment returns a boolean if a field has been set.

### SetCommentNil

`func (o *SenderRequestSchema) SetCommentNil(b bool)`

 SetCommentNil sets the value for Comment to be an explicit nil

### UnsetComment
`func (o *SenderRequestSchema) UnsetComment()`

UnsetComment ensures that no value is present for Comment, not even an explicit nil
### GetRejectionReason

`func (o *SenderRequestSchema) GetRejectionReason() string`

GetRejectionReason returns the RejectionReason field if non-nil, zero value otherwise.

### GetRejectionReasonOk

`func (o *SenderRequestSchema) GetRejectionReasonOk() (*string, bool)`

GetRejectionReasonOk returns a tuple with the RejectionReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejectionReason

`func (o *SenderRequestSchema) SetRejectionReason(v string)`

SetRejectionReason sets RejectionReason field to given value.

### HasRejectionReason

`func (o *SenderRequestSchema) HasRejectionReason() bool`

HasRejectionReason returns a boolean if a field has been set.

### SetRejectionReasonNil

`func (o *SenderRequestSchema) SetRejectionReasonNil(b bool)`

 SetRejectionReasonNil sets the value for RejectionReason to be an explicit nil

### UnsetRejectionReason
`func (o *SenderRequestSchema) UnsetRejectionReason()`

UnsetRejectionReason ensures that no value is present for RejectionReason, not even an explicit nil
### GetDescription

`func (o *SenderRequestSchema) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SenderRequestSchema) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SenderRequestSchema) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SenderRequestSchema) HasDescription() bool`

HasDescription returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


