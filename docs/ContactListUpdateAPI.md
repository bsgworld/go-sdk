# \ContactListUpdateAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactListUpdate**](ContactListUpdateAPI.md#ContactListUpdate) | **Put** /api/groups/{id} | Update list



## ContactListUpdate

> ContactListUpdate200Response ContactListUpdate(ctx, id).ContactListUpdateRequest(contactListUpdateRequest).Execute()

Update list



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
	id := int32(56) // int32 | 
	contactListUpdateRequest := *openapiclient.NewContactListUpdateRequest("List 1") // ContactListUpdateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactListUpdateAPI.ContactListUpdate(context.Background(), id).ContactListUpdateRequest(contactListUpdateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactListUpdateAPI.ContactListUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactListUpdate`: ContactListUpdate200Response
	fmt.Fprintf(os.Stdout, "Response from `ContactListUpdateAPI.ContactListUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiContactListUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **contactListUpdateRequest** | [**ContactListUpdateRequest**](ContactListUpdateRequest.md) |  | 

### Return type

[**ContactListUpdate200Response**](ContactListUpdate200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

