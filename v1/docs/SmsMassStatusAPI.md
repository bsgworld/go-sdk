# \SmsMassStatusAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SmsGetMassStatus**](SmsMassStatusAPI.md#SmsGetMassStatus) | **Post** /rest/sms/getStatus | Get status for multiple SMS messages



## SmsGetMassStatus

> SmsMassStatusResponse SmsGetMassStatus(ctx).SmsMassStatusRequest(smsMassStatusRequest).Execute()

Get status for multiple SMS messages



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
	smsMassStatusRequest := *openapiclient.NewSmsMassStatusRequest([]int32{int32(123)}) // SmsMassStatusRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmsMassStatusAPI.SmsGetMassStatus(context.Background()).SmsMassStatusRequest(smsMassStatusRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmsMassStatusAPI.SmsGetMassStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SmsGetMassStatus`: SmsMassStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `SmsMassStatusAPI.SmsGetMassStatus`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSmsGetMassStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **smsMassStatusRequest** | [**SmsMassStatusRequest**](SmsMassStatusRequest.md) |  | 

### Return type

[**SmsMassStatusResponse**](SmsMassStatusResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

