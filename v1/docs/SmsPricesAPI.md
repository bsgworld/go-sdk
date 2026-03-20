# \SmsPricesAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SmsGetPrices**](SmsPricesAPI.md#SmsGetPrices) | **Get** /rest/sms/prices | Get SMS pricing



## SmsGetPrices

> SmsPricesListResponse SmsGetPrices(ctx).Execute()

Get SMS pricing



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
	resp, r, err := apiClient.SmsPricesAPI.SmsGetPrices(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmsPricesAPI.SmsGetPrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SmsGetPrices`: SmsPricesListResponse
	fmt.Fprintf(os.Stdout, "Response from `SmsPricesAPI.SmsGetPrices`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSmsGetPricesRequest struct via the builder pattern


### Return type

[**SmsPricesListResponse**](SmsPricesListResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

