# \HlrCreatePutAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**HlrCreateObjectsPut**](HlrCreatePutAPI.md#HlrCreateObjectsPut) | **Put** /rest/hlr/create | Perform HLR lookup (PUT)



## HlrCreateObjectsPut

> HlrCreateResponse HlrCreateObjectsPut(ctx).HlrCreateRequest(hlrCreateRequest).Execute()

Perform HLR lookup (PUT)



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
	hlrCreateRequest := openapiclient.HlrCreateRequest{HlrCreateRequestOneOf: openapiclient.NewHlrCreateRequestOneOf("380953227271")} // HlrCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HlrCreatePutAPI.HlrCreateObjectsPut(context.Background()).HlrCreateRequest(hlrCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HlrCreatePutAPI.HlrCreateObjectsPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HlrCreateObjectsPut`: HlrCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `HlrCreatePutAPI.HlrCreateObjectsPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiHlrCreateObjectsPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **hlrCreateRequest** | [**HlrCreateRequest**](HlrCreateRequest.md) |  | 

### Return type

[**HlrCreateResponse**](HlrCreateResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

