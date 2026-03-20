# \MessagesWhatsAppAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**WhatsappSingle**](MessagesWhatsAppAPI.md#WhatsappSingle) | **Post** /api/messages/whatsapp/send | Send single WhatsApp message



## WhatsappSingle

> MessageResponse WhatsappSingle(ctx).WhatsAppMessage(whatsAppMessage).Execute()

Send single WhatsApp message



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
	whatsAppMessage := *openapiclient.NewWhatsAppMessage(*openapiclient.NewPhone("380661231231"), "Sender_example", "Type_example") // WhatsAppMessage | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessagesWhatsAppAPI.WhatsappSingle(context.Background()).WhatsAppMessage(whatsAppMessage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessagesWhatsAppAPI.WhatsappSingle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `WhatsappSingle`: MessageResponse
	fmt.Fprintf(os.Stdout, "Response from `MessagesWhatsAppAPI.WhatsappSingle`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiWhatsappSingleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **whatsAppMessage** | [**WhatsAppMessage**](WhatsAppMessage.md) |  | 

### Return type

[**MessageResponse**](MessageResponse.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

