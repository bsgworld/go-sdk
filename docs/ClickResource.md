# ClickResource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | click unique uuid | [optional] 
**BrowserLanguage** | Pointer to **string** | Language of user browser | [optional] 
**CountryCode** | Pointer to **NullableString** | User country detected by geo ip | [optional] 
**IsHuman** | Pointer to **bool** | We use some heuristics to determine is it real human or looks like bot | [optional] 
**IsUnique** | Pointer to **bool** | We use combination of ip address user-agent cookies and so on to account the same user just once | [optional] 
**HttpStatus** | Pointer to **int32** | Status code returned by GET original link when redirecting the user | [optional] 
**HttpMethod** | Pointer to **string** | Http method used by user when click on short link | [optional] 
**CreatedAt** | Pointer to **time.Time** | Date and time of click | [optional] 
**UserAgent** | Pointer to **string** | User-agent of first click | [optional] 
**ClientIp** | Pointer to **string** | Client IP address of first click | [optional] 
**Browser** | Pointer to **string** | User browser detected from user-agent | [optional] 
**ReferrerUrl** | Pointer to **NullableString** | source page from witch user click on short link | [optional] 
**City** | Pointer to **NullableString** | User city detected by geo ip | [optional] 
**DeviceOs** | Pointer to **NullableString** | User device operation system detected from user-agent | [optional] 
**ShortLink** | Pointer to **string** | short link url that can be used to redirect to original link | [optional] 
**OriginalLink** | Pointer to **string** | Original link where to short link will redirect | [optional] 
**MessageId** | Pointer to **NullableInt32** | message id for short links created as part of [sms campaign](#tag/Campaign-SMS) | [optional] 
**PhoneNumber** | Pointer to **NullableInt32** | Phone number without leading plus. For short links created as part of [sms campaign](#tag/Campaign-SMS) | [optional] 

## Methods

### NewClickResource

`func NewClickResource() *ClickResource`

NewClickResource instantiates a new ClickResource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClickResourceWithDefaults

`func NewClickResourceWithDefaults() *ClickResource`

NewClickResourceWithDefaults instantiates a new ClickResource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ClickResource) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClickResource) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClickResource) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ClickResource) HasId() bool`

HasId returns a boolean if a field has been set.

### GetBrowserLanguage

`func (o *ClickResource) GetBrowserLanguage() string`

GetBrowserLanguage returns the BrowserLanguage field if non-nil, zero value otherwise.

### GetBrowserLanguageOk

`func (o *ClickResource) GetBrowserLanguageOk() (*string, bool)`

GetBrowserLanguageOk returns a tuple with the BrowserLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrowserLanguage

`func (o *ClickResource) SetBrowserLanguage(v string)`

SetBrowserLanguage sets BrowserLanguage field to given value.

### HasBrowserLanguage

`func (o *ClickResource) HasBrowserLanguage() bool`

HasBrowserLanguage returns a boolean if a field has been set.

### GetCountryCode

`func (o *ClickResource) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *ClickResource) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *ClickResource) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *ClickResource) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### SetCountryCodeNil

`func (o *ClickResource) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *ClickResource) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetIsHuman

`func (o *ClickResource) GetIsHuman() bool`

GetIsHuman returns the IsHuman field if non-nil, zero value otherwise.

### GetIsHumanOk

`func (o *ClickResource) GetIsHumanOk() (*bool, bool)`

GetIsHumanOk returns a tuple with the IsHuman field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsHuman

`func (o *ClickResource) SetIsHuman(v bool)`

SetIsHuman sets IsHuman field to given value.

### HasIsHuman

`func (o *ClickResource) HasIsHuman() bool`

HasIsHuman returns a boolean if a field has been set.

### GetIsUnique

`func (o *ClickResource) GetIsUnique() bool`

GetIsUnique returns the IsUnique field if non-nil, zero value otherwise.

### GetIsUniqueOk

`func (o *ClickResource) GetIsUniqueOk() (*bool, bool)`

GetIsUniqueOk returns a tuple with the IsUnique field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsUnique

`func (o *ClickResource) SetIsUnique(v bool)`

SetIsUnique sets IsUnique field to given value.

### HasIsUnique

`func (o *ClickResource) HasIsUnique() bool`

HasIsUnique returns a boolean if a field has been set.

### GetHttpStatus

`func (o *ClickResource) GetHttpStatus() int32`

GetHttpStatus returns the HttpStatus field if non-nil, zero value otherwise.

### GetHttpStatusOk

`func (o *ClickResource) GetHttpStatusOk() (*int32, bool)`

GetHttpStatusOk returns a tuple with the HttpStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHttpStatus

`func (o *ClickResource) SetHttpStatus(v int32)`

SetHttpStatus sets HttpStatus field to given value.

### HasHttpStatus

`func (o *ClickResource) HasHttpStatus() bool`

HasHttpStatus returns a boolean if a field has been set.

### GetHttpMethod

`func (o *ClickResource) GetHttpMethod() string`

GetHttpMethod returns the HttpMethod field if non-nil, zero value otherwise.

### GetHttpMethodOk

`func (o *ClickResource) GetHttpMethodOk() (*string, bool)`

GetHttpMethodOk returns a tuple with the HttpMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHttpMethod

`func (o *ClickResource) SetHttpMethod(v string)`

SetHttpMethod sets HttpMethod field to given value.

### HasHttpMethod

`func (o *ClickResource) HasHttpMethod() bool`

HasHttpMethod returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ClickResource) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClickResource) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClickResource) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ClickResource) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUserAgent

`func (o *ClickResource) GetUserAgent() string`

GetUserAgent returns the UserAgent field if non-nil, zero value otherwise.

### GetUserAgentOk

`func (o *ClickResource) GetUserAgentOk() (*string, bool)`

GetUserAgentOk returns a tuple with the UserAgent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserAgent

`func (o *ClickResource) SetUserAgent(v string)`

SetUserAgent sets UserAgent field to given value.

### HasUserAgent

`func (o *ClickResource) HasUserAgent() bool`

HasUserAgent returns a boolean if a field has been set.

### GetClientIp

`func (o *ClickResource) GetClientIp() string`

GetClientIp returns the ClientIp field if non-nil, zero value otherwise.

### GetClientIpOk

`func (o *ClickResource) GetClientIpOk() (*string, bool)`

GetClientIpOk returns a tuple with the ClientIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientIp

`func (o *ClickResource) SetClientIp(v string)`

SetClientIp sets ClientIp field to given value.

### HasClientIp

`func (o *ClickResource) HasClientIp() bool`

HasClientIp returns a boolean if a field has been set.

### GetBrowser

`func (o *ClickResource) GetBrowser() string`

GetBrowser returns the Browser field if non-nil, zero value otherwise.

### GetBrowserOk

`func (o *ClickResource) GetBrowserOk() (*string, bool)`

GetBrowserOk returns a tuple with the Browser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrowser

`func (o *ClickResource) SetBrowser(v string)`

SetBrowser sets Browser field to given value.

### HasBrowser

`func (o *ClickResource) HasBrowser() bool`

HasBrowser returns a boolean if a field has been set.

### GetReferrerUrl

`func (o *ClickResource) GetReferrerUrl() string`

GetReferrerUrl returns the ReferrerUrl field if non-nil, zero value otherwise.

### GetReferrerUrlOk

`func (o *ClickResource) GetReferrerUrlOk() (*string, bool)`

GetReferrerUrlOk returns a tuple with the ReferrerUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferrerUrl

`func (o *ClickResource) SetReferrerUrl(v string)`

SetReferrerUrl sets ReferrerUrl field to given value.

### HasReferrerUrl

`func (o *ClickResource) HasReferrerUrl() bool`

HasReferrerUrl returns a boolean if a field has been set.

### SetReferrerUrlNil

`func (o *ClickResource) SetReferrerUrlNil(b bool)`

 SetReferrerUrlNil sets the value for ReferrerUrl to be an explicit nil

### UnsetReferrerUrl
`func (o *ClickResource) UnsetReferrerUrl()`

UnsetReferrerUrl ensures that no value is present for ReferrerUrl, not even an explicit nil
### GetCity

`func (o *ClickResource) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *ClickResource) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *ClickResource) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *ClickResource) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *ClickResource) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *ClickResource) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetDeviceOs

`func (o *ClickResource) GetDeviceOs() string`

GetDeviceOs returns the DeviceOs field if non-nil, zero value otherwise.

### GetDeviceOsOk

`func (o *ClickResource) GetDeviceOsOk() (*string, bool)`

GetDeviceOsOk returns a tuple with the DeviceOs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceOs

`func (o *ClickResource) SetDeviceOs(v string)`

SetDeviceOs sets DeviceOs field to given value.

### HasDeviceOs

`func (o *ClickResource) HasDeviceOs() bool`

HasDeviceOs returns a boolean if a field has been set.

### SetDeviceOsNil

`func (o *ClickResource) SetDeviceOsNil(b bool)`

 SetDeviceOsNil sets the value for DeviceOs to be an explicit nil

### UnsetDeviceOs
`func (o *ClickResource) UnsetDeviceOs()`

UnsetDeviceOs ensures that no value is present for DeviceOs, not even an explicit nil
### GetShortLink

`func (o *ClickResource) GetShortLink() string`

GetShortLink returns the ShortLink field if non-nil, zero value otherwise.

### GetShortLinkOk

`func (o *ClickResource) GetShortLinkOk() (*string, bool)`

GetShortLinkOk returns a tuple with the ShortLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortLink

`func (o *ClickResource) SetShortLink(v string)`

SetShortLink sets ShortLink field to given value.

### HasShortLink

`func (o *ClickResource) HasShortLink() bool`

HasShortLink returns a boolean if a field has been set.

### GetOriginalLink

`func (o *ClickResource) GetOriginalLink() string`

GetOriginalLink returns the OriginalLink field if non-nil, zero value otherwise.

### GetOriginalLinkOk

`func (o *ClickResource) GetOriginalLinkOk() (*string, bool)`

GetOriginalLinkOk returns a tuple with the OriginalLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalLink

`func (o *ClickResource) SetOriginalLink(v string)`

SetOriginalLink sets OriginalLink field to given value.

### HasOriginalLink

`func (o *ClickResource) HasOriginalLink() bool`

HasOriginalLink returns a boolean if a field has been set.

### GetMessageId

`func (o *ClickResource) GetMessageId() int32`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *ClickResource) GetMessageIdOk() (*int32, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *ClickResource) SetMessageId(v int32)`

SetMessageId sets MessageId field to given value.

### HasMessageId

`func (o *ClickResource) HasMessageId() bool`

HasMessageId returns a boolean if a field has been set.

### SetMessageIdNil

`func (o *ClickResource) SetMessageIdNil(b bool)`

 SetMessageIdNil sets the value for MessageId to be an explicit nil

### UnsetMessageId
`func (o *ClickResource) UnsetMessageId()`

UnsetMessageId ensures that no value is present for MessageId, not even an explicit nil
### GetPhoneNumber

`func (o *ClickResource) GetPhoneNumber() int32`

GetPhoneNumber returns the PhoneNumber field if non-nil, zero value otherwise.

### GetPhoneNumberOk

`func (o *ClickResource) GetPhoneNumberOk() (*int32, bool)`

GetPhoneNumberOk returns a tuple with the PhoneNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhoneNumber

`func (o *ClickResource) SetPhoneNumber(v int32)`

SetPhoneNumber sets PhoneNumber field to given value.

### HasPhoneNumber

`func (o *ClickResource) HasPhoneNumber() bool`

HasPhoneNumber returns a boolean if a field has been set.

### SetPhoneNumberNil

`func (o *ClickResource) SetPhoneNumberNil(b bool)`

 SetPhoneNumberNil sets the value for PhoneNumber to be an explicit nil

### UnsetPhoneNumber
`func (o *ClickResource) UnsetPhoneNumber()`

UnsetPhoneNumber ensures that no value is present for PhoneNumber, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


