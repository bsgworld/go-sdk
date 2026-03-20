# \MnpStatusByIdAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**MnpGetStatusById**](MnpStatusByIdAPI.md#MnpGetStatusById) | **Get** /rest/mnp/{id} | Get MNP result by ID



## MnpGetStatusById

> MnpStatusResponse MnpGetStatusById(ctx, id).Execute()

Get MNP result by ID



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
	id := "123456" // string | Internal record ID 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MnpStatusByIdAPI.MnpGetStatusById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MnpStatusByIdAPI.MnpGetStatusById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MnpGetStatusById`: MnpStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `MnpStatusByIdAPI.MnpGetStatusById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Internal record ID  | 

### Other Parameters

Other parameters are passed through a pointer to a apiMnpGetStatusByIdRequest struct via the builder pattern


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

