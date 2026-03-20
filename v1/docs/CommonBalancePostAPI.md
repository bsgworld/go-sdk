# \CommonBalancePostAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CommonGetBalancePost**](CommonBalancePostAPI.md#CommonGetBalancePost) | **Post** /rest/common/balance | Get account balance (POST)



## CommonGetBalancePost

> BalanceResponse CommonGetBalancePost(ctx).Execute()

Get account balance (POST)



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
	resp, r, err := apiClient.CommonBalancePostAPI.CommonGetBalancePost(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CommonBalancePostAPI.CommonGetBalancePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CommonGetBalancePost`: BalanceResponse
	fmt.Fprintf(os.Stdout, "Response from `CommonBalancePostAPI.CommonGetBalancePost`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiCommonGetBalancePostRequest struct via the builder pattern


### Return type

[**BalanceResponse**](BalanceResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

