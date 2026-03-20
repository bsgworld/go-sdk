# \CampaignAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CampaignSend**](CampaignAPI.md#CampaignSend) | **Post** /api/campaigns/send | Send campaign



## CampaignSend

> CampaignResponse CampaignSend(ctx).Campaign(campaign).Execute()

Send campaign



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
	campaign := *openapiclient.NewCampaign(*openapiclient.NewRecipients([]openapiclient.Phone{*openapiclient.NewPhone("380661231231")}, []int32{int32(123)}), []string{"Channels_example"}) // Campaign | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CampaignAPI.CampaignSend(context.Background()).Campaign(campaign).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CampaignAPI.CampaignSend``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CampaignSend`: CampaignResponse
	fmt.Fprintf(os.Stdout, "Response from `CampaignAPI.CampaignSend`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCampaignSendRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **campaign** | [**Campaign**](Campaign.md) |  | 

### Return type

[**CampaignResponse**](CampaignResponse.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

