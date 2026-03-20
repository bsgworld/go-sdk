# \MnpSyncCreateAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**MnpSyncCreateObjects**](MnpSyncCreateAPI.md#MnpSyncCreateObjects) | **Post** /rest/mnp-sync/create | Perform synchronous MNP lookup



## MnpSyncCreateObjects

> MnpCreateResponse MnpSyncCreateObjects(ctx).Msisdn(msisdn).Tariff(tariff).MnpCreateRequest(mnpCreateRequest).Execute()

Perform synchronous MNP lookup



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
	msisdn := "380953227271" // string | Phone number in international format (alternative to JSON body) (optional)
	tariff := int32(5) // int32 | Tariff code (optional, uses default if not provided) (optional)
	mnpCreateRequest := openapiclient.MnpCreateRequest{MnpCreateRequestOneOf: openapiclient.NewMnpCreateRequestOneOf("380953227271")} // MnpCreateRequest | JSON payload for batch requests or alternative to query parameters (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MnpSyncCreateAPI.MnpSyncCreateObjects(context.Background()).Msisdn(msisdn).Tariff(tariff).MnpCreateRequest(mnpCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MnpSyncCreateAPI.MnpSyncCreateObjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MnpSyncCreateObjects`: MnpCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `MnpSyncCreateAPI.MnpSyncCreateObjects`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMnpSyncCreateObjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **msisdn** | **string** | Phone number in international format (alternative to JSON body) | 
 **tariff** | **int32** | Tariff code (optional, uses default if not provided) | 
 **mnpCreateRequest** | [**MnpCreateRequest**](MnpCreateRequest.md) | JSON payload for batch requests or alternative to query parameters | 

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

