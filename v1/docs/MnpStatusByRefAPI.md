# \MnpStatusByRefAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**MnpGetStatusByExtId**](MnpStatusByRefAPI.md#MnpGetStatusByExtId) | **Get** /rest/mnp/reference/{reference} | Get MNP result by reference



## MnpGetStatusByExtId

> MnpStatusResponse MnpGetStatusByExtId(ctx, reference).Execute()

Get MNP result by reference



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
	reference := "unique_ref_123" // string | External reference ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MnpStatusByRefAPI.MnpGetStatusByExtId(context.Background(), reference).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MnpStatusByRefAPI.MnpGetStatusByExtId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MnpGetStatusByExtId`: MnpStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `MnpStatusByRefAPI.MnpGetStatusByExtId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**reference** | **string** | External reference ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiMnpGetStatusByExtIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MnpStatusResponse**](MnpStatusResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

