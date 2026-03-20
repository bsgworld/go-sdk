# \OtpListAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OtpList**](OtpListAPI.md#OtpList) | **Get** /api/2fa/authentications | List of authentication sessions



## OtpList

> OtpList200Response OtpList(ctx).FilterFrom(filterFrom).FilterTo(filterTo).PageOffset(pageOffset).PageLimit(pageLimit).FilterIds(filterIds).FilterStatus(filterStatus).FilterChannel(filterChannel).FilterRecipient(filterRecipient).FilterCountryCode(filterCountryCode).Way(way).Sort(sort).Execute()

List of authentication sessions



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
	filterFrom := time.Now() // string | Period start date (date and time when the authentication session was created) in ISO 8601 format.
	filterTo := time.Now() // string | End date of the period (date and time when the authentication was created) in ISO 8601 format.
	pageOffset := int32(56) // int32 |  (optional) (default to 0)
	pageLimit := int32(56) // int32 |  (optional) (default to 10)
	filterIds := []string{"ea5db413-e368-4952-b745-cc2030210c49"} // []string | Authentication ID. The maximum number is 3. (optional)
	filterStatus := openapiclient.OtpStatus("pending") // OtpStatus |  (optional)
	filterChannel := openapiclient.OtpChannel("sms") // OtpChannel |  (optional)
	filterRecipient := "filterRecipient_example" // string |  (optional)
	filterCountryCode := "filterCountryCode_example" // string |  (optional)
	way := openapiclient.SortWay("asc") // SortWay |  (optional) (default to "asc")
	sort := "sort_example" // string | Sort by (optional) (default to "id")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OtpListAPI.OtpList(context.Background()).FilterFrom(filterFrom).FilterTo(filterTo).PageOffset(pageOffset).PageLimit(pageLimit).FilterIds(filterIds).FilterStatus(filterStatus).FilterChannel(filterChannel).FilterRecipient(filterRecipient).FilterCountryCode(filterCountryCode).Way(way).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OtpListAPI.OtpList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OtpList`: OtpList200Response
	fmt.Fprintf(os.Stdout, "Response from `OtpListAPI.OtpList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOtpListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filterFrom** | **string** | Period start date (date and time when the authentication session was created) in ISO 8601 format. | 
 **filterTo** | **string** | End date of the period (date and time when the authentication was created) in ISO 8601 format. | 
 **pageOffset** | **int32** |  | [default to 0]
 **pageLimit** | **int32** |  | [default to 10]
 **filterIds** | **[]string** | Authentication ID. The maximum number is 3. | 
 **filterStatus** | [**OtpStatus**](OtpStatus.md) |  | 
 **filterChannel** | [**OtpChannel**](OtpChannel.md) |  | 
 **filterRecipient** | **string** |  | 
 **filterCountryCode** | **string** |  | 
 **way** | [**SortWay**](SortWay.md) |  | [default to &quot;asc&quot;]
 **sort** | **string** | Sort by | [default to &quot;id&quot;]

### Return type

[**OtpList200Response**](OtpList200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

