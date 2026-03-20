# \SmsBalancePostAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SmsGetBalancePost**](SmsBalancePostAPI.md#SmsGetBalancePost) | **Post** /rest/sms/balance | Get account balance



## SmsGetBalancePost

> SmsBalanceResponse SmsGetBalancePost(ctx).Execute()

Get account balance



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
	resp, r, err := apiClient.SmsBalancePostAPI.SmsGetBalancePost(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmsBalancePostAPI.SmsGetBalancePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SmsGetBalancePost`: SmsBalanceResponse
	fmt.Fprintf(os.Stdout, "Response from `SmsBalancePostAPI.SmsGetBalancePost`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSmsGetBalancePostRequest struct via the builder pattern


### Return type

[**SmsBalanceResponse**](SmsBalanceResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

