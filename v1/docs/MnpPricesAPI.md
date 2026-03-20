# \MnpPricesAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**MnpGetPrices**](MnpPricesAPI.md#MnpGetPrices) | **Get** /rest/mnp/prices | Get MNP pricing



## MnpGetPrices

> MnpPricesResponse MnpGetPrices(ctx).Execute()

Get MNP pricing



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
	resp, r, err := apiClient.MnpPricesAPI.MnpGetPrices(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MnpPricesAPI.MnpGetPrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MnpGetPrices`: MnpPricesResponse
	fmt.Fprintf(os.Stdout, "Response from `MnpPricesAPI.MnpGetPrices`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiMnpGetPricesRequest struct via the builder pattern


### Return type

[**MnpPricesResponse**](MnpPricesResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

