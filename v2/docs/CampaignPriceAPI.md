# \CampaignPriceAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CampaignPrice**](CampaignPriceAPI.md#CampaignPrice) | **Post** /api/campaigns/price | Calculate campaign price



## CampaignPrice

> CampaignPrice200Response CampaignPrice(ctx).CampaignPriceRequest(campaignPriceRequest).Execute()

Calculate campaign price



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
	campaignPriceRequest := *openapiclient.NewCampaignPriceRequest("testsms", "Hello! It’s just test message. Please ignore it!") // CampaignPriceRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CampaignPriceAPI.CampaignPrice(context.Background()).CampaignPriceRequest(campaignPriceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CampaignPriceAPI.CampaignPrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CampaignPrice`: CampaignPrice200Response
	fmt.Fprintf(os.Stdout, "Response from `CampaignPriceAPI.CampaignPrice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCampaignPriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **campaignPriceRequest** | [**CampaignPriceRequest**](CampaignPriceRequest.md) |  | 

### Return type

[**CampaignPrice200Response**](CampaignPrice200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

