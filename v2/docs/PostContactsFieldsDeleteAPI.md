# \PostContactsFieldsDeleteAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PostContactsFieldsDelete**](PostContactsFieldsDeleteAPI.md#PostContactsFieldsDelete) | **Post** /api/contacts/fields/delete | Delete contact fields by ids



## PostContactsFieldsDelete

> map[string]interface{} PostContactsFieldsDelete(ctx).PostContactsFieldsDeleteRequest(postContactsFieldsDeleteRequest).Execute()

Delete contact fields by ids



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
	postContactsFieldsDeleteRequest := *openapiclient.NewPostContactsFieldsDeleteRequest([]int32{int32(387714)}) // PostContactsFieldsDeleteRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostContactsFieldsDeleteAPI.PostContactsFieldsDelete(context.Background()).PostContactsFieldsDeleteRequest(postContactsFieldsDeleteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostContactsFieldsDeleteAPI.PostContactsFieldsDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostContactsFieldsDelete`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `PostContactsFieldsDeleteAPI.PostContactsFieldsDelete`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostContactsFieldsDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **postContactsFieldsDeleteRequest** | [**PostContactsFieldsDeleteRequest**](PostContactsFieldsDeleteRequest.md) |  | 

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

