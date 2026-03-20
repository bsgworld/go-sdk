# \ShortUrlsDomainAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ShortUrlsDomain**](ShortUrlsDomainAPI.md#ShortUrlsDomain) | **Get** /api/short-url/domains/{uuid} | Get domain by uuid



## ShortUrlsDomain

> ShortUrlsDomain200Response ShortUrlsDomain(ctx, uuid).Execute()

Get domain by uuid

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
	uuid := "db05af9e-107e-4ed6-b1ac-a373d90109c8" // string | Uuid of entity

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShortUrlsDomainAPI.ShortUrlsDomain(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShortUrlsDomainAPI.ShortUrlsDomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShortUrlsDomain`: ShortUrlsDomain200Response
	fmt.Fprintf(os.Stdout, "Response from `ShortUrlsDomainAPI.ShortUrlsDomain`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Uuid of entity | 

### Other Parameters

Other parameters are passed through a pointer to a apiShortUrlsDomainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ShortUrlsDomain200Response**](ShortUrlsDomain200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

