# \SystemAPI

All URIs are relative to *https://apiv1.vio-v.com/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SystemGroupwarsGet**](SystemAPI.md#SystemGroupwarsGet) | **Get** /system/groupwars | Get GroupWars Data
[**SystemItemsGet**](SystemAPI.md#SystemItemsGet) | **Get** /system/items | Get Items Data



## SystemGroupwarsGet

> []SystemGroupWar SystemGroupwarsGet(ctx).Execute()

Get GroupWars Data

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SystemAPI.SystemGroupwarsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SystemAPI.SystemGroupwarsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SystemGroupwarsGet`: []SystemGroupWar
	fmt.Fprintf(os.Stdout, "Response from `SystemAPI.SystemGroupwarsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSystemGroupwarsGetRequest struct via the builder pattern


### Return type

[**[]SystemGroupWar**](SystemGroupWar.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SystemItemsGet

> []SystemItem SystemItemsGet(ctx).Execute()

Get Items Data

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SystemAPI.SystemItemsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SystemAPI.SystemItemsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SystemItemsGet`: []SystemItem
	fmt.Fprintf(os.Stdout, "Response from `SystemAPI.SystemItemsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSystemItemsGetRequest struct via the builder pattern


### Return type

[**[]SystemItem**](SystemItem.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

