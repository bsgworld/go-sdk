# \MessagesAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SendMessage**](MessagesAPI.md#SendMessage) | **Post** /api/messages/send | Send single message



## SendMessage

> MessageResponse SendMessage(ctx).MessageUniversal(messageUniversal).Execute()

Send single message



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
	messageUniversal := *openapiclient.NewMessageUniversal([]string{"Channels_example"}, *openapiclient.NewPhone("380661231231")) // MessageUniversal | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessagesAPI.SendMessage(context.Background()).MessageUniversal(messageUniversal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessagesAPI.SendMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendMessage`: MessageResponse
	fmt.Fprintf(os.Stdout, "Response from `MessagesAPI.SendMessage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSendMessageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **messageUniversal** | [**MessageUniversal**](MessageUniversal.md) |  | 

### Return type

[**MessageResponse**](MessageResponse.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

