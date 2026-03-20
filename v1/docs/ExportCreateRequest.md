# ExportCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MessageId** | Pointer to **[]int32** | Array of message IDs to export. If provided, ALL other parameters must be empty. | [optional] 
**Msisdn** | Pointer to **[]string** | Phone numbers in international format to filter by | [optional] 
**Originator** | Pointer to **string** | Filter by sender/originator name | [optional] 
**SourceType** | Pointer to **string** | Filter by message source type (e.g. api, smpp). Empty string &#x3D; not specified. | [optional] 
**MessageType** | Pointer to **string** | Filter by message type | [optional] 
**TimeInFrom** | Pointer to **time.Time** | Start of message received date range (ISO 8601 format) | [optional] 
**TimeInTo** | Pointer to **time.Time** | End of message received date range (must be &gt;&#x3D; time_in_from) | [optional] 
**TimeSentFrom** | Pointer to **time.Time** | Start of message sent date range (ISO 8601 format) | [optional] 
**TimeSentTo** | Pointer to **time.Time** | End of message sent date range (must be &gt;&#x3D; time_sent_from) | [optional] 
**CountryId** | Pointer to **string** | ISO 3166-1 alpha-2 country code (exactly 2 characters) | [optional] 
**SlClicks** | Pointer to **string** | Short link clicks filter value. Empty string &#x3D; not specified. | [optional] 
**SlClicksComp** | Pointer to **string** | Clicks comparison operator (&gt;, &lt;, &#x3D;, &gt;&#x3D;, &lt;&#x3D;). Empty string &#x3D; not specified. | [optional] 
**SlClicksCount** | Pointer to **string** | Clicks count comparison value. Empty string &#x3D; not specified. | [optional] 

## Methods

### NewExportCreateRequest

`func NewExportCreateRequest() *ExportCreateRequest`

NewExportCreateRequest instantiates a new ExportCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExportCreateRequestWithDefaults

`func NewExportCreateRequestWithDefaults() *ExportCreateRequest`

NewExportCreateRequestWithDefaults instantiates a new ExportCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessageId

`func (o *ExportCreateRequest) GetMessageId() []int32`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *ExportCreateRequest) GetMessageIdOk() (*[]int32, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *ExportCreateRequest) SetMessageId(v []int32)`

SetMessageId sets MessageId field to given value.

### HasMessageId

`func (o *ExportCreateRequest) HasMessageId() bool`

HasMessageId returns a boolean if a field has been set.

### GetMsisdn

`func (o *ExportCreateRequest) GetMsisdn() []string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *ExportCreateRequest) GetMsisdnOk() (*[]string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *ExportCreateRequest) SetMsisdn(v []string)`

SetMsisdn sets Msisdn field to given value.

### HasMsisdn

`func (o *ExportCreateRequest) HasMsisdn() bool`

HasMsisdn returns a boolean if a field has been set.

### GetOriginator

`func (o *ExportCreateRequest) GetOriginator() string`

GetOriginator returns the Originator field if non-nil, zero value otherwise.

### GetOriginatorOk

`func (o *ExportCreateRequest) GetOriginatorOk() (*string, bool)`

GetOriginatorOk returns a tuple with the Originator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginator

`func (o *ExportCreateRequest) SetOriginator(v string)`

SetOriginator sets Originator field to given value.

### HasOriginator

`func (o *ExportCreateRequest) HasOriginator() bool`

HasOriginator returns a boolean if a field has been set.

### GetSourceType

`func (o *ExportCreateRequest) GetSourceType() string`

GetSourceType returns the SourceType field if non-nil, zero value otherwise.

### GetSourceTypeOk

`func (o *ExportCreateRequest) GetSourceTypeOk() (*string, bool)`

GetSourceTypeOk returns a tuple with the SourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceType

`func (o *ExportCreateRequest) SetSourceType(v string)`

SetSourceType sets SourceType field to given value.

### HasSourceType

`func (o *ExportCreateRequest) HasSourceType() bool`

HasSourceType returns a boolean if a field has been set.

### GetMessageType

`func (o *ExportCreateRequest) GetMessageType() string`

GetMessageType returns the MessageType field if non-nil, zero value otherwise.

### GetMessageTypeOk

`func (o *ExportCreateRequest) GetMessageTypeOk() (*string, bool)`

GetMessageTypeOk returns a tuple with the MessageType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageType

`func (o *ExportCreateRequest) SetMessageType(v string)`

SetMessageType sets MessageType field to given value.

### HasMessageType

`func (o *ExportCreateRequest) HasMessageType() bool`

HasMessageType returns a boolean if a field has been set.

### GetTimeInFrom

`func (o *ExportCreateRequest) GetTimeInFrom() time.Time`

GetTimeInFrom returns the TimeInFrom field if non-nil, zero value otherwise.

### GetTimeInFromOk

`func (o *ExportCreateRequest) GetTimeInFromOk() (*time.Time, bool)`

GetTimeInFromOk returns a tuple with the TimeInFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeInFrom

`func (o *ExportCreateRequest) SetTimeInFrom(v time.Time)`

SetTimeInFrom sets TimeInFrom field to given value.

### HasTimeInFrom

`func (o *ExportCreateRequest) HasTimeInFrom() bool`

HasTimeInFrom returns a boolean if a field has been set.

### GetTimeInTo

`func (o *ExportCreateRequest) GetTimeInTo() time.Time`

GetTimeInTo returns the TimeInTo field if non-nil, zero value otherwise.

### GetTimeInToOk

`func (o *ExportCreateRequest) GetTimeInToOk() (*time.Time, bool)`

GetTimeInToOk returns a tuple with the TimeInTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeInTo

`func (o *ExportCreateRequest) SetTimeInTo(v time.Time)`

SetTimeInTo sets TimeInTo field to given value.

### HasTimeInTo

`func (o *ExportCreateRequest) HasTimeInTo() bool`

HasTimeInTo returns a boolean if a field has been set.

### GetTimeSentFrom

`func (o *ExportCreateRequest) GetTimeSentFrom() time.Time`

GetTimeSentFrom returns the TimeSentFrom field if non-nil, zero value otherwise.

### GetTimeSentFromOk

`func (o *ExportCreateRequest) GetTimeSentFromOk() (*time.Time, bool)`

GetTimeSentFromOk returns a tuple with the TimeSentFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSentFrom

`func (o *ExportCreateRequest) SetTimeSentFrom(v time.Time)`

SetTimeSentFrom sets TimeSentFrom field to given value.

### HasTimeSentFrom

`func (o *ExportCreateRequest) HasTimeSentFrom() bool`

HasTimeSentFrom returns a boolean if a field has been set.

### GetTimeSentTo

`func (o *ExportCreateRequest) GetTimeSentTo() time.Time`

GetTimeSentTo returns the TimeSentTo field if non-nil, zero value otherwise.

### GetTimeSentToOk

`func (o *ExportCreateRequest) GetTimeSentToOk() (*time.Time, bool)`

GetTimeSentToOk returns a tuple with the TimeSentTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSentTo

`func (o *ExportCreateRequest) SetTimeSentTo(v time.Time)`

SetTimeSentTo sets TimeSentTo field to given value.

### HasTimeSentTo

`func (o *ExportCreateRequest) HasTimeSentTo() bool`

HasTimeSentTo returns a boolean if a field has been set.

### GetCountryId

`func (o *ExportCreateRequest) GetCountryId() string`

GetCountryId returns the CountryId field if non-nil, zero value otherwise.

### GetCountryIdOk

`func (o *ExportCreateRequest) GetCountryIdOk() (*string, bool)`

GetCountryIdOk returns a tuple with the CountryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryId

`func (o *ExportCreateRequest) SetCountryId(v string)`

SetCountryId sets CountryId field to given value.

### HasCountryId

`func (o *ExportCreateRequest) HasCountryId() bool`

HasCountryId returns a boolean if a field has been set.

### GetSlClicks

`func (o *ExportCreateRequest) GetSlClicks() string`

GetSlClicks returns the SlClicks field if non-nil, zero value otherwise.

### GetSlClicksOk

`func (o *ExportCreateRequest) GetSlClicksOk() (*string, bool)`

GetSlClicksOk returns a tuple with the SlClicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlClicks

`func (o *ExportCreateRequest) SetSlClicks(v string)`

SetSlClicks sets SlClicks field to given value.

### HasSlClicks

`func (o *ExportCreateRequest) HasSlClicks() bool`

HasSlClicks returns a boolean if a field has been set.

### GetSlClicksComp

`func (o *ExportCreateRequest) GetSlClicksComp() string`

GetSlClicksComp returns the SlClicksComp field if non-nil, zero value otherwise.

### GetSlClicksCompOk

`func (o *ExportCreateRequest) GetSlClicksCompOk() (*string, bool)`

GetSlClicksCompOk returns a tuple with the SlClicksComp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlClicksComp

`func (o *ExportCreateRequest) SetSlClicksComp(v string)`

SetSlClicksComp sets SlClicksComp field to given value.

### HasSlClicksComp

`func (o *ExportCreateRequest) HasSlClicksComp() bool`

HasSlClicksComp returns a boolean if a field has been set.

### GetSlClicksCount

`func (o *ExportCreateRequest) GetSlClicksCount() string`

GetSlClicksCount returns the SlClicksCount field if non-nil, zero value otherwise.

### GetSlClicksCountOk

`func (o *ExportCreateRequest) GetSlClicksCountOk() (*string, bool)`

GetSlClicksCountOk returns a tuple with the SlClicksCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlClicksCount

`func (o *ExportCreateRequest) SetSlClicksCount(v string)`

SetSlClicksCount sets SlClicksCount field to given value.

### HasSlClicksCount

`func (o *ExportCreateRequest) HasSlClicksCount() bool`

HasSlClicksCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


