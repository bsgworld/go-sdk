# \AccountTariffsAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AccountTariffs**](AccountTariffsAPI.md#AccountTariffs) | **Get** /api/accounts/tariff | Get tariffs



## AccountTariffs

> AccountTariffs200Response AccountTariffs(ctx).PageOffset(pageOffset).PageLimit(pageLimit).Execute()

Get tariffs



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
	pageOffset := int32(56) // int32 |  (optional) (default to 0)
	pageLimit := int32(50) // int32 | The number of items in the response (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountTariffsAPI.AccountTariffs(context.Background()).PageOffset(pageOffset).PageLimit(pageLimit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountTariffsAPI.AccountTariffs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountTariffs`: AccountTariffs200Response
	fmt.Fprintf(os.Stdout, "Response from `AccountTariffsAPI.AccountTariffs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAccountTariffsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pageOffset** | **int32** |  | [default to 0]
 **pageLimit** | **int32** | The number of items in the response | [default to 50]

### Return type

[**AccountTariffs200Response**](AccountTariffs200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

