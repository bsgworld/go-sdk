# \ContactsSearchAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactsSearch**](ContactsSearchAPI.md#ContactsSearch) | **Get** /api/contacts/search | Search contacts



## ContactsSearch

> ContactsSearch200Response ContactsSearch(ctx).PageOffset(pageOffset).PageLimit(pageLimit).Sort(sort).Way(way).SearchField(searchField).SearchOperator(searchOperator).SearchValue(searchValue).SearchFields0Field(searchFields0Field).SearchFields0Operator(searchFields0Operator).SearchFields0Value(searchFields0Value).Execute()

Search contacts



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
	sort := "sort_example" // string | Sort by conditions: id, phone (optional) (default to "id")
	way := openapiclient.SortWay("asc") // SortWay |  (optional) (default to "asc")
	searchField := "searchField_example" // string |  (optional)
	searchOperator := openapiclient.SearchOperator("like") // SearchOperator |  (optional)
	searchValue := "searchValue_example" // string |  (optional)
	searchFields0Field := "searchFields0Field_example" // string |  (optional)
	searchFields0Operator := openapiclient.SearchOperator("like") // SearchOperator |  (optional)
	searchFields0Value := "searchFields0Value_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactsSearchAPI.ContactsSearch(context.Background()).PageOffset(pageOffset).PageLimit(pageLimit).Sort(sort).Way(way).SearchField(searchField).SearchOperator(searchOperator).SearchValue(searchValue).SearchFields0Field(searchFields0Field).SearchFields0Operator(searchFields0Operator).SearchFields0Value(searchFields0Value).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactsSearchAPI.ContactsSearch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactsSearch`: ContactsSearch200Response
	fmt.Fprintf(os.Stdout, "Response from `ContactsSearchAPI.ContactsSearch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiContactsSearchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pageOffset** | **int32** |  | [default to 0]
 **pageLimit** | **int32** | The number of items in the response | [default to 50]
 **sort** | **string** | Sort by conditions: id, phone | [default to &quot;id&quot;]
 **way** | [**SortWay**](SortWay.md) |  | [default to &quot;asc&quot;]
 **searchField** | **string** |  | 
 **searchOperator** | [**SearchOperator**](SearchOperator.md) |  | 
 **searchValue** | **string** |  | 
 **searchFields0Field** | **string** |  | 
 **searchFields0Operator** | [**SearchOperator**](SearchOperator.md) |  | 
 **searchFields0Value** | **string** |  | 

### Return type

[**ContactsSearch200Response**](ContactsSearch200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

