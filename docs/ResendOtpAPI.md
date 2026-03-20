# \ResendOtpAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ResendOtp**](ResendOtpAPI.md#ResendOtp) | **Post** /api/2fa/authentications/otp/{id}/resend | Resend the one-time code



## ResendOtp

> ResendOtp200Response ResendOtp(ctx, id).Execute()

Resend the one-time code



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResendOtpAPI.ResendOtp(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResendOtpAPI.ResendOtp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResendOtp`: ResendOtp200Response
	fmt.Fprintf(os.Stdout, "Response from `ResendOtpAPI.ResendOtp`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Authentication ID received in response to [POST /api/2fa/authentications/otp](#tag/TwoFA/operation/send_otp) The maximum length is 36 characters. | 

### Other Parameters

Other parameters are passed through a pointer to a apiResendOtpRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ResendOtp200Response**](ResendOtp200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

