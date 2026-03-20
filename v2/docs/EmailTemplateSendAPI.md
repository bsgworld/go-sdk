# \EmailTemplateSendAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EmailTemplateSend**](EmailTemplateSendAPI.md#EmailTemplateSend) | **Post** /api/email/send-template-emails | Send Email template



## EmailTemplateSend

> EmailResponse EmailTemplateSend(ctx).SendTemplateEmail(sendTemplateEmail).Execute()

Send Email template



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
	sendTemplateEmail := *openapiclient.NewSendTemplateEmail([]string{"To_example"}, "From_example", int32(123)) // SendTemplateEmail | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmailTemplateSendAPI.EmailTemplateSend(context.Background()).SendTemplateEmail(sendTemplateEmail).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmailTemplateSendAPI.EmailTemplateSend``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EmailTemplateSend`: EmailResponse
	fmt.Fprintf(os.Stdout, "Response from `EmailTemplateSendAPI.EmailTemplateSend`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEmailTemplateSendRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sendTemplateEmail** | [**SendTemplateEmail**](SendTemplateEmail.md) |  | 

### Return type

[**EmailResponse**](EmailResponse.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

