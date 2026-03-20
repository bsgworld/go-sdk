# \ShortUrlsDomainUpdateAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ShortUrlsDomainUpdate**](ShortUrlsDomainUpdateAPI.md#ShortUrlsDomainUpdate) | **Put** /api/short-url/domains/{uuid} | Update domain



## ShortUrlsDomainUpdate

> ShortUrlsDomainUpdate200Response ShortUrlsDomainUpdate(ctx, uuid).DomainUpdateRequest(domainUpdateRequest).Execute()

Update domain

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
	uuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Uuid of entity
	domainUpdateRequest := *openapiclient.NewDomainUpdateRequest() // DomainUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShortUrlsDomainUpdateAPI.ShortUrlsDomainUpdate(context.Background(), uuid).DomainUpdateRequest(domainUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShortUrlsDomainUpdateAPI.ShortUrlsDomainUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShortUrlsDomainUpdate`: ShortUrlsDomainUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `ShortUrlsDomainUpdateAPI.ShortUrlsDomainUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Uuid of entity | 

### Other Parameters

Other parameters are passed through a pointer to a apiShortUrlsDomainUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **domainUpdateRequest** | [**DomainUpdateRequest**](DomainUpdateRequest.md) |  | 

### Return type

[**ShortUrlsDomainUpdate200Response**](ShortUrlsDomainUpdate200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

