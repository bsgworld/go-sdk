# \ShortUrlsDomainCreateAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ShortUrlsDomainCreate**](ShortUrlsDomainCreateAPI.md#ShortUrlsDomainCreate) | **Post** /api/short-url/domains | Add domain



## ShortUrlsDomainCreate

> ShortUrlsDomainCreate201Response ShortUrlsDomainCreate(ctx).DomainStoreRequest(domainStoreRequest).Execute()

Add domain

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
	domainStoreRequest := *openapiclient.NewDomainStoreRequest("short.ai", openapiclient.ShortDomainSlugType("random")) // DomainStoreRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShortUrlsDomainCreateAPI.ShortUrlsDomainCreate(context.Background()).DomainStoreRequest(domainStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShortUrlsDomainCreateAPI.ShortUrlsDomainCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShortUrlsDomainCreate`: ShortUrlsDomainCreate201Response
	fmt.Fprintf(os.Stdout, "Response from `ShortUrlsDomainCreateAPI.ShortUrlsDomainCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiShortUrlsDomainCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domainStoreRequest** | [**DomainStoreRequest**](DomainStoreRequest.md) |  | 

### Return type

[**ShortUrlsDomainCreate201Response**](ShortUrlsDomainCreate201Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

