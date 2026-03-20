# Recipients

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Phones** | Pointer to [**[]Phone**](Phone.md) | The list of objects containing information about the mobile phone number (number) and (reference_id) to send a message to | [optional] 
**Groups** | Pointer to **[]int32** | An array of lists (list id) with contacts from the address book to which RCS campaigns are to be sent. id of the lists can be obtained: using the Get [lists API](#tag/Contact-List) in your account [Contact Book → Lists](https://app.bsg.world/addressbook/lists) | [optional] 

## Methods

### NewRecipients

`func NewRecipients() *Recipients`

NewRecipients instantiates a new Recipients object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecipientsWithDefaults

`func NewRecipientsWithDefaults() *Recipients`

NewRecipientsWithDefaults instantiates a new Recipients object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhones

`func (o *Recipients) GetPhones() []Phone`

GetPhones returns the Phones field if non-nil, zero value otherwise.

### GetPhonesOk

`func (o *Recipients) GetPhonesOk() (*[]Phone, bool)`

GetPhonesOk returns a tuple with the Phones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhones

`func (o *Recipients) SetPhones(v []Phone)`

SetPhones sets Phones field to given value.

### HasPhones

`func (o *Recipients) HasPhones() bool`

HasPhones returns a boolean if a field has been set.

### GetGroups

`func (o *Recipients) GetGroups() []int32`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *Recipients) GetGroupsOk() (*[]int32, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *Recipients) SetGroups(v []int32)`

SetGroups sets Groups field to given value.

### HasGroups

`func (o *Recipients) HasGroups() bool`

HasGroups returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


