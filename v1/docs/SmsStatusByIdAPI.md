# \SmsStatusByIdAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SmsGetStatusById**](SmsStatusByIdAPI.md#SmsGetStatusById) | **Get** /rest/sms/{id} | Get SMS status by ID



## SmsGetStatusById

> SmsStatusResponse SmsGetStatusById(ctx, id).Execute()

Get SMS status by ID



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
	id := "123456" // string | Message ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmsStatusByIdAPI.SmsGetStatusById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmsStatusByIdAPI.SmsGetStatusById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SmsGetStatusById`: SmsStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `SmsStatusByIdAPI.SmsGetStatusById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Message ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiSmsGetStatusByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SmsStatusResponse**](SmsStatusResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

