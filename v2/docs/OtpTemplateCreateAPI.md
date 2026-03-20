# \OtpTemplateCreateAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OtpTemplateCreate**](OtpTemplateCreateAPI.md#OtpTemplateCreate) | **Post** /api/2fa/authentications/templates | Create a message template



## OtpTemplateCreate

> OtpTemplateCreate200Response OtpTemplateCreate(ctx).OtpTemplateCreateRequest(otpTemplateCreateRequest).Execute()

Create a message template



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
	otpTemplateCreateRequest := *openapiclient.NewOtpTemplateCreateRequest("template name", "test code is {code2fa}") // OtpTemplateCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OtpTemplateCreateAPI.OtpTemplateCreate(context.Background()).OtpTemplateCreateRequest(otpTemplateCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OtpTemplateCreateAPI.OtpTemplateCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OtpTemplateCreate`: OtpTemplateCreate200Response
	fmt.Fprintf(os.Stdout, "Response from `OtpTemplateCreateAPI.OtpTemplateCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOtpTemplateCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **otpTemplateCreateRequest** | [**OtpTemplateCreateRequest**](OtpTemplateCreateRequest.md) |  | 

### Return type

[**OtpTemplateCreate200Response**](OtpTemplateCreate200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

