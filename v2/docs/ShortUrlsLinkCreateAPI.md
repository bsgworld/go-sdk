# \ShortUrlsLinkCreateAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ShortUrlsLinkCreate**](ShortUrlsLinkCreateAPI.md#ShortUrlsLinkCreate) | **Post** /api/short-url/links | Create short link



## ShortUrlsLinkCreate

> ShortUrlsLinkCreate201Response ShortUrlsLinkCreate(ctx).LinkStoreRequest(linkStoreRequest).Execute()

Create short link



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
	linkStoreRequest := *openapiclient.NewLinkStoreRequest("14726feb-acfc-40fc-bebc-2e95bb0c913d", "https://app.bsg.world") // LinkStoreRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShortUrlsLinkCreateAPI.ShortUrlsLinkCreate(context.Background()).LinkStoreRequest(linkStoreRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShortUrlsLinkCreateAPI.ShortUrlsLinkCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShortUrlsLinkCreate`: ShortUrlsLinkCreate201Response
	fmt.Fprintf(os.Stdout, "Response from `ShortUrlsLinkCreateAPI.ShortUrlsLinkCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiShortUrlsLinkCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **linkStoreRequest** | [**LinkStoreRequest**](LinkStoreRequest.md) |  | 

### Return type

[**ShortUrlsLinkCreate201Response**](ShortUrlsLinkCreate201Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

