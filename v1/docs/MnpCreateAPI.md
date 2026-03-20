# \MnpCreateAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**MnpCreateObjects**](MnpCreateAPI.md#MnpCreateObjects) | **Post** /rest/mnp/create | Perform MNP lookup



## MnpCreateObjects

> MnpCreateResponse MnpCreateObjects(ctx).MnpCreateRequest(mnpCreateRequest).Execute()

Perform MNP lookup



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
	mnpCreateRequest := openapiclient.MnpCreateRequest{MnpCreateRequestOneOf: openapiclient.NewMnpCreateRequestOneOf("380953227271")} // MnpCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MnpCreateAPI.MnpCreateObjects(context.Background()).MnpCreateRequest(mnpCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MnpCreateAPI.MnpCreateObjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MnpCreateObjects`: MnpCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `MnpCreateAPI.MnpCreateObjects`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMnpCreateObjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **mnpCreateRequest** | [**MnpCreateRequest**](MnpCreateRequest.md) |  | 

### Return type

[**MnpCreateResponse**](MnpCreateResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

