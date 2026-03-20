# \StoplistAddAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**StoplistAdd**](StoplistAddAPI.md#StoplistAdd) | **Post** /api/stoplist/attach | Add contacts to stop list



## StoplistAdd

> StoplistAdd200Response StoplistAdd(ctx).StoplistAddRequest(stoplistAddRequest).Execute()

Add contacts to stop list



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
	stoplistAddRequest := *openapiclient.NewStoplistAddRequest([]int32{int32(380661231231)}, []string{"Types_example"}) // StoplistAddRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StoplistAddAPI.StoplistAdd(context.Background()).StoplistAddRequest(stoplistAddRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StoplistAddAPI.StoplistAdd``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StoplistAdd`: StoplistAdd200Response
	fmt.Fprintf(os.Stdout, "Response from `StoplistAddAPI.StoplistAdd`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiStoplistAddRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **stoplistAddRequest** | [**StoplistAddRequest**](StoplistAddRequest.md) |  | 

### Return type

[**StoplistAdd200Response**](StoplistAdd200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

