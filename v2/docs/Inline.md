# Inline

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | A variable representing the name or identifier of the inline attachment | 
**Cid** | **string** | The content identifier (links the inline attachment to the email body) | 
**ContentType** | Pointer to **string** | MIME content type | [optional] 
**Content** | **string** | The base64-encoded content of the inline attachment | 

## Methods

### NewInline

`func NewInline(name string, cid string, content string, ) *Inline`

NewInline instantiates a new Inline object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInlineWithDefaults

`func NewInlineWithDefaults() *Inline`

NewInlineWithDefaults instantiates a new Inline object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *Inline) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Inline) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Inline) SetName(v string)`

SetName sets Name field to given value.


### GetCid

`func (o *Inline) GetCid() string`

GetCid returns the Cid field if non-nil, zero value otherwise.

### GetCidOk

`func (o *Inline) GetCidOk() (*string, bool)`

GetCidOk returns a tuple with the Cid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCid

`func (o *Inline) SetCid(v string)`

SetCid sets Cid field to given value.


### GetContentType

`func (o *Inline) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *Inline) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *Inline) SetContentType(v string)`

SetContentType sets ContentType field to given value.

### HasContentType

`func (o *Inline) HasContentType() bool`

HasContentType returns a boolean if a field has been set.

### GetContent

`func (o *Inline) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *Inline) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *Inline) SetContent(v string)`

SetContent sets Content field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


