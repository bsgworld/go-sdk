# ContactListDetachRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Contacts** | **[]int32** | contacts Id | 
**Groups** | **[]int32** | Contact lists IDs | 

## Methods

### NewContactListDetachRequest

`func NewContactListDetachRequest(contacts []int32, groups []int32, ) *ContactListDetachRequest`

NewContactListDetachRequest instantiates a new ContactListDetachRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactListDetachRequestWithDefaults

`func NewContactListDetachRequestWithDefaults() *ContactListDetachRequest`

NewContactListDetachRequestWithDefaults instantiates a new ContactListDetachRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContacts

`func (o *ContactListDetachRequest) GetContacts() []int32`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *ContactListDetachRequest) GetContactsOk() (*[]int32, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *ContactListDetachRequest) SetContacts(v []int32)`

SetContacts sets Contacts field to given value.


### GetGroups

`func (o *ContactListDetachRequest) GetGroups() []int32`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *ContactListDetachRequest) GetGroupsOk() (*[]int32, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *ContactListDetachRequest) SetGroups(v []int32)`

SetGroups sets Groups field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


