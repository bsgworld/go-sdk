# \StoplistItemsAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**StoplistItems**](StoplistItemsAPI.md#StoplistItems) | **Get** /api/stoplist | List the contacts of stop lists



## StoplistItems

> StoplistItems200Response StoplistItems(ctx).PageOffset(pageOffset).PageLimit(pageLimit).Type_(type_).Execute()

List the contacts of stop lists



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
	pageLimit := int32(50) // int32 | The number of items in the response (optional) (default to 20)
	type_ := "type__example" // string | Specify the type of the stop list for which we need to return the contact list. If the stop list type is not specified, the method will return data for all the stop list types (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StoplistItemsAPI.StoplistItems(context.Background()).PageOffset(pageOffset).PageLimit(pageLimit).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StoplistItemsAPI.StoplistItems``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StoplistItems`: StoplistItems200Response
	fmt.Fprintf(os.Stdout, "Response from `StoplistItemsAPI.StoplistItems`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiStoplistItemsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pageOffset** | **int32** |  | [default to 0]
 **pageLimit** | **int32** | The number of items in the response | [default to 20]
 **type_** | **string** | Specify the type of the stop list for which we need to return the contact list. If the stop list type is not specified, the method will return data for all the stop list types | 

### Return type

[**StoplistItems200Response**](StoplistItems200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

