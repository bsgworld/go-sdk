# \PostCampaignsWhatsappSendAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PostCampaignsWhatsappSend**](PostCampaignsWhatsappSendAPI.md#PostCampaignsWhatsappSend) | **Post** /api/campaigns/whatsapp/send | Send WhatsApp campaign



## PostCampaignsWhatsappSend

> CampaignSchema PostCampaignsWhatsappSend(ctx).SendWhatsAppCampaign(sendWhatsAppCampaign).Execute()

Send WhatsApp campaign



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
	sendWhatsAppCampaign := *openapiclient.NewSendWhatsAppCampaign([]openapiclient.Phone{*openapiclient.NewPhone("380661231231")}, "whatsapp_sender", "Type_example") // SendWhatsAppCampaign | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostCampaignsWhatsappSendAPI.PostCampaignsWhatsappSend(context.Background()).SendWhatsAppCampaign(sendWhatsAppCampaign).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostCampaignsWhatsappSendAPI.PostCampaignsWhatsappSend``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostCampaignsWhatsappSend`: CampaignSchema
	fmt.Fprintf(os.Stdout, "Response from `PostCampaignsWhatsappSendAPI.PostCampaignsWhatsappSend`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostCampaignsWhatsappSendRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sendWhatsAppCampaign** | [**SendWhatsAppCampaign**](SendWhatsAppCampaign.md) |  | 

### Return type

[**CampaignSchema**](CampaignSchema.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

