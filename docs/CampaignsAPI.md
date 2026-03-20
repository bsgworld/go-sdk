# \CampaignsAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Campaigns**](CampaignsAPI.md#Campaigns) | **Get** /api/campaigns | List of campaigns



## Campaigns

> SearchCampaignResource Campaigns(ctx).PageOffset(pageOffset).PageLimit(pageLimit).Sort(sort).Way(way).FilterFrom(filterFrom).FilterTo(filterTo).FilterType(filterType).SearchField(searchField).SearchValue(searchValue).Execute()

List of campaigns



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/bsgworld/go-sdk"
)

func main() {
	pageOffset := int32(56) // int32 |  (optional) (default to 0)
	pageLimit := int32(50) // int32 | The number of items in the response (optional) (default to 50)
	sort := "sort_example" // string | Sort items by (optional) (default to "id")
	way := openapiclient.SortWay("asc") // SortWay |  (optional) (default to "asc")
	filterFrom := time.Now() // time.Time | Include items from (optional)
	filterTo := time.Now() // time.Time | Include items to (optional)
	filterType := "filterType_example" // string | Filter items by type type (optional)
	searchField := "searchField_example" // string | Filter items by search[field]=search[value] (optional)
	searchValue := "searchValue_example" // string | Filter items by search[field]=search[value] (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CampaignsAPI.Campaigns(context.Background()).PageOffset(pageOffset).PageLimit(pageLimit).Sort(sort).Way(way).FilterFrom(filterFrom).FilterTo(filterTo).FilterType(filterType).SearchField(searchField).SearchValue(searchValue).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CampaignsAPI.Campaigns``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Campaigns`: SearchCampaignResource
	fmt.Fprintf(os.Stdout, "Response from `CampaignsAPI.Campaigns`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCampaignsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pageOffset** | **int32** |  | [default to 0]
 **pageLimit** | **int32** | The number of items in the response | [default to 50]
 **sort** | **string** | Sort items by | [default to &quot;id&quot;]
 **way** | [**SortWay**](SortWay.md) |  | [default to &quot;asc&quot;]
 **filterFrom** | **time.Time** | Include items from | 
 **filterTo** | **time.Time** | Include items to | 
 **filterType** | **string** | Filter items by type type | 
 **searchField** | **string** | Filter items by search[field]&#x3D;search[value] | 
 **searchValue** | **string** | Filter items by search[field]&#x3D;search[value] | 

### Return type

[**SearchCampaignResource**](SearchCampaignResource.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

