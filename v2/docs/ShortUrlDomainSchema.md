# ShortUrlDomainSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique Id of short domain (uuid) | [optional] 
**SystemDomainId** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** | short domain | [optional] 
**IsDefault** | Pointer to **bool** |  | [optional] [default to true]
**SlugType** | Pointer to [**ShortDomainSlugType**](ShortDomainSlugType.md) |  | [optional] 
**InitDeletedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**NotFoundPage** | Pointer to **string** | Url to redirect if original link return status 404 not found | [optional] 
**CanRefreshStatus** | Pointer to **bool** |  | [optional] [default to true]
**CanRestore** | Pointer to **bool** |  | [optional] [default to true]
**RecordType** | Pointer to **NullableString** | if system_domain_id is null it is necessary to setup your dns | [optional] 
**Hostname** | Pointer to **NullableString** | if system_domain_id is null it is necessary to setup your dns | [optional] 
**Cname** | Pointer to **NullableString** | if system_domain_id is null it is necessary to setup your dns | [optional] 
**CountShortLinks** | Pointer to **int32** |  | [optional] 

## Methods

### NewShortUrlDomainSchema

`func NewShortUrlDomainSchema() *ShortUrlDomainSchema`

NewShortUrlDomainSchema instantiates a new ShortUrlDomainSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShortUrlDomainSchemaWithDefaults

`func NewShortUrlDomainSchemaWithDefaults() *ShortUrlDomainSchema`

NewShortUrlDomainSchemaWithDefaults instantiates a new ShortUrlDomainSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ShortUrlDomainSchema) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ShortUrlDomainSchema) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ShortUrlDomainSchema) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ShortUrlDomainSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSystemDomainId

`func (o *ShortUrlDomainSchema) GetSystemDomainId() string`

GetSystemDomainId returns the SystemDomainId field if non-nil, zero value otherwise.

### GetSystemDomainIdOk

`func (o *ShortUrlDomainSchema) GetSystemDomainIdOk() (*string, bool)`

GetSystemDomainIdOk returns a tuple with the SystemDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemDomainId

`func (o *ShortUrlDomainSchema) SetSystemDomainId(v string)`

SetSystemDomainId sets SystemDomainId field to given value.

### HasSystemDomainId

`func (o *ShortUrlDomainSchema) HasSystemDomainId() bool`

HasSystemDomainId returns a boolean if a field has been set.

### SetSystemDomainIdNil

`func (o *ShortUrlDomainSchema) SetSystemDomainIdNil(b bool)`

 SetSystemDomainIdNil sets the value for SystemDomainId to be an explicit nil

### UnsetSystemDomainId
`func (o *ShortUrlDomainSchema) UnsetSystemDomainId()`

UnsetSystemDomainId ensures that no value is present for SystemDomainId, not even an explicit nil
### GetStatus

`func (o *ShortUrlDomainSchema) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ShortUrlDomainSchema) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ShortUrlDomainSchema) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ShortUrlDomainSchema) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetName

`func (o *ShortUrlDomainSchema) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ShortUrlDomainSchema) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ShortUrlDomainSchema) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ShortUrlDomainSchema) HasName() bool`

HasName returns a boolean if a field has been set.

### GetIsDefault

`func (o *ShortUrlDomainSchema) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *ShortUrlDomainSchema) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *ShortUrlDomainSchema) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *ShortUrlDomainSchema) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.

### GetSlugType

`func (o *ShortUrlDomainSchema) GetSlugType() ShortDomainSlugType`

GetSlugType returns the SlugType field if non-nil, zero value otherwise.

### GetSlugTypeOk

`func (o *ShortUrlDomainSchema) GetSlugTypeOk() (*ShortDomainSlugType, bool)`

GetSlugTypeOk returns a tuple with the SlugType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlugType

`func (o *ShortUrlDomainSchema) SetSlugType(v ShortDomainSlugType)`

SetSlugType sets SlugType field to given value.

### HasSlugType

`func (o *ShortUrlDomainSchema) HasSlugType() bool`

HasSlugType returns a boolean if a field has been set.

### GetInitDeletedAt

`func (o *ShortUrlDomainSchema) GetInitDeletedAt() time.Time`

GetInitDeletedAt returns the InitDeletedAt field if non-nil, zero value otherwise.

### GetInitDeletedAtOk

`func (o *ShortUrlDomainSchema) GetInitDeletedAtOk() (*time.Time, bool)`

GetInitDeletedAtOk returns a tuple with the InitDeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitDeletedAt

`func (o *ShortUrlDomainSchema) SetInitDeletedAt(v time.Time)`

SetInitDeletedAt sets InitDeletedAt field to given value.

### HasInitDeletedAt

`func (o *ShortUrlDomainSchema) HasInitDeletedAt() bool`

HasInitDeletedAt returns a boolean if a field has been set.

### SetInitDeletedAtNil

`func (o *ShortUrlDomainSchema) SetInitDeletedAtNil(b bool)`

 SetInitDeletedAtNil sets the value for InitDeletedAt to be an explicit nil

### UnsetInitDeletedAt
`func (o *ShortUrlDomainSchema) UnsetInitDeletedAt()`

UnsetInitDeletedAt ensures that no value is present for InitDeletedAt, not even an explicit nil
### GetCreatedAt

`func (o *ShortUrlDomainSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ShortUrlDomainSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ShortUrlDomainSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ShortUrlDomainSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetNotFoundPage

`func (o *ShortUrlDomainSchema) GetNotFoundPage() string`

GetNotFoundPage returns the NotFoundPage field if non-nil, zero value otherwise.

### GetNotFoundPageOk

`func (o *ShortUrlDomainSchema) GetNotFoundPageOk() (*string, bool)`

GetNotFoundPageOk returns a tuple with the NotFoundPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotFoundPage

`func (o *ShortUrlDomainSchema) SetNotFoundPage(v string)`

SetNotFoundPage sets NotFoundPage field to given value.

### HasNotFoundPage

`func (o *ShortUrlDomainSchema) HasNotFoundPage() bool`

HasNotFoundPage returns a boolean if a field has been set.

### GetCanRefreshStatus

`func (o *ShortUrlDomainSchema) GetCanRefreshStatus() bool`

GetCanRefreshStatus returns the CanRefreshStatus field if non-nil, zero value otherwise.

### GetCanRefreshStatusOk

`func (o *ShortUrlDomainSchema) GetCanRefreshStatusOk() (*bool, bool)`

GetCanRefreshStatusOk returns a tuple with the CanRefreshStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanRefreshStatus

`func (o *ShortUrlDomainSchema) SetCanRefreshStatus(v bool)`

SetCanRefreshStatus sets CanRefreshStatus field to given value.

### HasCanRefreshStatus

`func (o *ShortUrlDomainSchema) HasCanRefreshStatus() bool`

HasCanRefreshStatus returns a boolean if a field has been set.

### GetCanRestore

`func (o *ShortUrlDomainSchema) GetCanRestore() bool`

GetCanRestore returns the CanRestore field if non-nil, zero value otherwise.

### GetCanRestoreOk

`func (o *ShortUrlDomainSchema) GetCanRestoreOk() (*bool, bool)`

GetCanRestoreOk returns a tuple with the CanRestore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanRestore

`func (o *ShortUrlDomainSchema) SetCanRestore(v bool)`

SetCanRestore sets CanRestore field to given value.

### HasCanRestore

`func (o *ShortUrlDomainSchema) HasCanRestore() bool`

HasCanRestore returns a boolean if a field has been set.

### GetRecordType

`func (o *ShortUrlDomainSchema) GetRecordType() string`

GetRecordType returns the RecordType field if non-nil, zero value otherwise.

### GetRecordTypeOk

`func (o *ShortUrlDomainSchema) GetRecordTypeOk() (*string, bool)`

GetRecordTypeOk returns a tuple with the RecordType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordType

`func (o *ShortUrlDomainSchema) SetRecordType(v string)`

SetRecordType sets RecordType field to given value.

### HasRecordType

`func (o *ShortUrlDomainSchema) HasRecordType() bool`

HasRecordType returns a boolean if a field has been set.

### SetRecordTypeNil

`func (o *ShortUrlDomainSchema) SetRecordTypeNil(b bool)`

 SetRecordTypeNil sets the value for RecordType to be an explicit nil

### UnsetRecordType
`func (o *ShortUrlDomainSchema) UnsetRecordType()`

UnsetRecordType ensures that no value is present for RecordType, not even an explicit nil
### GetHostname

`func (o *ShortUrlDomainSchema) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *ShortUrlDomainSchema) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *ShortUrlDomainSchema) SetHostname(v string)`

SetHostname sets Hostname field to given value.

### HasHostname

`func (o *ShortUrlDomainSchema) HasHostname() bool`

HasHostname returns a boolean if a field has been set.

### SetHostnameNil

`func (o *ShortUrlDomainSchema) SetHostnameNil(b bool)`

 SetHostnameNil sets the value for Hostname to be an explicit nil

### UnsetHostname
`func (o *ShortUrlDomainSchema) UnsetHostname()`

UnsetHostname ensures that no value is present for Hostname, not even an explicit nil
### GetCname

`func (o *ShortUrlDomainSchema) GetCname() string`

GetCname returns the Cname field if non-nil, zero value otherwise.

### GetCnameOk

`func (o *ShortUrlDomainSchema) GetCnameOk() (*string, bool)`

GetCnameOk returns a tuple with the Cname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCname

`func (o *ShortUrlDomainSchema) SetCname(v string)`

SetCname sets Cname field to given value.

### HasCname

`func (o *ShortUrlDomainSchema) HasCname() bool`

HasCname returns a boolean if a field has been set.

### SetCnameNil

`func (o *ShortUrlDomainSchema) SetCnameNil(b bool)`

 SetCnameNil sets the value for Cname to be an explicit nil

### UnsetCname
`func (o *ShortUrlDomainSchema) UnsetCname()`

UnsetCname ensures that no value is present for Cname, not even an explicit nil
### GetCountShortLinks

`func (o *ShortUrlDomainSchema) GetCountShortLinks() int32`

GetCountShortLinks returns the CountShortLinks field if non-nil, zero value otherwise.

### GetCountShortLinksOk

`func (o *ShortUrlDomainSchema) GetCountShortLinksOk() (*int32, bool)`

GetCountShortLinksOk returns a tuple with the CountShortLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountShortLinks

`func (o *ShortUrlDomainSchema) SetCountShortLinks(v int32)`

SetCountShortLinks sets CountShortLinks field to given value.

### HasCountShortLinks

`func (o *ShortUrlDomainSchema) HasCountShortLinks() bool`

HasCountShortLinks returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


