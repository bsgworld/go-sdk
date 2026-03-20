# \ViberCreatePutAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ViberCreateObjectsPut**](ViberCreatePutAPI.md#ViberCreateObjectsPut) | **Put** /rest/viber/create | Send Viber message (PUT)



## ViberCreateObjectsPut

> ViberCreateResponse ViberCreateObjectsPut(ctx).ViberCreateRequest(viberCreateRequest).Execute()

Send Viber message (PUT)



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
	viberCreateRequest := *openapiclient.NewViberCreateRequest([]openapiclient.ViberCreateRequestMessagesInner{*openapiclient.NewViberCreateRequestMessagesInner("Hello from Viber!", "BSG", []openapiclient.ViberCreateRequestMessagesInnerToInner{*openapiclient.NewViberCreateRequestMessagesInnerToInner("380953227271")})}) // ViberCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ViberCreatePutAPI.ViberCreateObjectsPut(context.Background()).ViberCreateRequest(viberCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ViberCreatePutAPI.ViberCreateObjectsPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ViberCreateObjectsPut`: ViberCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `ViberCreatePutAPI.ViberCreateObjectsPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiViberCreateObjectsPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **viberCreateRequest** | [**ViberCreateRequest**](ViberCreateRequest.md) |  | 

### Return type

[**ViberCreateResponse**](ViberCreateResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

