# \VerifyOtpAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**VerifyOtp**](VerifyOtpAPI.md#VerifyOtp) | **Post** /api/2fa/authentications/otp/{id}/verify | Check one-time Code



## VerifyOtp

> VerifyOtp200Response VerifyOtp(ctx, id).VerifyOtpRequest(verifyOtpRequest).Execute()

Check one-time Code



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
	id := "ea5db413-e368-4952-b745-cc2030210c49" // string | Authentication ID received in response to [POST /api/2fa/authentications/otp](#tag/TwoFA/operation/send_otp) The maximum length is 36 characters.
	verifyOtpRequest := *openapiclient.NewVerifyOtpRequest("76928") // VerifyOtpRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VerifyOtpAPI.VerifyOtp(context.Background(), id).VerifyOtpRequest(verifyOtpRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VerifyOtpAPI.VerifyOtp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifyOtp`: VerifyOtp200Response
	fmt.Fprintf(os.Stdout, "Response from `VerifyOtpAPI.VerifyOtp`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Authentication ID received in response to [POST /api/2fa/authentications/otp](#tag/TwoFA/operation/send_otp) The maximum length is 36 characters. | 

### Other Parameters

Other parameters are passed through a pointer to a apiVerifyOtpRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **verifyOtpRequest** | [**VerifyOtpRequest**](VerifyOtpRequest.md) |  | 

### Return type

[**VerifyOtp200Response**](VerifyOtp200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

