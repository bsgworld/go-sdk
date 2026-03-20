# \SmsTaskStatusAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SmsGetTaskStatus**](SmsTaskStatusAPI.md#SmsGetTaskStatus) | **Get** /rest/sms/task/{taskId} | Get task status



## SmsGetTaskStatus

> SmsTaskStatusResponse SmsGetTaskStatus(ctx, taskId).Execute()

Get task status



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
	taskId := "123" // string | Task ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmsTaskStatusAPI.SmsGetTaskStatus(context.Background(), taskId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmsTaskStatusAPI.SmsGetTaskStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SmsGetTaskStatus`: SmsTaskStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `SmsTaskStatusAPI.SmsGetTaskStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**taskId** | **string** | Task ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiSmsGetTaskStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SmsTaskStatusResponse**](SmsTaskStatusResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

