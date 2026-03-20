# \ContactListDetachAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactListDetach**](ContactListDetachAPI.md#ContactListDetach) | **Post** /api/groups/detach | Remove contacts from the list



## ContactListDetach

> map[string]interface{} ContactListDetach(ctx).ContactListDetachRequest(contactListDetachRequest).Execute()

Remove contacts from the list



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
	contactListDetachRequest := *openapiclient.NewContactListDetachRequest([]int32{int32(123)}, []int32{int32(123)}) // ContactListDetachRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactListDetachAPI.ContactListDetach(context.Background()).ContactListDetachRequest(contactListDetachRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactListDetachAPI.ContactListDetach``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactListDetach`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ContactListDetachAPI.ContactListDetach`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiContactListDetachRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **contactListDetachRequest** | [**ContactListDetachRequest**](ContactListDetachRequest.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

