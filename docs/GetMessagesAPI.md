# \GetMessagesAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetMessages**](GetMessagesAPI.md#GetMessages) | **Get** /api/messages | Find messages



## GetMessages

> GetMessages200Response GetMessages(ctx).PageOffset(pageOffset).PageLimit(pageLimit).Sort(sort).Way(way).FilterId(filterId).FilterCampaignId(filterCampaignId).FilterReferenceId(filterReferenceId).FilterFrom(filterFrom).FilterTo(filterTo).Execute()

Find messages

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
	sort := "id" // string | Field to sort the results (optional) (default to "id")
	way := openapiclient.SortWay("asc") // SortWay |  (optional) (default to "asc")
	filterId := int32(56) // int32 |  (optional)
	filterCampaignId := int32(56) // int32 | Filter by campaign Id received when [send message](#operation/sms_send) (optional)
	filterReferenceId := "filterReferenceId_example" // string | Filter by reference passed when [send message](#operation/sms_send) (optional)
	filterFrom := time.Now() // time.Time | Filter message from this date. format ― Y-m-d H:i:s (optional)
	filterTo := time.Now() // time.Time | Filter message up to this date. format ― Y-m-d H:i:s (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GetMessagesAPI.GetMessages(context.Background()).PageOffset(pageOffset).PageLimit(pageLimit).Sort(sort).Way(way).FilterId(filterId).FilterCampaignId(filterCampaignId).FilterReferenceId(filterReferenceId).FilterFrom(filterFrom).FilterTo(filterTo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GetMessagesAPI.GetMessages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMessages`: GetMessages200Response
	fmt.Fprintf(os.Stdout, "Response from `GetMessagesAPI.GetMessages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetMessagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pageOffset** | **int32** |  | [default to 0]
 **pageLimit** | **int32** | The number of items in the response | [default to 50]
 **sort** | **string** | Field to sort the results | [default to &quot;id&quot;]
 **way** | [**SortWay**](SortWay.md) |  | [default to &quot;asc&quot;]
 **filterId** | **int32** |  | 
 **filterCampaignId** | **int32** | Filter by campaign Id received when [send message](#operation/sms_send) | 
 **filterReferenceId** | **string** | Filter by reference passed when [send message](#operation/sms_send) | 
 **filterFrom** | **time.Time** | Filter message from this date. format ― Y-m-d H:i:s | 
 **filterTo** | **time.Time** | Filter message up to this date. format ― Y-m-d H:i:s | 

### Return type

[**GetMessages200Response**](GetMessages200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

