# \ContactListsAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactLists**](ContactListsAPI.md#ContactLists) | **Get** /api/groups | List of contact lists



## ContactLists

> ContactLists200Response ContactLists(ctx).PageOffset(pageOffset).PageLimit(pageLimit).Execute()

List of contact lists



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
	pageOffset := int32(56) // int32 |  (optional) (default to 0)
	pageLimit := int32(50) // int32 | The number of items in the response (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactListsAPI.ContactLists(context.Background()).PageOffset(pageOffset).PageLimit(pageLimit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactListsAPI.ContactLists``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactLists`: ContactLists200Response
	fmt.Fprintf(os.Stdout, "Response from `ContactListsAPI.ContactLists`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiContactListsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pageOffset** | **int32** |  | [default to 0]
 **pageLimit** | **int32** | The number of items in the response | [default to 50]

### Return type

[**ContactLists200Response**](ContactLists200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

