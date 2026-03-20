# \SmsBalanceAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SmsGetBalance**](SmsBalanceAPI.md#SmsGetBalance) | **Get** /rest/sms/balance | Get account balance



## SmsGetBalance

> SmsBalanceResponse SmsGetBalance(ctx).Execute()

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
	resp, r, err := apiClient.SmsBalanceAPI.SmsGetBalance(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmsBalanceAPI.SmsGetBalance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SmsGetBalance`: SmsBalanceResponse
	fmt.Fprintf(os.Stdout, "Response from `SmsBalanceAPI.SmsGetBalance`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSmsGetBalanceRequest struct via the builder pattern


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

