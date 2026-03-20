# \CampaignRCSAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RcsSendGroups**](CampaignRCSAPI.md#RcsSendGroups) | **Post** /api/campaigns/rcs/send-groups | Send RCS message to contact list



## RcsSendGroups

> RcsSendGroups200Response RcsSendGroups(ctx).SendRcsCampaignGroups(sendRcsCampaignGroups).Execute()

Send RCS message to contact list



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
	sendRcsCampaignGroups := *openapiclient.NewSendRcsCampaignGroups([]int32{int32(123)}, "rcs_sender", *openapiclient.NewOptions([]openapiclient.Card{*openapiclient.NewCard()}, "Hello! ☺️")) // SendRcsCampaignGroups | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CampaignRCSAPI.RcsSendGroups(context.Background()).SendRcsCampaignGroups(sendRcsCampaignGroups).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CampaignRCSAPI.RcsSendGroups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RcsSendGroups`: RcsSendGroups200Response
	fmt.Fprintf(os.Stdout, "Response from `CampaignRCSAPI.RcsSendGroups`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRcsSendGroupsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sendRcsCampaignGroups** | [**SendRcsCampaignGroups**](SendRcsCampaignGroups.md) |  | 

### Return type

[**RcsSendGroups200Response**](RcsSendGroups200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

