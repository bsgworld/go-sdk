# \ContactFieldCreateAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactFieldCreate**](ContactFieldCreateAPI.md#ContactFieldCreate) | **Post** /api/contacts/fields | Create contact field



## ContactFieldCreate

> ContactFieldCreate201Response ContactFieldCreate(ctx).ContactFieldCreateRequest(contactFieldCreateRequest).Execute()

Create contact field



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
	contactFieldCreateRequest := *openapiclient.NewContactFieldCreateRequest("country", openapiclient.ContactFieldType("text")) // ContactFieldCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactFieldCreateAPI.ContactFieldCreate(context.Background()).ContactFieldCreateRequest(contactFieldCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactFieldCreateAPI.ContactFieldCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactFieldCreate`: ContactFieldCreate201Response
	fmt.Fprintf(os.Stdout, "Response from `ContactFieldCreateAPI.ContactFieldCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiContactFieldCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **contactFieldCreateRequest** | [**ContactFieldCreateRequest**](ContactFieldCreateRequest.md) |  | 

### Return type

[**ContactFieldCreate201Response**](ContactFieldCreate201Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

