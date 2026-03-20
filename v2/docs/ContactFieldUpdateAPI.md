# \ContactFieldUpdateAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactFieldUpdate**](ContactFieldUpdateAPI.md#ContactFieldUpdate) | **Patch** /api/contacts/fields/{id} | Update contact field



## ContactFieldUpdate

> ContactFieldUpdate200Response ContactFieldUpdate(ctx, id).ContactFieldUpdateRequest(contactFieldUpdateRequest).Execute()

Update contact field



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
	id := int32(56) // int32 | Contact field id
	contactFieldUpdateRequest := *openapiclient.NewContactFieldUpdateRequest() // ContactFieldUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactFieldUpdateAPI.ContactFieldUpdate(context.Background(), id).ContactFieldUpdateRequest(contactFieldUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactFieldUpdateAPI.ContactFieldUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactFieldUpdate`: ContactFieldUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `ContactFieldUpdateAPI.ContactFieldUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Contact field id | 

### Other Parameters

Other parameters are passed through a pointer to a apiContactFieldUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **contactFieldUpdateRequest** | [**ContactFieldUpdateRequest**](ContactFieldUpdateRequest.md) |  | 

### Return type

[**ContactFieldUpdate200Response**](ContactFieldUpdate200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

