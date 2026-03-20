# \ShortUrlsClicksAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ShortUrlsClicks**](ShortUrlsClicksAPI.md#ShortUrlsClicks) | **Get** /api/short-url/clicks | List of clicks



## ShortUrlsClicks

> ShortUrlsClicks200Response ShortUrlsClicks(ctx).From(from).To(to).Page(page).PerPage(perPage).Campaign(campaign).Execute()

List of clicks



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
	campaign := int32(56) // int32 | Campaign id to get only clicks on short link sent as part on [sms campaign](#tag/Campaign-SMS) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShortUrlsClicksAPI.ShortUrlsClicks(context.Background()).From(from).To(to).Page(page).PerPage(perPage).Campaign(campaign).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShortUrlsClicksAPI.ShortUrlsClicks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShortUrlsClicks`: ShortUrlsClicks200Response
	fmt.Fprintf(os.Stdout, "Response from `ShortUrlsClicksAPI.ShortUrlsClicks`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiShortUrlsClicksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **from** | **string** | From date | 
 **to** | **string** | To date | 
 **page** | **int32** | Get items starting from this page. | [default to 1]
 **perPage** | **int32** | The number of items in the page. Possible values are from 10 to 500. | [default to 20]
 **campaign** | **int32** | Campaign id to get only clicks on short link sent as part on [sms campaign](#tag/Campaign-SMS) | 

### Return type

[**ShortUrlsClicks200Response**](ShortUrlsClicks200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

