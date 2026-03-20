# \HlrStatusByRefAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**HlrGetStatusByExtId**](HlrStatusByRefAPI.md#HlrGetStatusByExtId) | **Get** /rest/hlr/reference/{reference} | Get HLR result by reference



## HlrGetStatusByExtId

> HlrStatusResponse HlrGetStatusByExtId(ctx, reference).Execute()

Get HLR result by reference



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
	resp, r, err := apiClient.HlrStatusByRefAPI.HlrGetStatusByExtId(context.Background(), reference).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HlrStatusByRefAPI.HlrGetStatusByExtId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HlrGetStatusByExtId`: HlrStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `HlrStatusByRefAPI.HlrGetStatusByExtId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**reference** | **string** | External reference ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiHlrGetStatusByExtIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**HlrStatusResponse**](HlrStatusResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

