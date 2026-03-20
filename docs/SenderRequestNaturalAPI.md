# \SenderRequestNaturalAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SenderRequestNatural**](SenderRequestNaturalAPI.md#SenderRequestNatural) | **Post** /api/senders/requests/natural | Sender registration by an individual



## SenderRequestNatural

> SenderRequestNatural201Response SenderRequestNatural(ctx).SenderRequestNaturalRequest(senderRequestNaturalRequest).Execute()

Sender registration by an individual



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/bsgworld/go-sdk"
)

func main() {
	senderRequestNaturalRequest := *openapiclient.NewSenderRequestNaturalRequest("UA", openapiclient.SenderRequestType("sms"), "testsms", "Oleksander Melnik", "31316718", "Flower selling", "notifications for customers") // SenderRequestNaturalRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SenderRequestNaturalAPI.SenderRequestNatural(context.Background()).SenderRequestNaturalRequest(senderRequestNaturalRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SenderRequestNaturalAPI.SenderRequestNatural``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SenderRequestNatural`: SenderRequestNatural201Response
	fmt.Fprintf(os.Stdout, "Response from `SenderRequestNaturalAPI.SenderRequestNatural`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSenderRequestNaturalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **senderRequestNaturalRequest** | [**SenderRequestNaturalRequest**](SenderRequestNaturalRequest.md) |  | 

### Return type

[**SenderRequestNatural201Response**](SenderRequestNatural201Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

