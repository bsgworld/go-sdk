# \StoplistRemoveAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**StoplistRemove**](StoplistRemoveAPI.md#StoplistRemove) | **Post** /api/stoplist/detach | Remove contacts from stop list



## StoplistRemove

> map[string]interface{} StoplistRemove(ctx).StoplistRemoveRequest(stoplistRemoveRequest).Execute()

Remove contacts from stop list



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
	stoplistRemoveRequest := *openapiclient.NewStoplistRemoveRequest([]int32{int32(9392897)}, []string{"Types_example"}) // StoplistRemoveRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StoplistRemoveAPI.StoplistRemove(context.Background()).StoplistRemoveRequest(stoplistRemoveRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StoplistRemoveAPI.StoplistRemove``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StoplistRemove`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `StoplistRemoveAPI.StoplistRemove`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiStoplistRemoveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stoplistRemoveRequest** | [**StoplistRemoveRequest**](StoplistRemoveRequest.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

