# GroupsTrait

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Groups** | **[]int32** | An array of lists (list id) with contacts from the address book to which RCS campaigns are to be sent. id of the lists can be obtained: using the Get [lists API](#tag/Contact-List) in your account [Contact Book → Lists](https://app.bsg.world/addressbook/lists) | 

## Methods

### NewGroupsTrait

`func NewGroupsTrait(groups []int32, ) *GroupsTrait`

NewGroupsTrait instantiates a new GroupsTrait object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupsTraitWithDefaults

`func NewGroupsTraitWithDefaults() *GroupsTrait`

NewGroupsTraitWithDefaults instantiates a new GroupsTrait object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroups

`func (o *GroupsTrait) GetGroups() []int32`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *GroupsTrait) GetGroupsOk() (*[]int32, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *GroupsTrait) SetGroups(v []int32)`

SetGroups sets Groups field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


