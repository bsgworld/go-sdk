# \ViberCheckPricePutAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ViberCheckPricePut**](ViberCheckPricePutAPI.md#ViberCheckPricePut) | **Put** /rest/viber/price | Check Viber campaign price (PUT)



## ViberCheckPricePut

> ViberPriceCheckResponse ViberCheckPricePut(ctx).ViberPriceCheckRequest(viberPriceCheckRequest).Execute()

Check Viber campaign price (PUT)



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
	resp, r, err := apiClient.ViberCheckPricePutAPI.ViberCheckPricePut(context.Background()).ViberPriceCheckRequest(viberPriceCheckRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ViberCheckPricePutAPI.ViberCheckPricePut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ViberCheckPricePut`: ViberPriceCheckResponse
	fmt.Fprintf(os.Stdout, "Response from `ViberCheckPricePutAPI.ViberCheckPricePut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiViberCheckPricePutRequest struct via the builder pattern


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

