# \StatGetFileAPI

All URIs are relative to *https://api.sms-service.local*

Method | HTTP request | Description
------------- | ------------- | -------------
[**StatGetFile**](StatGetFileAPI.md#StatGetFile) | **Get** /rest/stat/file/id/{id}/format/{format} | Download export file



## StatGetFile

> SuccessResponse StatGetFile(ctx, id, format).Execute()

Download export file



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
	id := "a78e8ba648698afdfe" // string | Export file key (returned from create request)
	format := "csv" // string | File format for download (default to "json")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StatGetFileAPI.StatGetFile(context.Background(), id, format).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StatGetFileAPI.StatGetFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StatGetFile`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `StatGetFileAPI.StatGetFile`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Export file key (returned from create request) | 
**format** | **string** | File format for download | [default to &quot;json&quot;]

### Other Parameters

Other parameters are passed through a pointer to a apiStatGetFileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

