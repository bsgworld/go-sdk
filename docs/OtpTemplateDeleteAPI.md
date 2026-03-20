# \OtpTemplateDeleteAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OtpTemplateDelete**](OtpTemplateDeleteAPI.md#OtpTemplateDelete) | **Delete** /api/2fa/authentications/templates/{templateId} | Delete a message template



## OtpTemplateDelete

> OtpTemplateDelete200Response OtpTemplateDelete(ctx, templateId).Execute()

Delete a message template



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
	templateId := int32(56) // int32 | The ID of the message template that you want to delete. From 1 to 9 digits.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OtpTemplateDeleteAPI.OtpTemplateDelete(context.Background(), templateId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OtpTemplateDeleteAPI.OtpTemplateDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OtpTemplateDelete`: OtpTemplateDelete200Response
	fmt.Fprintf(os.Stdout, "Response from `OtpTemplateDeleteAPI.OtpTemplateDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**templateId** | **int32** | The ID of the message template that you want to delete. From 1 to 9 digits. | 

### Other Parameters

Other parameters are passed through a pointer to a apiOtpTemplateDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OtpTemplateDelete200Response**](OtpTemplateDelete200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

