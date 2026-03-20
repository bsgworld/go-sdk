# \OtpTemplateAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OtpTemplate**](OtpTemplateAPI.md#OtpTemplate) | **Get** /api/2fa/authentications/templates/{templateId} | Get message template



## OtpTemplate

> OtpTemplate200Response OtpTemplate(ctx, templateId).Execute()

Get message template

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
	templateId := int32(56) // int32 | Template id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OtpTemplateAPI.OtpTemplate(context.Background(), templateId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OtpTemplateAPI.OtpTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OtpTemplate`: OtpTemplate200Response
	fmt.Fprintf(os.Stdout, "Response from `OtpTemplateAPI.OtpTemplate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**templateId** | **int32** | Template id | 

### Other Parameters

Other parameters are passed through a pointer to a apiOtpTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OtpTemplate200Response**](OtpTemplate200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

