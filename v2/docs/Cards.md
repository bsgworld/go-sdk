# Cards

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cards** | [**[]Card**](Card.md) | The array contains information about the card. The maximum number of cards is 5. Messages with one card are called “Single card”, messages with 2 or more cards are called “Carousel”. Depending on the chosen tariff, the number of cards may be limited (for example, you can send only Single cards).  Details will be provided by manager. | 

## Methods

### NewCards

`func NewCards(cards []Card, ) *Cards`

NewCards instantiates a new Cards object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCardsWithDefaults

`func NewCardsWithDefaults() *Cards`

NewCardsWithDefaults instantiates a new Cards object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCards

`func (o *Cards) GetCards() []Card`

GetCards returns the Cards field if non-nil, zero value otherwise.

### GetCardsOk

`func (o *Cards) GetCardsOk() (*[]Card, bool)`

GetCardsOk returns a tuple with the Cards field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCards

`func (o *Cards) SetCards(v []Card)`

SetCards sets Cards field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


