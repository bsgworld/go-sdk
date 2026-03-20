# \EmailSendAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EmailSend**](EmailSendAPI.md#EmailSend) | **Post** /api/email/send-emails | Send Email



## EmailSend

> EmailResponse EmailSend(ctx).SendEmail(sendEmail).Execute()

Send Email



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
	sendEmail := *openapiclient.NewSendEmail([]string{"To_example"}, "From_example", "Subject_example", "Htmlbody_example") // SendEmail | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmailSendAPI.EmailSend(context.Background()).SendEmail(sendEmail).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmailSendAPI.EmailSend``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EmailSend`: EmailResponse
	fmt.Fprintf(os.Stdout, "Response from `EmailSendAPI.EmailSend`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiEmailSendRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sendEmail** | [**SendEmail**](SendEmail.md) |  | 

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

