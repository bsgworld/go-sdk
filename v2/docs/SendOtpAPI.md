# \SendOtpAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SendOtp**](SendOtpAPI.md#SendOtp) | **Post** /api/2fa/authentications/otp | Send One-time password



## SendOtp

> SendOtp201Response SendOtp(ctx).SendOtpRequest(sendOtpRequest).Execute()

Send One-time password



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
	sendOtpRequest := *openapiclient.NewSendOtpRequest("61401629754", "sms", "SENDER", int32(1), int32(300), int32(3), int32(5)) // SendOtpRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SendOtpAPI.SendOtp(context.Background()).SendOtpRequest(sendOtpRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SendOtpAPI.SendOtp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendOtp`: SendOtp201Response
	fmt.Fprintf(os.Stdout, "Response from `SendOtpAPI.SendOtp`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSendOtpRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sendOtpRequest** | [**SendOtpRequest**](SendOtpRequest.md) |  | 

### Return type

[**SendOtp201Response**](SendOtp201Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

