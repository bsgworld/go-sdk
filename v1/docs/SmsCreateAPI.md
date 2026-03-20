# \SmsCreateAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SmsCreateObjects**](SmsCreateAPI.md#SmsCreateObjects) | **Post** /rest/sms/create | Send SMS message



## SmsCreateObjects

> SmsCreateResponse SmsCreateObjects(ctx).SmsCreateRequest(smsCreateRequest).Execute()

Send SMS message



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
	smsCreateRequest := *openapiclient.NewSmsCreateRequest("otp", "380953227271", "OTP", "Your verification code is: {gen_otp_09,4}", []openapiclient.PhoneNumbersInner1{*openapiclient.NewPhoneNumbersInner1("380953227271", "BSG", "Personalized message for this recipient")}) // SmsCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmsCreateAPI.SmsCreateObjects(context.Background()).SmsCreateRequest(smsCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmsCreateAPI.SmsCreateObjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SmsCreateObjects`: SmsCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `SmsCreateAPI.SmsCreateObjects`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSmsCreateObjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **smsCreateRequest** | [**SmsCreateRequest**](SmsCreateRequest.md) |  | 

### Return type

[**SmsCreateResponse**](SmsCreateResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

