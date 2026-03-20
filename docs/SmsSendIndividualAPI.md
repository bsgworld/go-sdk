# \SmsSendIndividualAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SmsSendIndividual**](SmsSendIndividualAPI.md#SmsSendIndividual) | **Post** /api/campaigns/sms/send-individual | Send SMS with different text



## SmsSendIndividual

> SmsCampaignResponse SmsSendIndividual(ctx).SmsSendIndividualRequest(smsSendIndividualRequest).Execute()

Send SMS with different text



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
	smsSendIndividualRequest := *openapiclient.NewSmsSendIndividualRequest([]openapiclient.IndividualMessageData{*openapiclient.NewIndividualMessageData(int32(380661231231), "Hello! It’s just test message. Please ignore it!", "testsms")}) // SmsSendIndividualRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmsSendIndividualAPI.SmsSendIndividual(context.Background()).SmsSendIndividualRequest(smsSendIndividualRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmsSendIndividualAPI.SmsSendIndividual``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SmsSendIndividual`: SmsCampaignResponse
	fmt.Fprintf(os.Stdout, "Response from `SmsSendIndividualAPI.SmsSendIndividual`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSmsSendIndividualRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **smsSendIndividualRequest** | [**SmsSendIndividualRequest**](SmsSendIndividualRequest.md) |  | 

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

