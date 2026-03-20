# \ShortUrlsLinkDeleteAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ShortUrlsLinkDelete**](ShortUrlsLinkDeleteAPI.md#ShortUrlsLinkDelete) | **Delete** /api/short-url/links/{uuid} | Remove short link



## ShortUrlsLinkDelete

> interface{} ShortUrlsLinkDelete(ctx, uuid).Execute()

Remove short link



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShortUrlsLinkDeleteAPI.ShortUrlsLinkDelete(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShortUrlsLinkDeleteAPI.ShortUrlsLinkDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShortUrlsLinkDelete`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `ShortUrlsLinkDeleteAPI.ShortUrlsLinkDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Uuid of entity | 

### Other Parameters

Other parameters are passed through a pointer to a apiShortUrlsLinkDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**interface{}**

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

