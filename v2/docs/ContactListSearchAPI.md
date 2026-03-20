# \ContactListSearchAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactListSearch**](ContactListSearchAPI.md#ContactListSearch) | **Get** /api/groups/search | Search list



## ContactListSearch

> ContactListSearch200Response ContactListSearch(ctx).PageOffset(pageOffset).PageLimit(pageLimit).Sort(sort).Way(way).SearchField(searchField).SearchOperator(searchOperator).SearchValue(searchValue).SearchFields0Field(searchFields0Field).SearchFields0Operator(searchFields0Operator).SearchFields0Value(searchFields0Value).Execute()

Search list



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
	sort := "sort_example" // string |  (optional) (default to "id")
	way := openapiclient.SortWay("asc") // SortWay |  (optional) (default to "asc")
	searchField := openapiclient.ContactGroupSearchField("id") // ContactGroupSearchField |  (optional)
	searchOperator := openapiclient.SearchOperator("like") // SearchOperator |  (optional)
	searchValue := "searchValue_example" // string |  (optional)
	searchFields0Field := openapiclient.ContactGroupSearchField("id") // ContactGroupSearchField |  (optional)
	searchFields0Operator := openapiclient.SearchOperator("like") // SearchOperator |  (optional)
	searchFields0Value := "searchFields0Value_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactListSearchAPI.ContactListSearch(context.Background()).PageOffset(pageOffset).PageLimit(pageLimit).Sort(sort).Way(way).SearchField(searchField).SearchOperator(searchOperator).SearchValue(searchValue).SearchFields0Field(searchFields0Field).SearchFields0Operator(searchFields0Operator).SearchFields0Value(searchFields0Value).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactListSearchAPI.ContactListSearch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactListSearch`: ContactListSearch200Response
	fmt.Fprintf(os.Stdout, "Response from `ContactListSearchAPI.ContactListSearch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiContactListSearchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pageOffset** | **int32** |  | [default to 0]
 **pageLimit** | **int32** | The number of items in the response | [default to 50]
 **sort** | **string** |  | [default to &quot;id&quot;]
 **way** | [**SortWay**](SortWay.md) |  | [default to &quot;asc&quot;]
 **searchField** | [**ContactGroupSearchField**](ContactGroupSearchField.md) |  | 
 **searchOperator** | [**SearchOperator**](SearchOperator.md) |  | 
 **searchValue** | **string** |  | 
 **searchFields0Field** | [**ContactGroupSearchField**](ContactGroupSearchField.md) |  | 
 **searchFields0Operator** | [**SearchOperator**](SearchOperator.md) |  | 
 **searchFields0Value** | **string** |  | 

### Return type

[**ContactListSearch200Response**](ContactListSearch200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

