# \ContactListAttachAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactListAttach**](ContactListAttachAPI.md#ContactListAttach) | **Post** /api/groups/attach | Add contacts to the list



## ContactListAttach

> map[string]interface{} ContactListAttach(ctx).ContactListAttachRequest(contactListAttachRequest).Execute()

Add contacts to the list



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
	contactListAttachRequest := *openapiclient.NewContactListAttachRequest([]int32{int32(123)}, []int32{int32(123)}) // ContactListAttachRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactListAttachAPI.ContactListAttach(context.Background()).ContactListAttachRequest(contactListAttachRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactListAttachAPI.ContactListAttach``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactListAttach`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ContactListAttachAPI.ContactListAttach`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiContactListAttachRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **contactListAttachRequest** | [**ContactListAttachRequest**](ContactListAttachRequest.md) |  | 

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

