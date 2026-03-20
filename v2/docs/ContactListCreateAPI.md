# \ContactListCreateAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactListCreate**](ContactListCreateAPI.md#ContactListCreate) | **Post** /api/groups | Create list



## ContactListCreate

> ContactListCreate201Response ContactListCreate(ctx).ContactListCreateRequest(contactListCreateRequest).Execute()

Create list



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
	contactListCreateRequest := *openapiclient.NewContactListCreateRequest("List 1") // ContactListCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactListCreateAPI.ContactListCreate(context.Background()).ContactListCreateRequest(contactListCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactListCreateAPI.ContactListCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactListCreate`: ContactListCreate201Response
	fmt.Fprintf(os.Stdout, "Response from `ContactListCreateAPI.ContactListCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiContactListCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **contactListCreateRequest** | [**ContactListCreateRequest**](ContactListCreateRequest.md) |  | 

### Return type

[**ContactListCreate201Response**](ContactListCreate201Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

