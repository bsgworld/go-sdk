# \ContactFieldsAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ContactFields**](ContactFieldsAPI.md#ContactFields) | **Get** /api/contacts/fields | List of contact fields



## ContactFields

> ContactFieldCollectionSchema ContactFields(ctx).Execute()

List of contact fields



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ContactFieldsAPI.ContactFields(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ContactFieldsAPI.ContactFields``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContactFields`: ContactFieldCollectionSchema
	fmt.Fprintf(os.Stdout, "Response from `ContactFieldsAPI.ContactFields`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiContactFieldsRequest struct via the builder pattern


### Return type

[**ContactFieldCollectionSchema**](ContactFieldCollectionSchema.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

