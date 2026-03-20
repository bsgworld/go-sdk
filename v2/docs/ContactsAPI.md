# \ContactsAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Contacts**](ContactsAPI.md#Contacts) | **Get** /api/contacts | List of contacts



## Contacts

> Contacts200Response Contacts(ctx).PageOffset(pageOffset).PageLimit(pageLimit).Groups(groups).Execute()

List of contacts



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
	pageLimit := int32(50) // int32 | The number of items in the response (optional) (default to 20)
	groups := []int32{int32(123)} // []int32 | Index of IDs of the lists for which you want to display contacts (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactsAPI.Contacts(context.Background()).PageOffset(pageOffset).PageLimit(pageLimit).Groups(groups).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactsAPI.Contacts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Contacts`: Contacts200Response
	fmt.Fprintf(os.Stdout, "Response from `ContactsAPI.Contacts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiContactsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pageOffset** | **int32** |  | [default to 0]
 **pageLimit** | **int32** | The number of items in the response | [default to 20]
 **groups** | **[]int32** | Index of IDs of the lists for which you want to display contacts | 

### Return type

[**Contacts200Response**](Contacts200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

