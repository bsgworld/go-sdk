# \ViberPricesAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ViberGetPrices**](ViberPricesAPI.md#ViberGetPrices) | **Get** /rest/viber/prices/{tariff} | Get Viber pricing



## ViberGetPrices

> ViberPricesResponse ViberGetPrices(ctx, tariff).Execute()

Get Viber pricing



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
	tariff := int32(0) // int32 | Tariff code (0-9). Use 0 or omit to use account default tariff. (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ViberPricesAPI.ViberGetPrices(context.Background(), tariff).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ViberPricesAPI.ViberGetPrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ViberGetPrices`: ViberPricesResponse
	fmt.Fprintf(os.Stdout, "Response from `ViberPricesAPI.ViberGetPrices`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tariff** | **int32** | Tariff code (0-9). Use 0 or omit to use account default tariff. | [default to 0]

### Other Parameters

Other parameters are passed through a pointer to a apiViberGetPricesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ViberPricesResponse**](ViberPricesResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

