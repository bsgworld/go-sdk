# \ContactCreateAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactCreate**](ContactCreateAPI.md#ContactCreate) | **Post** /api/contacts | Create a contact



## ContactCreate

> ContactCreate201Response ContactCreate(ctx).StoreContact(storeContact).Execute()

Create a contact



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
	storeContact := *openapiclient.NewStoreContact(int32(33601148802)) // StoreContact | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactCreateAPI.ContactCreate(context.Background()).StoreContact(storeContact).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactCreateAPI.ContactCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactCreate`: ContactCreate201Response
	fmt.Fprintf(os.Stdout, "Response from `ContactCreateAPI.ContactCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiContactCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **storeContact** | [**StoreContact**](StoreContact.md) |  | 

### Return type

[**ContactCreate201Response**](ContactCreate201Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

