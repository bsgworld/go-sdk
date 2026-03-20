# SendEmail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**To** | **[]string** | List of email addresses to send the email to | 
**From** | **string** | The sender’s email address | 
**Subject** | **string** | The subject line of the email | 
**Body** | Pointer to **NullableString** | Optional email body as plain text in addition to &#x60;htmlbody&#x60; for old email clients without html support | [optional] 
**Htmlbody** | **NullableString** | The HTML-formatted content of the email body (can include rich text elements) | 
**Inlines** | Pointer to [**[]Inline**](Inline.md) | A list of inline attachments | [optional] 

## Methods

### NewSendEmail

`func NewSendEmail(to []string, from string, subject string, htmlbody NullableString, ) *SendEmail`

NewSendEmail instantiates a new SendEmail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSendEmailWithDefaults

`func NewSendEmailWithDefaults() *SendEmail`

NewSendEmailWithDefaults instantiates a new SendEmail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTo

`func (o *SendEmail) GetTo() []string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SendEmail) GetToOk() (*[]string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SendEmail) SetTo(v []string)`

SetTo sets To field to given value.


### GetFrom

`func (o *SendEmail) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SendEmail) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SendEmail) SetFrom(v string)`

SetFrom sets From field to given value.


### GetSubject

`func (o *SendEmail) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *SendEmail) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *SendEmail) SetSubject(v string)`

SetSubject sets Subject field to given value.


### GetBody

`func (o *SendEmail) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *SendEmail) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *SendEmail) SetBody(v string)`

SetBody sets Body field to given value.

### HasBody

`func (o *SendEmail) HasBody() bool`

HasBody returns a boolean if a field has been set.

### SetBodyNil

`func (o *SendEmail) SetBodyNil(b bool)`

 SetBodyNil sets the value for Body to be an explicit nil

### UnsetBody
`func (o *SendEmail) UnsetBody()`

UnsetBody ensures that no value is present for Body, not even an explicit nil
### GetHtmlbody

`func (o *SendEmail) GetHtmlbody() string`

GetHtmlbody returns the Htmlbody field if non-nil, zero value otherwise.

### GetHtmlbodyOk

`func (o *SendEmail) GetHtmlbodyOk() (*string, bool)`

GetHtmlbodyOk returns a tuple with the Htmlbody field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHtmlbody

`func (o *SendEmail) SetHtmlbody(v string)`

SetHtmlbody sets Htmlbody field to given value.


### SetHtmlbodyNil

`func (o *SendEmail) SetHtmlbodyNil(b bool)`

 SetHtmlbodyNil sets the value for Htmlbody to be an explicit nil

### UnsetHtmlbody
`func (o *SendEmail) UnsetHtmlbody()`

UnsetHtmlbody ensures that no value is present for Htmlbody, not even an explicit nil
### GetInlines

`func (o *SendEmail) GetInlines() []Inline`

GetInlines returns the Inlines field if non-nil, zero value otherwise.

### GetInlinesOk

`func (o *SendEmail) GetInlinesOk() (*[]Inline, bool)`

GetInlinesOk returns a tuple with the Inlines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInlines

`func (o *SendEmail) SetInlines(v []Inline)`

SetInlines sets Inlines field to given value.

### HasInlines

`func (o *SendEmail) HasInlines() bool`

HasInlines returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


