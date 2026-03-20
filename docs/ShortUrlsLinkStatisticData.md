# ShortUrlsLinkStatisticData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CountClicks** | Pointer to **int32** | Number of clicks on a short link  *Please note: count of clicks updated with some latency* | [optional] 
**ShortLink** | Pointer to **string** | short link url that can be used to redirect to original link | [optional] 
**ClickDate** | Pointer to **time.Time** | Date of first click | [optional] 
**ClickId** | Pointer to **string** | click unique uuid | [optional] 
**UserAgent** | Pointer to **string** | User-agent of first click | [optional] 
**ClientIp** | Pointer to **string** | Client IP address of first click | [optional] 
**OriginalLink** | Pointer to **string** | Original link where to short link will redirect | [optional] 
**Phone** | Pointer to **NullableInt32** | Phone number without leading plus. For short links created as part of [sms campaign](#tag/Campaign-SMS) | [optional] 
**MessageId** | Pointer to **NullableInt32** | message id for short links created as part of [sms campaign](#tag/Campaign-SMS) | [optional] 
**CampaignId** | Pointer to **int32** | campaign ID if short link is part of sms campaign.  Campaign allow send messages to all the leads with different short link for each lead that follows to the same original link | [optional] 
**IsHuman** | Pointer to **bool** | We use some heuristics to determine is it real human or looks like bot | [optional] 

## Methods

### NewShortUrlsLinkStatisticData

`func NewShortUrlsLinkStatisticData() *ShortUrlsLinkStatisticData`

NewShortUrlsLinkStatisticData instantiates a new ShortUrlsLinkStatisticData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShortUrlsLinkStatisticDataWithDefaults

`func NewShortUrlsLinkStatisticDataWithDefaults() *ShortUrlsLinkStatisticData`

NewShortUrlsLinkStatisticDataWithDefaults instantiates a new ShortUrlsLinkStatisticData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCountClicks

`func (o *ShortUrlsLinkStatisticData) GetCountClicks() int32`

GetCountClicks returns the CountClicks field if non-nil, zero value otherwise.

### GetCountClicksOk

`func (o *ShortUrlsLinkStatisticData) GetCountClicksOk() (*int32, bool)`

GetCountClicksOk returns a tuple with the CountClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountClicks

`func (o *ShortUrlsLinkStatisticData) SetCountClicks(v int32)`

SetCountClicks sets CountClicks field to given value.

### HasCountClicks

`func (o *ShortUrlsLinkStatisticData) HasCountClicks() bool`

HasCountClicks returns a boolean if a field has been set.

### GetShortLink

`func (o *ShortUrlsLinkStatisticData) GetShortLink() string`

GetShortLink returns the ShortLink field if non-nil, zero value otherwise.

### GetShortLinkOk

`func (o *ShortUrlsLinkStatisticData) GetShortLinkOk() (*string, bool)`

GetShortLinkOk returns a tuple with the ShortLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortLink

`func (o *ShortUrlsLinkStatisticData) SetShortLink(v string)`

SetShortLink sets ShortLink field to given value.

### HasShortLink

`func (o *ShortUrlsLinkStatisticData) HasShortLink() bool`

HasShortLink returns a boolean if a field has been set.

### GetClickDate

`func (o *ShortUrlsLinkStatisticData) GetClickDate() time.Time`

GetClickDate returns the ClickDate field if non-nil, zero value otherwise.

### GetClickDateOk

`func (o *ShortUrlsLinkStatisticData) GetClickDateOk() (*time.Time, bool)`

GetClickDateOk returns a tuple with the ClickDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClickDate

`func (o *ShortUrlsLinkStatisticData) SetClickDate(v time.Time)`

SetClickDate sets ClickDate field to given value.

### HasClickDate

`func (o *ShortUrlsLinkStatisticData) HasClickDate() bool`

HasClickDate returns a boolean if a field has been set.

### GetClickId

`func (o *ShortUrlsLinkStatisticData) GetClickId() string`

GetClickId returns the ClickId field if non-nil, zero value otherwise.

### GetClickIdOk

`func (o *ShortUrlsLinkStatisticData) GetClickIdOk() (*string, bool)`

GetClickIdOk returns a tuple with the ClickId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClickId

`func (o *ShortUrlsLinkStatisticData) SetClickId(v string)`

SetClickId sets ClickId field to given value.

### HasClickId

`func (o *ShortUrlsLinkStatisticData) HasClickId() bool`

HasClickId returns a boolean if a field has been set.

### GetUserAgent

`func (o *ShortUrlsLinkStatisticData) GetUserAgent() string`

GetUserAgent returns the UserAgent field if non-nil, zero value otherwise.

### GetUserAgentOk

`func (o *ShortUrlsLinkStatisticData) GetUserAgentOk() (*string, bool)`

GetUserAgentOk returns a tuple with the UserAgent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserAgent

`func (o *ShortUrlsLinkStatisticData) SetUserAgent(v string)`

SetUserAgent sets UserAgent field to given value.

### HasUserAgent

`func (o *ShortUrlsLinkStatisticData) HasUserAgent() bool`

HasUserAgent returns a boolean if a field has been set.

### GetClientIp

`func (o *ShortUrlsLinkStatisticData) GetClientIp() string`

GetClientIp returns the ClientIp field if non-nil, zero value otherwise.

### GetClientIpOk

`func (o *ShortUrlsLinkStatisticData) GetClientIpOk() (*string, bool)`

GetClientIpOk returns a tuple with the ClientIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientIp

`func (o *ShortUrlsLinkStatisticData) SetClientIp(v string)`

SetClientIp sets ClientIp field to given value.

### HasClientIp

`func (o *ShortUrlsLinkStatisticData) HasClientIp() bool`

HasClientIp returns a boolean if a field has been set.

### GetOriginalLink

`func (o *ShortUrlsLinkStatisticData) GetOriginalLink() string`

GetOriginalLink returns the OriginalLink field if non-nil, zero value otherwise.

### GetOriginalLinkOk

`func (o *ShortUrlsLinkStatisticData) GetOriginalLinkOk() (*string, bool)`

GetOriginalLinkOk returns a tuple with the OriginalLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalLink

`func (o *ShortUrlsLinkStatisticData) SetOriginalLink(v string)`

SetOriginalLink sets OriginalLink field to given value.

### HasOriginalLink

`func (o *ShortUrlsLinkStatisticData) HasOriginalLink() bool`

HasOriginalLink returns a boolean if a field has been set.

### GetPhone

`func (o *ShortUrlsLinkStatisticData) GetPhone() int32`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *ShortUrlsLinkStatisticData) GetPhoneOk() (*int32, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *ShortUrlsLinkStatisticData) SetPhone(v int32)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *ShortUrlsLinkStatisticData) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *ShortUrlsLinkStatisticData) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *ShortUrlsLinkStatisticData) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetMessageId

`func (o *ShortUrlsLinkStatisticData) GetMessageId() int32`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *ShortUrlsLinkStatisticData) GetMessageIdOk() (*int32, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *ShortUrlsLinkStatisticData) SetMessageId(v int32)`

SetMessageId sets MessageId field to given value.

### HasMessageId

`func (o *ShortUrlsLinkStatisticData) HasMessageId() bool`

HasMessageId returns a boolean if a field has been set.

### SetMessageIdNil

`func (o *ShortUrlsLinkStatisticData) SetMessageIdNil(b bool)`

 SetMessageIdNil sets the value for MessageId to be an explicit nil

### UnsetMessageId
`func (o *ShortUrlsLinkStatisticData) UnsetMessageId()`

UnsetMessageId ensures that no value is present for MessageId, not even an explicit nil
### GetCampaignId

`func (o *ShortUrlsLinkStatisticData) GetCampaignId() int32`

GetCampaignId returns the CampaignId field if non-nil, zero value otherwise.

### GetCampaignIdOk

`func (o *ShortUrlsLinkStatisticData) GetCampaignIdOk() (*int32, bool)`

GetCampaignIdOk returns a tuple with the CampaignId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignId

`func (o *ShortUrlsLinkStatisticData) SetCampaignId(v int32)`

SetCampaignId sets CampaignId field to given value.

### HasCampaignId

`func (o *ShortUrlsLinkStatisticData) HasCampaignId() bool`

HasCampaignId returns a boolean if a field has been set.

### GetIsHuman

`func (o *ShortUrlsLinkStatisticData) GetIsHuman() bool`

GetIsHuman returns the IsHuman field if non-nil, zero value otherwise.

### GetIsHumanOk

`func (o *ShortUrlsLinkStatisticData) GetIsHumanOk() (*bool, bool)`

GetIsHumanOk returns a tuple with the IsHuman field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsHuman

`func (o *ShortUrlsLinkStatisticData) SetIsHuman(v bool)`

SetIsHuman sets IsHuman field to given value.

### HasIsHuman

`func (o *ShortUrlsLinkStatisticData) HasIsHuman() bool`

HasIsHuman returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


