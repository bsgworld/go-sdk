# Media

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | Contains a link to an image or video that will be to be attached to the message. The link must begin with http/https.  Acceptable formats for images/videos:   - pictures: jpeg, jpg, gif, png  - videos: h263, m4v, mp4, mpeg, mpeg4, webm  - size: images – 2 MB, videos – 10 MB | 

## Methods

### NewMedia

`func NewMedia(url string, ) *Media`

NewMedia instantiates a new Media object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMediaWithDefaults

`func NewMediaWithDefaults() *Media`

NewMediaWithDefaults instantiates a new Media object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *Media) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *Media) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *Media) SetUrl(v string)`

SetUrl sets Url field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


