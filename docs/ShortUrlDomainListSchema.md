# ShortUrlDomainListSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**SystemDomainId** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**IsDefault** | Pointer to **bool** |  | [optional] [default to true]
**InitDeletedAt** | Pointer to **time.Time** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**CanRefreshStatus** | Pointer to **bool** |  | [optional] [default to true]
**CanRestore** | Pointer to **bool** |  | [optional] [default to true]
**CountShortLinks** | Pointer to **int32** |  | [optional] 

## Methods

### NewShortUrlDomainListSchema

`func NewShortUrlDomainListSchema() *ShortUrlDomainListSchema`

NewShortUrlDomainListSchema instantiates a new ShortUrlDomainListSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShortUrlDomainListSchemaWithDefaults

`func NewShortUrlDomainListSchemaWithDefaults() *ShortUrlDomainListSchema`

NewShortUrlDomainListSchemaWithDefaults instantiates a new ShortUrlDomainListSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ShortUrlDomainListSchema) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ShortUrlDomainListSchema) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ShortUrlDomainListSchema) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ShortUrlDomainListSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSystemDomainId

`func (o *ShortUrlDomainListSchema) GetSystemDomainId() string`

GetSystemDomainId returns the SystemDomainId field if non-nil, zero value otherwise.

### GetSystemDomainIdOk

`func (o *ShortUrlDomainListSchema) GetSystemDomainIdOk() (*string, bool)`

GetSystemDomainIdOk returns a tuple with the SystemDomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemDomainId

`func (o *ShortUrlDomainListSchema) SetSystemDomainId(v string)`

SetSystemDomainId sets SystemDomainId field to given value.

### HasSystemDomainId

`func (o *ShortUrlDomainListSchema) HasSystemDomainId() bool`

HasSystemDomainId returns a boolean if a field has been set.

### GetStatus

`func (o *ShortUrlDomainListSchema) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ShortUrlDomainListSchema) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ShortUrlDomainListSchema) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ShortUrlDomainListSchema) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetName

`func (o *ShortUrlDomainListSchema) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ShortUrlDomainListSchema) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ShortUrlDomainListSchema) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ShortUrlDomainListSchema) HasName() bool`

HasName returns a boolean if a field has been set.

### GetIsDefault

`func (o *ShortUrlDomainListSchema) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *ShortUrlDomainListSchema) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *ShortUrlDomainListSchema) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *ShortUrlDomainListSchema) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.

### GetInitDeletedAt

`func (o *ShortUrlDomainListSchema) GetInitDeletedAt() time.Time`

GetInitDeletedAt returns the InitDeletedAt field if non-nil, zero value otherwise.

### GetInitDeletedAtOk

`func (o *ShortUrlDomainListSchema) GetInitDeletedAtOk() (*time.Time, bool)`

GetInitDeletedAtOk returns a tuple with the InitDeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitDeletedAt

`func (o *ShortUrlDomainListSchema) SetInitDeletedAt(v time.Time)`

SetInitDeletedAt sets InitDeletedAt field to given value.

### HasInitDeletedAt

`func (o *ShortUrlDomainListSchema) HasInitDeletedAt() bool`

HasInitDeletedAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ShortUrlDomainListSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ShortUrlDomainListSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ShortUrlDomainListSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ShortUrlDomainListSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetCanRefreshStatus

`func (o *ShortUrlDomainListSchema) GetCanRefreshStatus() bool`

GetCanRefreshStatus returns the CanRefreshStatus field if non-nil, zero value otherwise.

### GetCanRefreshStatusOk

`func (o *ShortUrlDomainListSchema) GetCanRefreshStatusOk() (*bool, bool)`

GetCanRefreshStatusOk returns a tuple with the CanRefreshStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanRefreshStatus

`func (o *ShortUrlDomainListSchema) SetCanRefreshStatus(v bool)`

SetCanRefreshStatus sets CanRefreshStatus field to given value.

### HasCanRefreshStatus

`func (o *ShortUrlDomainListSchema) HasCanRefreshStatus() bool`

HasCanRefreshStatus returns a boolean if a field has been set.

### GetCanRestore

`func (o *ShortUrlDomainListSchema) GetCanRestore() bool`

GetCanRestore returns the CanRestore field if non-nil, zero value otherwise.

### GetCanRestoreOk

`func (o *ShortUrlDomainListSchema) GetCanRestoreOk() (*bool, bool)`

GetCanRestoreOk returns a tuple with the CanRestore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanRestore

`func (o *ShortUrlDomainListSchema) SetCanRestore(v bool)`

SetCanRestore sets CanRestore field to given value.

### HasCanRestore

`func (o *ShortUrlDomainListSchema) HasCanRestore() bool`

HasCanRestore returns a boolean if a field has been set.

### GetCountShortLinks

`func (o *ShortUrlDomainListSchema) GetCountShortLinks() int32`

GetCountShortLinks returns the CountShortLinks field if non-nil, zero value otherwise.

### GetCountShortLinksOk

`func (o *ShortUrlDomainListSchema) GetCountShortLinksOk() (*int32, bool)`

GetCountShortLinksOk returns a tuple with the CountShortLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountShortLinks

`func (o *ShortUrlDomainListSchema) SetCountShortLinks(v int32)`

SetCountShortLinks sets CountShortLinks field to given value.

### HasCountShortLinks

`func (o *ShortUrlDomainListSchema) HasCountShortLinks() bool`

HasCountShortLinks returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


