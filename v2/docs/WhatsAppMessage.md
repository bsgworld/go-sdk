# WhatsAppMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Phone** | [**Phone**](Phone.md) |  | 
**Sender** | **string** |  | 
**Type** | **string** |  | 
**Template** | Pointer to [**NullableWhatsAppMessageTemplate**](WhatsAppMessageTemplate.md) |  | [optional] 
**AlternativeChannel** | Pointer to [**NullableWhatsAppMessageAlternativeChannel**](WhatsAppMessageAlternativeChannel.md) |  | [optional] 
**CallbackUrl** | Pointer to **interface{}** | Link to get the delivery status of messages. If this parameter is specified in the method, it will take precedence over the value specified in the “Callback URL” field in the Personal Area. | [optional] 
**AddToContactBook** | Pointer to **bool** |  | [optional] [default to true]
**CheckStopList** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewWhatsAppMessage

`func NewWhatsAppMessage(phone Phone, sender string, type_ string, ) *WhatsAppMessage`

NewWhatsAppMessage instantiates a new WhatsAppMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWhatsAppMessageWithDefaults

`func NewWhatsAppMessageWithDefaults() *WhatsAppMessage`

NewWhatsAppMessageWithDefaults instantiates a new WhatsAppMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhone

`func (o *WhatsAppMessage) GetPhone() Phone`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *WhatsAppMessage) GetPhoneOk() (*Phone, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *WhatsAppMessage) SetPhone(v Phone)`

SetPhone sets Phone field to given value.


### GetSender

`func (o *WhatsAppMessage) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *WhatsAppMessage) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *WhatsAppMessage) SetSender(v string)`

SetSender sets Sender field to given value.


### GetType

`func (o *WhatsAppMessage) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *WhatsAppMessage) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *WhatsAppMessage) SetType(v string)`

SetType sets Type field to given value.


### GetTemplate

`func (o *WhatsAppMessage) GetTemplate() WhatsAppMessageTemplate`

GetTemplate returns the Template field if non-nil, zero value otherwise.

### GetTemplateOk

`func (o *WhatsAppMessage) GetTemplateOk() (*WhatsAppMessageTemplate, bool)`

GetTemplateOk returns a tuple with the Template field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplate

`func (o *WhatsAppMessage) SetTemplate(v WhatsAppMessageTemplate)`

SetTemplate sets Template field to given value.

### HasTemplate

`func (o *WhatsAppMessage) HasTemplate() bool`

HasTemplate returns a boolean if a field has been set.

### SetTemplateNil

`func (o *WhatsAppMessage) SetTemplateNil(b bool)`

 SetTemplateNil sets the value for Template to be an explicit nil

### UnsetTemplate
`func (o *WhatsAppMessage) UnsetTemplate()`

UnsetTemplate ensures that no value is present for Template, not even an explicit nil
### GetAlternativeChannel

`func (o *WhatsAppMessage) GetAlternativeChannel() WhatsAppMessageAlternativeChannel`

GetAlternativeChannel returns the AlternativeChannel field if non-nil, zero value otherwise.

### GetAlternativeChannelOk

`func (o *WhatsAppMessage) GetAlternativeChannelOk() (*WhatsAppMessageAlternativeChannel, bool)`

GetAlternativeChannelOk returns a tuple with the AlternativeChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternativeChannel

`func (o *WhatsAppMessage) SetAlternativeChannel(v WhatsAppMessageAlternativeChannel)`

SetAlternativeChannel sets AlternativeChannel field to given value.

### HasAlternativeChannel

`func (o *WhatsAppMessage) HasAlternativeChannel() bool`

HasAlternativeChannel returns a boolean if a field has been set.

### SetAlternativeChannelNil

`func (o *WhatsAppMessage) SetAlternativeChannelNil(b bool)`

 SetAlternativeChannelNil sets the value for AlternativeChannel to be an explicit nil

### UnsetAlternativeChannel
`func (o *WhatsAppMessage) UnsetAlternativeChannel()`

UnsetAlternativeChannel ensures that no value is present for AlternativeChannel, not even an explicit nil
### GetCallbackUrl

`func (o *WhatsAppMessage) GetCallbackUrl() interface{}`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *WhatsAppMessage) GetCallbackUrlOk() (*interface{}, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *WhatsAppMessage) SetCallbackUrl(v interface{})`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *WhatsAppMessage) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### SetCallbackUrlNil

`func (o *WhatsAppMessage) SetCallbackUrlNil(b bool)`

 SetCallbackUrlNil sets the value for CallbackUrl to be an explicit nil

### UnsetCallbackUrl
`func (o *WhatsAppMessage) UnsetCallbackUrl()`

UnsetCallbackUrl ensures that no value is present for CallbackUrl, not even an explicit nil
### GetAddToContactBook

`func (o *WhatsAppMessage) GetAddToContactBook() bool`

GetAddToContactBook returns the AddToContactBook field if non-nil, zero value otherwise.

### GetAddToContactBookOk

`func (o *WhatsAppMessage) GetAddToContactBookOk() (*bool, bool)`

GetAddToContactBookOk returns a tuple with the AddToContactBook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddToContactBook

`func (o *WhatsAppMessage) SetAddToContactBook(v bool)`

SetAddToContactBook sets AddToContactBook field to given value.

### HasAddToContactBook

`func (o *WhatsAppMessage) HasAddToContactBook() bool`

HasAddToContactBook returns a boolean if a field has been set.

### GetCheckStopList

`func (o *WhatsAppMessage) GetCheckStopList() bool`

GetCheckStopList returns the CheckStopList field if non-nil, zero value otherwise.

### GetCheckStopListOk

`func (o *WhatsAppMessage) GetCheckStopListOk() (*bool, bool)`

GetCheckStopListOk returns a tuple with the CheckStopList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckStopList

`func (o *WhatsAppMessage) SetCheckStopList(v bool)`

SetCheckStopList sets CheckStopList field to given value.

### HasCheckStopList

`func (o *WhatsAppMessage) HasCheckStopList() bool`

HasCheckStopList returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


