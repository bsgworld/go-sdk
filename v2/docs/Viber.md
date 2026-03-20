# Viber

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sender** | **NullableString** |  | 
**Text** | **NullableString** |  | 
**ImageUrl** | Pointer to **string** |  | [optional] 
**ButtonCaption** | Pointer to **string** |  | [optional] 
**LinkUrl** | Pointer to **string** | Required if button_caption is set | [optional] 

## Methods

### NewViber

`func NewViber(sender NullableString, text NullableString, ) *Viber`

NewViber instantiates a new Viber object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberWithDefaults

`func NewViberWithDefaults() *Viber`

NewViberWithDefaults instantiates a new Viber object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSender

`func (o *Viber) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *Viber) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *Viber) SetSender(v string)`

SetSender sets Sender field to given value.


### SetSenderNil

`func (o *Viber) SetSenderNil(b bool)`

 SetSenderNil sets the value for Sender to be an explicit nil

### UnsetSender
`func (o *Viber) UnsetSender()`

UnsetSender ensures that no value is present for Sender, not even an explicit nil
### GetText

`func (o *Viber) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *Viber) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *Viber) SetText(v string)`

SetText sets Text field to given value.


### SetTextNil

`func (o *Viber) SetTextNil(b bool)`

 SetTextNil sets the value for Text to be an explicit nil

### UnsetText
`func (o *Viber) UnsetText()`

UnsetText ensures that no value is present for Text, not even an explicit nil
### GetImageUrl

`func (o *Viber) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *Viber) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *Viber) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *Viber) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### GetButtonCaption

`func (o *Viber) GetButtonCaption() string`

GetButtonCaption returns the ButtonCaption field if non-nil, zero value otherwise.

### GetButtonCaptionOk

`func (o *Viber) GetButtonCaptionOk() (*string, bool)`

GetButtonCaptionOk returns a tuple with the ButtonCaption field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetButtonCaption

`func (o *Viber) SetButtonCaption(v string)`

SetButtonCaption sets ButtonCaption field to given value.

### HasButtonCaption

`func (o *Viber) HasButtonCaption() bool`

HasButtonCaption returns a boolean if a field has been set.

### GetLinkUrl

`func (o *Viber) GetLinkUrl() string`

GetLinkUrl returns the LinkUrl field if non-nil, zero value otherwise.

### GetLinkUrlOk

`func (o *Viber) GetLinkUrlOk() (*string, bool)`

GetLinkUrlOk returns a tuple with the LinkUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkUrl

`func (o *Viber) SetLinkUrl(v string)`

SetLinkUrl sets LinkUrl field to given value.

### HasLinkUrl

`func (o *Viber) HasLinkUrl() bool`

HasLinkUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


