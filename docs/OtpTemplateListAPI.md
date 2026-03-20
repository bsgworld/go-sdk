# \OtpTemplateListAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OtpTemplateList**](OtpTemplateListAPI.md#OtpTemplateList) | **Get** /api/2fa/authentications/templates | List of message templates



## OtpTemplateList

> OtpTemplateList200Response OtpTemplateList(ctx).PageOffset(pageOffset).PageLimit(pageLimit).FilterIds(filterIds).FilterStatus(filterStatus).Sort(sort).Way(way).Execute()

List of message templates



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
	pageOffset := int32(56) // int32 |  (optional) (default to 0)
	pageLimit := int32(56) // int32 |  (optional) (default to 10)
	filterIds := []int32{int32(515)} // []int32 |  (optional)
	filterStatus := "filterStatus_example" // string |  (optional)
	sort := "sort_example" // string | Sorting by (optional) (default to "template_id")
	way := openapiclient.SortWay("asc") // SortWay |  (optional) (default to "asc")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OtpTemplateListAPI.OtpTemplateList(context.Background()).PageOffset(pageOffset).PageLimit(pageLimit).FilterIds(filterIds).FilterStatus(filterStatus).Sort(sort).Way(way).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OtpTemplateListAPI.OtpTemplateList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OtpTemplateList`: OtpTemplateList200Response
	fmt.Fprintf(os.Stdout, "Response from `OtpTemplateListAPI.OtpTemplateList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOtpTemplateListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pageOffset** | **int32** |  | [default to 0]
 **pageLimit** | **int32** |  | [default to 10]
 **filterIds** | **[]int32** |  | 
 **filterStatus** | **string** |  | 
 **sort** | **string** | Sorting by | [default to &quot;template_id&quot;]
 **way** | [**SortWay**](SortWay.md) |  | [default to &quot;asc&quot;]

### Return type

[**OtpTemplateList200Response**](OtpTemplateList200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

