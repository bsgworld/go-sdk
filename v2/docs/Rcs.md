# Rcs

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cards** | [**[]Card**](Card.md) | The array contains information about the card. The maximum number of cards is 5. Messages with one card are called “Single card”, messages with 2 or more cards are called “Carousel”. Depending on the chosen tariff, the number of cards may be limited (for example, you can send only Single cards).  Details will be provided by manager. | 
**Text** | **string** | It is specified only for the “text” message type. RCS message text is  up to 160 characters. Can contain emojis (character count for emojis according to UTF-16 code points. Simple emojis take 2 code points, complex emojis take 4, Cyrillic emojis take 1). If the message contains a link in the format http://nosms.cc/XXXX, the System will generate an Unsubscribe link while sending the message | 
**Sender** | **string** | The name of the agent used to send the rcs message | 

## Methods

### NewRcs

`func NewRcs(cards []Card, text string, sender string, ) *Rcs`

NewRcs instantiates a new Rcs object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRcsWithDefaults

`func NewRcsWithDefaults() *Rcs`

NewRcsWithDefaults instantiates a new Rcs object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCards

`func (o *Rcs) GetCards() []Card`

GetCards returns the Cards field if non-nil, zero value otherwise.

### GetCardsOk

`func (o *Rcs) GetCardsOk() (*[]Card, bool)`

GetCardsOk returns a tuple with the Cards field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCards

`func (o *Rcs) SetCards(v []Card)`

SetCards sets Cards field to given value.


### GetText

`func (o *Rcs) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *Rcs) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *Rcs) SetText(v string)`

SetText sets Text field to given value.


### GetSender

`func (o *Rcs) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *Rcs) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *Rcs) SetSender(v string)`

SetSender sets Sender field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


