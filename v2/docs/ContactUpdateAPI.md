# \ContactUpdateAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactUpdate**](ContactUpdateAPI.md#ContactUpdate) | **Put** /api/contacts/{id} | Update contact



## ContactUpdate

> ContactUpdate200Response ContactUpdate(ctx, id).ContactUpdateRequest(contactUpdateRequest).Execute()

Update contact



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
	id := int32(56) // int32 | Contact id
	contactUpdateRequest := *openapiclient.NewContactUpdateRequest(int32(33601148802)) // ContactUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactUpdateAPI.ContactUpdate(context.Background(), id).ContactUpdateRequest(contactUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactUpdateAPI.ContactUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactUpdate`: ContactUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `ContactUpdateAPI.ContactUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Contact id | 

### Other Parameters

Other parameters are passed through a pointer to a apiContactUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **contactUpdateRequest** | [**ContactUpdateRequest**](ContactUpdateRequest.md) |  | 

### Return type

[**ContactUpdate200Response**](ContactUpdate200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

