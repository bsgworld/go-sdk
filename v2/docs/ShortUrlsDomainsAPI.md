# \ShortUrlsDomainsAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ShortUrlsDomains**](ShortUrlsDomainsAPI.md#ShortUrlsDomains) | **Get** /api/short-url/domains | List of domains



## ShortUrlsDomains

> ShortUrlsDomains200Response ShortUrlsDomains(ctx).From(from).To(to).Page(page).PerPage(perPage).Execute()

List of domains



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
	resp, r, err := apiClient.ShortUrlsDomainsAPI.ShortUrlsDomains(context.Background()).From(from).To(to).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShortUrlsDomainsAPI.ShortUrlsDomains``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShortUrlsDomains`: ShortUrlsDomains200Response
	fmt.Fprintf(os.Stdout, "Response from `ShortUrlsDomainsAPI.ShortUrlsDomains`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiShortUrlsDomainsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **from** | **string** | From date | 
 **to** | **string** | To date | 
 **page** | **int32** | Get items starting from this page. | [default to 1]
 **perPage** | **int32** | The number of items in the page. Possible values are from 10 to 500. | [default to 20]

### Return type

[**ShortUrlsDomains200Response**](ShortUrlsDomains200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

