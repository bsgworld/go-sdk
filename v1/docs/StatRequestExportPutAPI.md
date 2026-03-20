# \StatRequestExportPutAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**StatRequestExportPut**](StatRequestExportPutAPI.md#StatRequestExportPut) | **Put** /rest/stat/create | Request data export (PUT)



## StatRequestExportPut

> SuccessResponse StatRequestExportPut(ctx).ExportCreateRequest(exportCreateRequest).Execute()

Request data export (PUT)



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
	exportCreateRequest := *openapiclient.NewExportCreateRequest() // ExportCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StatRequestExportPutAPI.StatRequestExportPut(context.Background()).ExportCreateRequest(exportCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StatRequestExportPutAPI.StatRequestExportPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StatRequestExportPut`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `StatRequestExportPutAPI.StatRequestExportPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiStatRequestExportPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **exportCreateRequest** | [**ExportCreateRequest**](ExportCreateRequest.md) |  | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

