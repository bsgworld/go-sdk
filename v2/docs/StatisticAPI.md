# \StatisticAPI

All URIs are relative to *https://one-api.bsg.world*

Method | HTTP request | Description
------------- | ------------- | -------------
[**StatJobsCreate**](StatisticAPI.md#StatJobsCreate) | **Post** /api/stat/jobs | Create new job
[**StatJobsDelete**](StatisticAPI.md#StatJobsDelete) | **Delete** /api/stat/jobs/{id} | Delete job result
[**StatJobsList**](StatisticAPI.md#StatJobsList) | **Get** /api/stat/jobs | List statistic jobs
[**StatJobsShow**](StatisticAPI.md#StatJobsShow) | **Get** /api/stat/jobs/{id} | Load job result



## StatJobsCreate

> StatJobsCreate200Response StatJobsCreate(ctx).StatJobsCreateRequest(statJobsCreateRequest).Execute()

Create new job

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
	statJobsCreateRequest := openapiclient.StatJobsCreateRequest{CreateJobMessage: openapiclient.NewCreateJobMessage("message", []int32{int32(123)})} // StatJobsCreateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StatisticAPI.StatJobsCreate(context.Background()).StatJobsCreateRequest(statJobsCreateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StatisticAPI.StatJobsCreate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StatJobsCreate`: StatJobsCreate200Response
	fmt.Fprintf(os.Stdout, "Response from `StatisticAPI.StatJobsCreate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiStatJobsCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **statJobsCreateRequest** | [**StatJobsCreateRequest**](StatJobsCreateRequest.md) |  | 

### Return type

[**StatJobsCreate200Response**](StatJobsCreate200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StatJobsDelete

> StatJobsDelete200Response StatJobsDelete(ctx, id).Execute()

Delete job result

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
	id := "3941ffacdd698b404e" // string | Job identifier

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StatisticAPI.StatJobsDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StatisticAPI.StatJobsDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StatJobsDelete`: StatJobsDelete200Response
	fmt.Fprintf(os.Stdout, "Response from `StatisticAPI.StatJobsDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Job identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiStatJobsDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**StatJobsDelete200Response**](StatJobsDelete200Response.md)

### Authorization

[ExternalAuth](../README.md#ExternalAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StatJobsList

> map[string]interface{} StatJobsList(ctx).Execute()

List statistic jobs

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
	resp, r, err := apiClient.StatisticAPI.StatJobsList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StatisticAPI.StatJobsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StatJobsList`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `StatisticAPI.StatJobsList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiStatJobsListRequest struct via the builder pattern


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


## StatJobsShow

> map[string]interface{} StatJobsShow(ctx, id).Execute()

Load job result

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
	id := "3941ffacdd698b404e" // string | Job identifier

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StatisticAPI.StatJobsShow(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StatisticAPI.StatJobsShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StatJobsShow`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `StatisticAPI.StatJobsShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Job identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiStatJobsShowRequest struct via the builder pattern


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

