# RcsClickCallback

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Message ID – a unique identifier automatically generated on the Platform when the message is created | [optional] 
**Reference** | Pointer to **string** | external unique ID. String up to 32 characters containing only alpha numeric characters.  **Please note:** messages with duplicate reference_id will be rejected | [optional] 
**Msisdn** | Pointer to **string** | Phone number | [optional] 
**Text** | Pointer to **string** | Text on clicked button from suggestions | [optional] 
**Postback** | Pointer to **string** | postback_data field value from suggestion button object | [optional] 
**TimeClick** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 

## Methods

### NewRcsClickCallback

`func NewRcsClickCallback() *RcsClickCallback`

NewRcsClickCallback instantiates a new RcsClickCallback object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRcsClickCallbackWithDefaults

`func NewRcsClickCallbackWithDefaults() *RcsClickCallback`

NewRcsClickCallbackWithDefaults instantiates a new RcsClickCallback object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RcsClickCallback) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RcsClickCallback) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RcsClickCallback) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *RcsClickCallback) HasId() bool`

HasId returns a boolean if a field has been set.

### GetReference

`func (o *RcsClickCallback) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *RcsClickCallback) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *RcsClickCallback) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *RcsClickCallback) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetMsisdn

`func (o *RcsClickCallback) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *RcsClickCallback) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *RcsClickCallback) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.

### HasMsisdn

`func (o *RcsClickCallback) HasMsisdn() bool`

HasMsisdn returns a boolean if a field has been set.

### GetText

`func (o *RcsClickCallback) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *RcsClickCallback) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *RcsClickCallback) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *RcsClickCallback) HasText() bool`

HasText returns a boolean if a field has been set.

### GetPostback

`func (o *RcsClickCallback) GetPostback() string`

GetPostback returns the Postback field if non-nil, zero value otherwise.

### GetPostbackOk

`func (o *RcsClickCallback) GetPostbackOk() (*string, bool)`

GetPostbackOk returns a tuple with the Postback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostback

`func (o *RcsClickCallback) SetPostback(v string)`

SetPostback sets Postback field to given value.

### HasPostback

`func (o *RcsClickCallback) HasPostback() bool`

HasPostback returns a boolean if a field has been set.

### GetTimeClick

`func (o *RcsClickCallback) GetTimeClick() time.Time`

GetTimeClick returns the TimeClick field if non-nil, zero value otherwise.

### GetTimeClickOk

`func (o *RcsClickCallback) GetTimeClickOk() (*time.Time, bool)`

GetTimeClickOk returns a tuple with the TimeClick field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeClick

`func (o *RcsClickCallback) SetTimeClick(v time.Time)`

SetTimeClick sets TimeClick field to given value.

### HasTimeClick

`func (o *RcsClickCallback) HasTimeClick() bool`

HasTimeClick returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


