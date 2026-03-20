# SendTemplateEmail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**To** | **[]string** | List of email addresses to send the email to | 
**From** | **string** | The sender’s email address | 
**TemplateId** | **int32** | ID of the email template to be used for the email’s content | 
**Subject** | Pointer to **string** | The subject line of the email | [optional] 
**TemplateContent** | Pointer to **map[string]string** | JSON object with key-value pairs for dynamic content in the email template | [optional] 
**Inlines** | Pointer to [**[]Inline**](Inline.md) | A list of inline attachments | [optional] 

## Methods

### NewSendTemplateEmail

`func NewSendTemplateEmail(to []string, from string, templateId int32, ) *SendTemplateEmail`

NewSendTemplateEmail instantiates a new SendTemplateEmail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSendTemplateEmailWithDefaults

`func NewSendTemplateEmailWithDefaults() *SendTemplateEmail`

NewSendTemplateEmailWithDefaults instantiates a new SendTemplateEmail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTo

`func (o *SendTemplateEmail) GetTo() []string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SendTemplateEmail) GetToOk() (*[]string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SendTemplateEmail) SetTo(v []string)`

SetTo sets To field to given value.


### GetFrom

`func (o *SendTemplateEmail) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SendTemplateEmail) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SendTemplateEmail) SetFrom(v string)`

SetFrom sets From field to given value.


### GetTemplateId

`func (o *SendTemplateEmail) GetTemplateId() int32`

GetTemplateId returns the TemplateId field if non-nil, zero value otherwise.

### GetTemplateIdOk

`func (o *SendTemplateEmail) GetTemplateIdOk() (*int32, bool)`

GetTemplateIdOk returns a tuple with the TemplateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateId

`func (o *SendTemplateEmail) SetTemplateId(v int32)`

SetTemplateId sets TemplateId field to given value.


### GetSubject

`func (o *SendTemplateEmail) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *SendTemplateEmail) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *SendTemplateEmail) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *SendTemplateEmail) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### GetTemplateContent

`func (o *SendTemplateEmail) GetTemplateContent() map[string]string`

GetTemplateContent returns the TemplateContent field if non-nil, zero value otherwise.

### GetTemplateContentOk

`func (o *SendTemplateEmail) GetTemplateContentOk() (*map[string]string, bool)`

GetTemplateContentOk returns a tuple with the TemplateContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateContent

`func (o *SendTemplateEmail) SetTemplateContent(v map[string]string)`

SetTemplateContent sets TemplateContent field to given value.

### HasTemplateContent

`func (o *SendTemplateEmail) HasTemplateContent() bool`

HasTemplateContent returns a boolean if a field has been set.

### GetInlines

`func (o *SendTemplateEmail) GetInlines() []Inline`

GetInlines returns the Inlines field if non-nil, zero value otherwise.

### GetInlinesOk

`func (o *SendTemplateEmail) GetInlinesOk() (*[]Inline, bool)`

GetInlinesOk returns a tuple with the Inlines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInlines

`func (o *SendTemplateEmail) SetInlines(v []Inline)`

SetInlines sets Inlines field to given value.

### HasInlines

`func (o *SendTemplateEmail) HasInlines() bool`

HasInlines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


