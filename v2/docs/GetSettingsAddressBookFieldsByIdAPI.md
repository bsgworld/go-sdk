# \GetSettingsAddressBookFieldsByIdAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetSettingsAddressBookFieldsById**](GetSettingsAddressBookFieldsByIdAPI.md#GetSettingsAddressBookFieldsById) | **Get** /api/settings/address-book-fields/{id} | Get settings value



## GetSettingsAddressBookFieldsById

> map[string]interface{} GetSettingsAddressBookFieldsById(ctx, id).Execute()

Get settings value

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
	id := int32(1) // int32 | Address Book ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GetSettingsAddressBookFieldsByIdAPI.GetSettingsAddressBookFieldsById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GetSettingsAddressBookFieldsByIdAPI.GetSettingsAddressBookFieldsById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSettingsAddressBookFieldsById`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `GetSettingsAddressBookFieldsByIdAPI.GetSettingsAddressBookFieldsById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **int32** | Address Book ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSettingsAddressBookFieldsByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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

