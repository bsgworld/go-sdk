# \HlrPricesAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**HlrGetPrices**](HlrPricesAPI.md#HlrGetPrices) | **Get** /rest/hlr/prices | Get HLR pricing



## HlrGetPrices

> HlrPricesResponse HlrGetPrices(ctx).Execute()

Get HLR pricing



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
	resp, r, err := apiClient.HlrPricesAPI.HlrGetPrices(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HlrPricesAPI.HlrGetPrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HlrGetPrices`: HlrPricesResponse
	fmt.Fprintf(os.Stdout, "Response from `HlrPricesAPI.HlrGetPrices`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiHlrGetPricesRequest struct via the builder pattern


### Return type

[**HlrPricesResponse**](HlrPricesResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

