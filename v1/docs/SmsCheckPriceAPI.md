# \SmsCheckPriceAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SmsCheckPrice**](SmsCheckPriceAPI.md#SmsCheckPrice) | **Post** /rest/sms/price | Check SMS price



## SmsCheckPrice

> SmsPriceCheckResponse SmsCheckPrice(ctx).SmsPriceCheckRequest(smsPriceCheckRequest).Execute()

Check SMS price



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
	smsPriceCheckRequest := *openapiclient.NewSmsPriceCheckRequest("phones", "380953227271", "BSG", "Hello! This is a bulk SMS for price calculation.", []openapiclient.PhoneNumbersInner2{*openapiclient.NewPhoneNumbersInner2("380953227271")}) // SmsPriceCheckRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmsCheckPriceAPI.SmsCheckPrice(context.Background()).SmsPriceCheckRequest(smsPriceCheckRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmsCheckPriceAPI.SmsCheckPrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SmsCheckPrice`: SmsPriceCheckResponse
	fmt.Fprintf(os.Stdout, "Response from `SmsCheckPriceAPI.SmsCheckPrice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSmsCheckPriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **smsPriceCheckRequest** | [**SmsPriceCheckRequest**](SmsPriceCheckRequest.md) |  | 

### Return type

[**SmsPriceCheckResponse**](SmsPriceCheckResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

