# \ShortUrlsLinksAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ShortUrlsLinks**](ShortUrlsLinksAPI.md#ShortUrlsLinks) | **Get** /api/short-url/links | List of short links



## ShortUrlsLinks

> ShortUrlsLinks200Response ShortUrlsLinks(ctx).From(from).To(to).Page(page).PerPage(perPage).Execute()

List of short links



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
	from := "2022-04-28" // string | From date
	to := "2022-04-28" // string | To date
	page := int32(56) // int32 | Get items starting from this page. (optional) (default to 1)
	perPage := int32(56) // int32 | The number of items in the page. Possible values are from 10 to 500. (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShortUrlsLinksAPI.ShortUrlsLinks(context.Background()).From(from).To(to).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShortUrlsLinksAPI.ShortUrlsLinks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShortUrlsLinks`: ShortUrlsLinks200Response
	fmt.Fprintf(os.Stdout, "Response from `ShortUrlsLinksAPI.ShortUrlsLinks`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiShortUrlsLinksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **from** | **string** | From date | 
 **to** | **string** | To date | 
 **page** | **int32** | Get items starting from this page. | [default to 1]
 **perPage** | **int32** | The number of items in the page. Possible values are from 10 to 500. | [default to 20]

### Return type

[**ShortUrlsLinks200Response**](ShortUrlsLinks200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

