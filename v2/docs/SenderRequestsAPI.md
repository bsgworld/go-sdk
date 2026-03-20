# \SenderRequestsAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SenderRequests**](SenderRequestsAPI.md#SenderRequests) | **Get** /api/senders/requests/sms | List of Sender Requests



## SenderRequests

> SenderRequests200Response SenderRequests(ctx).PageLimit(pageLimit).PageOffset(pageOffset).Sort(sort).Way(way).FilterStatus(filterStatus).FilterId(filterId).FilterCountryCode(filterCountryCode).FilterSender(filterSender).FilterCreatedAt(filterCreatedAt).Execute()

List of Sender Requests



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
	pageLimit := int32(50) // int32 |  (optional) (default to 50)
	pageOffset := int32(56) // int32 |  (optional) (default to 0)
	sort := "sort_example" // string |  (optional) (default to "id")
	way := openapiclient.SortWay("asc") // SortWay |  (optional) (default to "asc")
	filterStatus := openapiclient.SenderRequestStatus("new") // SenderRequestStatus |  (optional)
	filterId := int32(56) // int32 |  (optional)
	filterCountryCode := "filterCountryCode_example" // string |  (optional)
	filterSender := "filterSender_example" // string |  (optional)
	filterCreatedAt := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SenderRequestsAPI.SenderRequests(context.Background()).PageLimit(pageLimit).PageOffset(pageOffset).Sort(sort).Way(way).FilterStatus(filterStatus).FilterId(filterId).FilterCountryCode(filterCountryCode).FilterSender(filterSender).FilterCreatedAt(filterCreatedAt).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SenderRequestsAPI.SenderRequests``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SenderRequests`: SenderRequests200Response
	fmt.Fprintf(os.Stdout, "Response from `SenderRequestsAPI.SenderRequests`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSenderRequestsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pageLimit** | **int32** |  | [default to 50]
 **pageOffset** | **int32** |  | [default to 0]
 **sort** | **string** |  | [default to &quot;id&quot;]
 **way** | [**SortWay**](SortWay.md) |  | [default to &quot;asc&quot;]
 **filterStatus** | [**SenderRequestStatus**](SenderRequestStatus.md) |  | 
 **filterId** | **int32** |  | 
 **filterCountryCode** | **string** |  | 
 **filterSender** | **string** |  | 
 **filterCreatedAt** | **time.Time** |  | 

### Return type

[**SenderRequests200Response**](SenderRequests200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

