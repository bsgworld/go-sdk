# \RcsSingleAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RcsSingle**](RcsSingleAPI.md#RcsSingle) | **Post** /api/messages/rcs/send | Send single RCS message



## RcsSingle

> MessageResponse RcsSingle(ctx).RcsMessage(rcsMessage).Execute()

Send single RCS message



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
	rcsMessage := *openapiclient.NewRcsMessage(*openapiclient.NewPhone("380661231231"), "Sender_example", *openapiclient.NewOptions([]openapiclient.Card{*openapiclient.NewCard()}, "Hello! ☺️")) // RcsMessage | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RcsSingleAPI.RcsSingle(context.Background()).RcsMessage(rcsMessage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RcsSingleAPI.RcsSingle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RcsSingle`: MessageResponse
	fmt.Fprintf(os.Stdout, "Response from `RcsSingleAPI.RcsSingle`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRcsSingleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rcsMessage** | [**RcsMessage**](RcsMessage.md) |  | 

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

