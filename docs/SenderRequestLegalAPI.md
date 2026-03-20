# \SenderRequestLegalAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SenderRequestLegal**](SenderRequestLegalAPI.md#SenderRequestLegal) | **Post** /api/senders/requests/legal | Sender registration by a legal entity



## SenderRequestLegal

> SenderRequestLegal201Response SenderRequestLegal(ctx).SenderRequestLegalRequest(senderRequestLegalRequest).Execute()

Sender registration by a legal entity



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
	senderRequestLegalRequest := *openapiclient.NewSenderRequestLegalRequest("UA", openapiclient.SenderRequestType("sms"), "testsms", "31316718", "13167116014", "Flower selling", "notifications for customers") // SenderRequestLegalRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SenderRequestLegalAPI.SenderRequestLegal(context.Background()).SenderRequestLegalRequest(senderRequestLegalRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SenderRequestLegalAPI.SenderRequestLegal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SenderRequestLegal`: SenderRequestLegal201Response
	fmt.Fprintf(os.Stdout, "Response from `SenderRequestLegalAPI.SenderRequestLegal`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSenderRequestLegalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **senderRequestLegalRequest** | [**SenderRequestLegalRequest**](SenderRequestLegalRequest.md) |  | 

### Return type

[**SenderRequestLegal201Response**](SenderRequestLegal201Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

