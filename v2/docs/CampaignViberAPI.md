# \CampaignViberAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ViberSend**](CampaignViberAPI.md#ViberSend) | **Post** /api/campaigns/viber/send | Send Viber campaign



## ViberSend

> ViberCampaignResponse ViberSend(ctx).SendViberCampaign(sendViberCampaign).Execute()

Send Viber campaign



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
	sendViberCampaign := *openapiclient.NewSendViberCampaign([]openapiclient.Phone{*openapiclient.NewPhone("380661231231")}, "testsms", "Text_example") // SendViberCampaign | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CampaignViberAPI.ViberSend(context.Background()).SendViberCampaign(sendViberCampaign).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CampaignViberAPI.ViberSend``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ViberSend`: ViberCampaignResponse
	fmt.Fprintf(os.Stdout, "Response from `CampaignViberAPI.ViberSend`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiViberSendRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sendViberCampaign** | [**SendViberCampaign**](SendViberCampaign.md) |  | 

### Return type

[**ViberCampaignResponse**](ViberCampaignResponse.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

