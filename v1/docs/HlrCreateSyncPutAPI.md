# \HlrCreateSyncPutAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**HlrCreateObjectsSyncPut**](HlrCreateSyncPutAPI.md#HlrCreateObjectsSyncPut) | **Put** /rest/hlr/check | Perform synchronous HLR lookup (PUT)



## HlrCreateObjectsSyncPut

> HlrSyncResponse HlrCreateObjectsSyncPut(ctx).HlrSyncRequest(hlrSyncRequest).Execute()

Perform synchronous HLR lookup (PUT)



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
	hlrSyncRequest := *openapiclient.NewHlrSyncRequest("380953227271") // HlrSyncRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HlrCreateSyncPutAPI.HlrCreateObjectsSyncPut(context.Background()).HlrSyncRequest(hlrSyncRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HlrCreateSyncPutAPI.HlrCreateObjectsSyncPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HlrCreateObjectsSyncPut`: HlrSyncResponse
	fmt.Fprintf(os.Stdout, "Response from `HlrCreateSyncPutAPI.HlrCreateObjectsSyncPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiHlrCreateObjectsSyncPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **hlrSyncRequest** | [**HlrSyncRequest**](HlrSyncRequest.md) |  | 

### Return type

[**HlrSyncResponse**](HlrSyncResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

