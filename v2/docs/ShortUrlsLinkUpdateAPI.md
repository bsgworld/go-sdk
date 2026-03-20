# \ShortUrlsLinkUpdateAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ShortUrlsLinkUpdate**](ShortUrlsLinkUpdateAPI.md#ShortUrlsLinkUpdate) | **Put** /api/short-url/links/{uuid} | Update short link



## ShortUrlsLinkUpdate

> ShortUrlsLinkUpdate200Response ShortUrlsLinkUpdate(ctx, uuid).LinkUpdateRequest(linkUpdateRequest).Execute()

Update short link



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
	linkUpdateRequest := *openapiclient.NewLinkUpdateRequest() // LinkUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShortUrlsLinkUpdateAPI.ShortUrlsLinkUpdate(context.Background(), uuid).LinkUpdateRequest(linkUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShortUrlsLinkUpdateAPI.ShortUrlsLinkUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShortUrlsLinkUpdate`: ShortUrlsLinkUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `ShortUrlsLinkUpdateAPI.ShortUrlsLinkUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Uuid of entity | 

### Other Parameters

Other parameters are passed through a pointer to a apiShortUrlsLinkUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **linkUpdateRequest** | [**LinkUpdateRequest**](LinkUpdateRequest.md) |  | 

### Return type

[**ShortUrlsLinkUpdate200Response**](ShortUrlsLinkUpdate200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

