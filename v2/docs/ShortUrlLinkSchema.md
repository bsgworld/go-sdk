# ShortUrlLinkSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | short link unique id | [optional] 
**Status** | Pointer to [**ShortLinkStatus**](ShortLinkStatus.md) |  | [optional] 
**Name** | Pointer to **NullableString** | Name of short link. like a comment | [optional] 
**Slug** | Pointer to **string** | part of short link after domain | [optional] 
**CampaignId** | Pointer to **int32** | campaign ID if short link is part of sms campaign.  Campaign allow send messages to all the leads with different short link for each lead that follows to the same original link | [optional] 
**MessageId** | Pointer to **NullableInt32** | message id for short links created as part of [sms campaign](#tag/Campaign-SMS) | [optional] 
**InitDeletedAt** | Pointer to **time.Time** | Date and time when short link was deactivated | [optional] 
**CreatedAt** | Pointer to **time.Time** | Date and time when short link was created | [optional] 
**ShortLink** | Pointer to **string** | short link url that can be used to redirect to original link | [optional] 
**OriginalLink** | Pointer to **string** | Original link where to short link will redirect | [optional] 
**CanRestore** | Pointer to **bool** | For link marked as deleted it can be restored a few time if can_restore&#x3D;true | [optional] [default to true]
**CountClicks** | Pointer to **int32** | Number of clicks on a short link  *Please note: count of clicks updated with some latency* | [optional] 
**CountHumanClicks** | Pointer to **int32** | Number of clicks on a short link looks like human  We use some heuristics to determine is it real human or looks like bot | [optional] 
**CountUniqueClicks** | Pointer to **int32** | Number of unique clicks on a short link  We use combination of ip address user-agent cookies and so on to account the same user just once | [optional] 

## Methods

### NewShortUrlLinkSchema

`func NewShortUrlLinkSchema() *ShortUrlLinkSchema`

NewShortUrlLinkSchema instantiates a new ShortUrlLinkSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShortUrlLinkSchemaWithDefaults

`func NewShortUrlLinkSchemaWithDefaults() *ShortUrlLinkSchema`

NewShortUrlLinkSchemaWithDefaults instantiates a new ShortUrlLinkSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ShortUrlLinkSchema) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ShortUrlLinkSchema) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ShortUrlLinkSchema) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ShortUrlLinkSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetStatus

`func (o *ShortUrlLinkSchema) GetStatus() ShortLinkStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ShortUrlLinkSchema) GetStatusOk() (*ShortLinkStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ShortUrlLinkSchema) SetStatus(v ShortLinkStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ShortUrlLinkSchema) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetName

`func (o *ShortUrlLinkSchema) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ShortUrlLinkSchema) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ShortUrlLinkSchema) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ShortUrlLinkSchema) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ShortUrlLinkSchema) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ShortUrlLinkSchema) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetSlug

`func (o *ShortUrlLinkSchema) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *ShortUrlLinkSchema) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *ShortUrlLinkSchema) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *ShortUrlLinkSchema) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### GetCampaignId

`func (o *ShortUrlLinkSchema) GetCampaignId() int32`

GetCampaignId returns the CampaignId field if non-nil, zero value otherwise.

### GetCampaignIdOk

`func (o *ShortUrlLinkSchema) GetCampaignIdOk() (*int32, bool)`

GetCampaignIdOk returns a tuple with the CampaignId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignId

`func (o *ShortUrlLinkSchema) SetCampaignId(v int32)`

SetCampaignId sets CampaignId field to given value.

### HasCampaignId

`func (o *ShortUrlLinkSchema) HasCampaignId() bool`

HasCampaignId returns a boolean if a field has been set.

### GetMessageId

`func (o *ShortUrlLinkSchema) GetMessageId() int32`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *ShortUrlLinkSchema) GetMessageIdOk() (*int32, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *ShortUrlLinkSchema) SetMessageId(v int32)`

SetMessageId sets MessageId field to given value.

### HasMessageId

`func (o *ShortUrlLinkSchema) HasMessageId() bool`

HasMessageId returns a boolean if a field has been set.

### SetMessageIdNil

`func (o *ShortUrlLinkSchema) SetMessageIdNil(b bool)`

 SetMessageIdNil sets the value for MessageId to be an explicit nil

### UnsetMessageId
`func (o *ShortUrlLinkSchema) UnsetMessageId()`

UnsetMessageId ensures that no value is present for MessageId, not even an explicit nil
### GetInitDeletedAt

`func (o *ShortUrlLinkSchema) GetInitDeletedAt() time.Time`

GetInitDeletedAt returns the InitDeletedAt field if non-nil, zero value otherwise.

### GetInitDeletedAtOk

`func (o *ShortUrlLinkSchema) GetInitDeletedAtOk() (*time.Time, bool)`

GetInitDeletedAtOk returns a tuple with the InitDeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitDeletedAt

`func (o *ShortUrlLinkSchema) SetInitDeletedAt(v time.Time)`

SetInitDeletedAt sets InitDeletedAt field to given value.

### HasInitDeletedAt

`func (o *ShortUrlLinkSchema) HasInitDeletedAt() bool`

HasInitDeletedAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ShortUrlLinkSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ShortUrlLinkSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ShortUrlLinkSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ShortUrlLinkSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetShortLink

`func (o *ShortUrlLinkSchema) GetShortLink() string`

GetShortLink returns the ShortLink field if non-nil, zero value otherwise.

### GetShortLinkOk

`func (o *ShortUrlLinkSchema) GetShortLinkOk() (*string, bool)`

GetShortLinkOk returns a tuple with the ShortLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortLink

`func (o *ShortUrlLinkSchema) SetShortLink(v string)`

SetShortLink sets ShortLink field to given value.

### HasShortLink

`func (o *ShortUrlLinkSchema) HasShortLink() bool`

HasShortLink returns a boolean if a field has been set.

### GetOriginalLink

`func (o *ShortUrlLinkSchema) GetOriginalLink() string`

GetOriginalLink returns the OriginalLink field if non-nil, zero value otherwise.

### GetOriginalLinkOk

`func (o *ShortUrlLinkSchema) GetOriginalLinkOk() (*string, bool)`

GetOriginalLinkOk returns a tuple with the OriginalLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalLink

`func (o *ShortUrlLinkSchema) SetOriginalLink(v string)`

SetOriginalLink sets OriginalLink field to given value.

### HasOriginalLink

`func (o *ShortUrlLinkSchema) HasOriginalLink() bool`

HasOriginalLink returns a boolean if a field has been set.

### GetCanRestore

`func (o *ShortUrlLinkSchema) GetCanRestore() bool`

GetCanRestore returns the CanRestore field if non-nil, zero value otherwise.

### GetCanRestoreOk

`func (o *ShortUrlLinkSchema) GetCanRestoreOk() (*bool, bool)`

GetCanRestoreOk returns a tuple with the CanRestore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanRestore

`func (o *ShortUrlLinkSchema) SetCanRestore(v bool)`

SetCanRestore sets CanRestore field to given value.

### HasCanRestore

`func (o *ShortUrlLinkSchema) HasCanRestore() bool`

HasCanRestore returns a boolean if a field has been set.

### GetCountClicks

`func (o *ShortUrlLinkSchema) GetCountClicks() int32`

GetCountClicks returns the CountClicks field if non-nil, zero value otherwise.

### GetCountClicksOk

`func (o *ShortUrlLinkSchema) GetCountClicksOk() (*int32, bool)`

GetCountClicksOk returns a tuple with the CountClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountClicks

`func (o *ShortUrlLinkSchema) SetCountClicks(v int32)`

SetCountClicks sets CountClicks field to given value.

### HasCountClicks

`func (o *ShortUrlLinkSchema) HasCountClicks() bool`

HasCountClicks returns a boolean if a field has been set.

### GetCountHumanClicks

`func (o *ShortUrlLinkSchema) GetCountHumanClicks() int32`

GetCountHumanClicks returns the CountHumanClicks field if non-nil, zero value otherwise.

### GetCountHumanClicksOk

`func (o *ShortUrlLinkSchema) GetCountHumanClicksOk() (*int32, bool)`

GetCountHumanClicksOk returns a tuple with the CountHumanClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountHumanClicks

`func (o *ShortUrlLinkSchema) SetCountHumanClicks(v int32)`

SetCountHumanClicks sets CountHumanClicks field to given value.

### HasCountHumanClicks

`func (o *ShortUrlLinkSchema) HasCountHumanClicks() bool`

HasCountHumanClicks returns a boolean if a field has been set.

### GetCountUniqueClicks

`func (o *ShortUrlLinkSchema) GetCountUniqueClicks() int32`

GetCountUniqueClicks returns the CountUniqueClicks field if non-nil, zero value otherwise.

### GetCountUniqueClicksOk

`func (o *ShortUrlLinkSchema) GetCountUniqueClicksOk() (*int32, bool)`

GetCountUniqueClicksOk returns a tuple with the CountUniqueClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountUniqueClicks

`func (o *ShortUrlLinkSchema) SetCountUniqueClicks(v int32)`

SetCountUniqueClicks sets CountUniqueClicks field to given value.

### HasCountUniqueClicks

`func (o *ShortUrlLinkSchema) HasCountUniqueClicks() bool`

HasCountUniqueClicks returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


