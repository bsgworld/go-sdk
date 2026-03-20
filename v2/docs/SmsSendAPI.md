# \SmsSendAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SmsSend**](SmsSendAPI.md#SmsSend) | **Post** /api/campaigns/sms/send | Send SMS campaign



## SmsSend

> SmsCampaignResponse SmsSend(ctx).SmsSendRequest(smsSendRequest).Execute()

Send SMS campaign



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
	smsSendRequest := *openapiclient.NewSmsSendRequest([]openapiclient.SmsSendRequestPhonesItem{*openapiclient.NewSmsSendRequestPhonesItem(int32(380661231231))}, "testsms", "Hello! It’s just test message. Please ignore it!") // SmsSendRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmsSendAPI.SmsSend(context.Background()).SmsSendRequest(smsSendRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmsSendAPI.SmsSend``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SmsSend`: SmsCampaignResponse
	fmt.Fprintf(os.Stdout, "Response from `SmsSendAPI.SmsSend`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSmsSendRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **smsSendRequest** | [**SmsSendRequest**](SmsSendRequest.md) |  | 

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

