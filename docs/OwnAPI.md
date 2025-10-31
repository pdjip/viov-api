# \OwnAPI

All URIs are relative to *https://apiv1.vio-v.com/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SelfBanklogsGet**](OwnAPI.md#SelfBanklogsGet) | **Get** /self/banklogs | Get Own Banklogs
[**SelfGet**](OwnAPI.md#SelfGet) | **Get** /self | Get Own Data
[**SelfPlayingtimeGet**](OwnAPI.md#SelfPlayingtimeGet) | **Get** /self/playingtime | Get Own Playingtime statistics
[**SelfStorageGet**](OwnAPI.md#SelfStorageGet) | **Get** /self/storage | Get Own Storage



## SelfBanklogsGet

> []CharacterBankLog SelfBanklogsGet(ctx).Execute()

Get Own Banklogs

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/pdjip/viov-api"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OwnAPI.SelfBanklogsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OwnAPI.SelfBanklogsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SelfBanklogsGet`: []CharacterBankLog
	fmt.Fprintf(os.Stdout, "Response from `OwnAPI.SelfBanklogsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSelfBanklogsGetRequest struct via the builder pattern


### Return type

[**[]CharacterBankLog**](CharacterBankLog.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SelfGet

> Character SelfGet(ctx).Execute()

Get Own Data

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/pdjip/viov-api"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OwnAPI.SelfGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OwnAPI.SelfGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SelfGet`: Character
	fmt.Fprintf(os.Stdout, "Response from `OwnAPI.SelfGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSelfGetRequest struct via the builder pattern


### Return type

[**Character**](Character.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SelfPlayingtimeGet

> []CharacterPlaytime SelfPlayingtimeGet(ctx).Execute()

Get Own Playingtime statistics

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/pdjip/viov-api"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OwnAPI.SelfPlayingtimeGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OwnAPI.SelfPlayingtimeGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SelfPlayingtimeGet`: []CharacterPlaytime
	fmt.Fprintf(os.Stdout, "Response from `OwnAPI.SelfPlayingtimeGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSelfPlayingtimeGetRequest struct via the builder pattern


### Return type

[**[]CharacterPlaytime**](CharacterPlaytime.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SelfStorageGet

> []InventoryItem SelfStorageGet(ctx).Execute()

Get Own Storage

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/pdjip/viov-api"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OwnAPI.SelfStorageGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OwnAPI.SelfStorageGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SelfStorageGet`: []InventoryItem
	fmt.Fprintf(os.Stdout, "Response from `OwnAPI.SelfStorageGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSelfStorageGetRequest struct via the builder pattern


### Return type

[**[]InventoryItem**](InventoryItem.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

