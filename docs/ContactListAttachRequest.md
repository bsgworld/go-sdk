# ContactListAttachRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Contacts** | **[]int32** | contacts Id | 
**Groups** | **[]int32** | Contact lists IDs | 

## Methods

### NewContactListAttachRequest

`func NewContactListAttachRequest(contacts []int32, groups []int32, ) *ContactListAttachRequest`

NewContactListAttachRequest instantiates a new ContactListAttachRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactListAttachRequestWithDefaults

`func NewContactListAttachRequestWithDefaults() *ContactListAttachRequest`

NewContactListAttachRequestWithDefaults instantiates a new ContactListAttachRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContacts

`func (o *ContactListAttachRequest) GetContacts() []int32`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *ContactListAttachRequest) GetContactsOk() (*[]int32, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *ContactListAttachRequest) SetContacts(v []int32)`

SetContacts sets Contacts field to given value.


### GetGroups

`func (o *ContactListAttachRequest) GetGroups() []int32`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *ContactListAttachRequest) GetGroupsOk() (*[]int32, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *ContactListAttachRequest) SetGroups(v []int32)`

SetGroups sets Groups field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


