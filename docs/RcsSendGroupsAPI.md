# \RcsSendGroupsAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RcsSend**](RcsSendGroupsAPI.md#RcsSend) | **Post** /api/campaigns/rcs/send | Send RCS message



## RcsSend

> RcsSend200Response RcsSend(ctx).SendRcsCampaign(sendRcsCampaign).Execute()

Send RCS message



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
	sendRcsCampaign := *openapiclient.NewSendRcsCampaign([]openapiclient.Phone{*openapiclient.NewPhone("380661231231")}, "rcs_sender", *openapiclient.NewOptions([]openapiclient.Card{*openapiclient.NewCard()}, "Hello! ☺️")) // SendRcsCampaign | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RcsSendGroupsAPI.RcsSend(context.Background()).SendRcsCampaign(sendRcsCampaign).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RcsSendGroupsAPI.RcsSend``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RcsSend`: RcsSend200Response
	fmt.Fprintf(os.Stdout, "Response from `RcsSendGroupsAPI.RcsSend`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRcsSendRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sendRcsCampaign** | [**SendRcsCampaign**](SendRcsCampaign.md) |  | 

### Return type

[**RcsSend200Response**](RcsSend200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

