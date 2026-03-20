# ViberPricesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Messages** | [**[]ViberPricesRequestMessagesInner**](ViberPricesRequestMessagesInner.md) | Array of Viber messages for price calculation | 

## Methods

### NewViberPricesRequest

`func NewViberPricesRequest(messages []ViberPricesRequestMessagesInner, ) *ViberPricesRequest`

NewViberPricesRequest instantiates a new ViberPricesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberPricesRequestWithDefaults

`func NewViberPricesRequestWithDefaults() *ViberPricesRequest`

NewViberPricesRequestWithDefaults instantiates a new ViberPricesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessages

`func (o *ViberPricesRequest) GetMessages() []ViberPricesRequestMessagesInner`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *ViberPricesRequest) GetMessagesOk() (*[]ViberPricesRequestMessagesInner, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *ViberPricesRequest) SetMessages(v []ViberPricesRequestMessagesInner)`

SetMessages sets Messages field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


