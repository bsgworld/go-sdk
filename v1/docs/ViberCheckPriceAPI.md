# \ViberCheckPriceAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ViberCheckPrice**](ViberCheckPriceAPI.md#ViberCheckPrice) | **Post** /rest/viber/price | Check Viber campaign price



## ViberCheckPrice

> ViberPriceCheckResponse ViberCheckPrice(ctx).ViberPriceCheckRequest(viberPriceCheckRequest).Execute()

Check Viber campaign price



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
	viberPriceCheckRequest := *openapiclient.NewViberPriceCheckRequest([]openapiclient.ViberPriceCheckRequestMessagesInner{*openapiclient.NewViberPriceCheckRequestMessagesInner("Hello from Viber! Check price.", "BSG", []openapiclient.ViberPriceCheckRequestMessagesInnerToInner{*openapiclient.NewViberPriceCheckRequestMessagesInnerToInner("380953227271")})}) // ViberPriceCheckRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ViberCheckPriceAPI.ViberCheckPrice(context.Background()).ViberPriceCheckRequest(viberPriceCheckRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ViberCheckPriceAPI.ViberCheckPrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ViberCheckPrice`: ViberPriceCheckResponse
	fmt.Fprintf(os.Stdout, "Response from `ViberCheckPriceAPI.ViberCheckPrice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiViberCheckPriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **viberPriceCheckRequest** | [**ViberPriceCheckRequest**](ViberPriceCheckRequest.md) |  | 

### Return type

[**ViberPriceCheckResponse**](ViberPriceCheckResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

