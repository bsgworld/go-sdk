# \Sms2wayIncomingAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SmsGet2WayIncoming**](Sms2wayIncomingAPI.md#SmsGet2WayIncoming) | **Get** /rest/sms/2wayIncoming | Get 2-way incoming messages



## SmsGet2WayIncoming

> Sms2WayIncomingResponse SmsGet2WayIncoming(ctx).Execute()

Get 2-way incoming messages



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.Sms2wayIncomingAPI.SmsGet2WayIncoming(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `Sms2wayIncomingAPI.SmsGet2WayIncoming``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SmsGet2WayIncoming`: Sms2WayIncomingResponse
	fmt.Fprintf(os.Stdout, "Response from `Sms2wayIncomingAPI.SmsGet2WayIncoming`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSmsGet2WayIncomingRequest struct via the builder pattern


### Return type

[**Sms2WayIncomingResponse**](Sms2WayIncomingResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

