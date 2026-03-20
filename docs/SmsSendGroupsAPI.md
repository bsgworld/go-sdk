# \SmsSendGroupsAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SmsSendGroups**](SmsSendGroupsAPI.md#SmsSendGroups) | **Post** /api/campaigns/sms/send-groups | Send SMS to contact list



## SmsSendGroups

> SmsCampaignResponse SmsSendGroups(ctx).SmsSendGroupsRequest(smsSendGroupsRequest).Execute()

Send SMS to contact list



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
	smsSendGroupsRequest := *openapiclient.NewSmsSendGroupsRequest("testsms", "Hello! It’s just test message. Please ignore it!") // SmsSendGroupsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmsSendGroupsAPI.SmsSendGroups(context.Background()).SmsSendGroupsRequest(smsSendGroupsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmsSendGroupsAPI.SmsSendGroups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SmsSendGroups`: SmsCampaignResponse
	fmt.Fprintf(os.Stdout, "Response from `SmsSendGroupsAPI.SmsSendGroups`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSmsSendGroupsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **smsSendGroupsRequest** | [**SmsSendGroupsRequest**](SmsSendGroupsRequest.md) |  | 

### Return type

[**SmsCampaignResponse**](SmsCampaignResponse.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

