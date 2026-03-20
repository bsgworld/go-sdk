# \ViberStatusByRefAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ViberGetStatusByExtId**](ViberStatusByRefAPI.md#ViberGetStatusByExtId) | **Get** /rest/viber/reference/{reference} | Get Viber status by reference



## ViberGetStatusByExtId

> ViberStatusResponse ViberGetStatusByExtId(ctx, reference).Execute()

Get Viber status by reference



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
	resp, r, err := apiClient.ViberStatusByRefAPI.ViberGetStatusByExtId(context.Background(), reference).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ViberStatusByRefAPI.ViberGetStatusByExtId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ViberGetStatusByExtId`: ViberStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `ViberStatusByRefAPI.ViberGetStatusByExtId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**reference** | **string** | External reference ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiViberGetStatusByExtIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ViberStatusResponse**](ViberStatusResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

