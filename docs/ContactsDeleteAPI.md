# \ContactsDeleteAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactsDelete**](ContactsDeleteAPI.md#ContactsDelete) | **Post** /api/contacts/delete | Delete multiple contacts



## ContactsDelete

> map[string]interface{} ContactsDelete(ctx).ContactIds(contactIds).GroupIds(groupIds).Execute()

Delete multiple contacts



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
	contactIds := []int32{int32(123)} // []int32 | Contact ids to delete (optional)
	groupIds := []int32{int32(123)} // []int32 | Contact lists ids to delete **contacts** included into these lists (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactsDeleteAPI.ContactsDelete(context.Background()).ContactIds(contactIds).GroupIds(groupIds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactsDeleteAPI.ContactsDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactsDelete`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ContactsDeleteAPI.ContactsDelete`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiContactsDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **contactIds** | **[]int32** | Contact ids to delete | 
 **groupIds** | **[]int32** | Contact lists ids to delete **contacts** included into these lists | 

### Return type

**map[string]interface{}**

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

