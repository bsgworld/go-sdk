# WhatsAppMessageTemplate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Template name | 
**Language** | [**Language**](Language.md) |  | 
**Components** | [**[]Components**](Components.md) |  | 

## Methods

### NewWhatsAppMessageTemplate

`func NewWhatsAppMessageTemplate(name string, language Language, components []Components, ) *WhatsAppMessageTemplate`

NewWhatsAppMessageTemplate instantiates a new WhatsAppMessageTemplate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWhatsAppMessageTemplateWithDefaults

`func NewWhatsAppMessageTemplateWithDefaults() *WhatsAppMessageTemplate`

NewWhatsAppMessageTemplateWithDefaults instantiates a new WhatsAppMessageTemplate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *WhatsAppMessageTemplate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WhatsAppMessageTemplate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WhatsAppMessageTemplate) SetName(v string)`

SetName sets Name field to given value.


### GetLanguage

`func (o *WhatsAppMessageTemplate) GetLanguage() Language`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *WhatsAppMessageTemplate) GetLanguageOk() (*Language, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *WhatsAppMessageTemplate) SetLanguage(v Language)`

SetLanguage sets Language field to given value.


### GetComponents

`func (o *WhatsAppMessageTemplate) GetComponents() []Components`

GetComponents returns the Components field if non-nil, zero value otherwise.

### GetComponentsOk

`func (o *WhatsAppMessageTemplate) GetComponentsOk() (*[]Components, bool)`

GetComponentsOk returns a tuple with the Components field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponents

`func (o *WhatsAppMessageTemplate) SetComponents(v []Components)`

SetComponents sets Components field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


