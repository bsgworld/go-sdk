# \Sms2waySendersAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SmsGet2WaySenders**](Sms2waySendersAPI.md#SmsGet2WaySenders) | **Get** /rest/sms/2waySenders | Get 2-way senders



## SmsGet2WaySenders

> SuccessResponse SmsGet2WaySenders(ctx).Execute()

Get 2-way senders



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.Sms2waySendersAPI.SmsGet2WaySenders(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `Sms2waySendersAPI.SmsGet2WaySenders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SmsGet2WaySenders`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `Sms2waySendersAPI.SmsGet2WaySenders`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSmsGet2WaySendersRequest struct via the builder pattern


### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

