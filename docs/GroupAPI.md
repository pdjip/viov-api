# \GroupAPI

All URIs are relative to *https://apiv1.vio-v.com/api/v3*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GroupAreasGet**](GroupAPI.md#GroupAreasGet) | **Get** /group/areas | Get Group Areas Data (GangWars)
[**GroupFactoriesGet**](GroupAPI.md#GroupFactoriesGet) | **Get** /group/factories | Get Group Factories Data | Squad only!
[**GroupFairplayBlacklistGet**](GroupAPI.md#GroupFairplayBlacklistGet) | **Get** /group/fairplay_blacklist | Get Server Fairplay Blacklist
[**GroupGet**](GroupAPI.md#GroupGet) | **Get** /group | Get Group Data
[**GroupMembersGet**](GroupAPI.md#GroupMembersGet) | **Get** /group/members | Get Group Members Data
[**GroupOwnFactoriesGet**](GroupAPI.md#GroupOwnFactoriesGet) | **Get** /group/own_factories | Get Group Produktion Factories Data
[**GroupRanksGet**](GroupAPI.md#GroupRanksGet) | **Get** /group/ranks | Get Group Rank Data
[**GroupShopsGet**](GroupAPI.md#GroupShopsGet) | **Get** /group/shops | Get Group Shops
[**GroupSkinGet**](GroupAPI.md#GroupSkinGet) | **Get** /group/skin | Get Group Skin Data
[**GroupSpraiesGet**](GroupAPI.md#GroupSpraiesGet) | **Get** /group/spraies | Get Group Spraies Data
[**GroupStorageGet**](GroupAPI.md#GroupStorageGet) | **Get** /group/storage | Get Group Storage
[**GroupStorageLogsGet**](GroupAPI.md#GroupStorageLogsGet) | **Get** /group/storage/logs | Get Group Storage Logs
[**GroupVehiclesGet**](GroupAPI.md#GroupVehiclesGet) | **Get** /group/vehicles | Get Group Vehicles Data



## GroupAreasGet

> []GangArea GroupAreasGet(ctx).Execute()

Get Group Areas Data (GangWars)

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
	resp, r, err := apiClient.GroupAPI.GroupAreasGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupAPI.GroupAreasGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GroupAreasGet`: []GangArea
	fmt.Fprintf(os.Stdout, "Response from `GroupAPI.GroupAreasGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGroupAreasGetRequest struct via the builder pattern


### Return type

[**[]GangArea**](GangArea.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GroupFactoriesGet

> []GroupSpray GroupFactoriesGet(ctx).Execute()

Get Group Factories Data | Squad only!

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
	resp, r, err := apiClient.GroupAPI.GroupFactoriesGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupAPI.GroupFactoriesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GroupFactoriesGet`: []GroupSpray
	fmt.Fprintf(os.Stdout, "Response from `GroupAPI.GroupFactoriesGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGroupFactoriesGetRequest struct via the builder pattern


### Return type

[**[]GroupSpray**](GroupSpray.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GroupFairplayBlacklistGet

> []GroupSpray GroupFairplayBlacklistGet(ctx).Execute()

Get Server Fairplay Blacklist

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
	resp, r, err := apiClient.GroupAPI.GroupFairplayBlacklistGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupAPI.GroupFairplayBlacklistGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GroupFairplayBlacklistGet`: []GroupSpray
	fmt.Fprintf(os.Stdout, "Response from `GroupAPI.GroupFairplayBlacklistGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGroupFairplayBlacklistGetRequest struct via the builder pattern


### Return type

[**[]GroupSpray**](GroupSpray.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GroupGet

> []Group GroupGet(ctx).Execute()

Get Group Data

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
	resp, r, err := apiClient.GroupAPI.GroupGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupAPI.GroupGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GroupGet`: []Group
	fmt.Fprintf(os.Stdout, "Response from `GroupAPI.GroupGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGroupGetRequest struct via the builder pattern


### Return type

[**[]Group**](Group.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GroupMembersGet

> []GroupMember GroupMembersGet(ctx).Execute()

Get Group Members Data

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
	resp, r, err := apiClient.GroupAPI.GroupMembersGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupAPI.GroupMembersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GroupMembersGet`: []GroupMember
	fmt.Fprintf(os.Stdout, "Response from `GroupAPI.GroupMembersGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGroupMembersGetRequest struct via the builder pattern


### Return type

[**[]GroupMember**](GroupMember.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GroupOwnFactoriesGet

> []GroupOwnFactory GroupOwnFactoriesGet(ctx).Execute()

Get Group Produktion Factories Data

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
	resp, r, err := apiClient.GroupAPI.GroupOwnFactoriesGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupAPI.GroupOwnFactoriesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GroupOwnFactoriesGet`: []GroupOwnFactory
	fmt.Fprintf(os.Stdout, "Response from `GroupAPI.GroupOwnFactoriesGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGroupOwnFactoriesGetRequest struct via the builder pattern


### Return type

[**[]GroupOwnFactory**](GroupOwnFactory.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GroupRanksGet

> []GroupRank GroupRanksGet(ctx).Execute()

Get Group Rank Data

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
	resp, r, err := apiClient.GroupAPI.GroupRanksGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupAPI.GroupRanksGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GroupRanksGet`: []GroupRank
	fmt.Fprintf(os.Stdout, "Response from `GroupAPI.GroupRanksGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGroupRanksGetRequest struct via the builder pattern


### Return type

[**[]GroupRank**](GroupRank.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GroupShopsGet

> []GroupShop GroupShopsGet(ctx).Execute()

Get Group Shops

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
	resp, r, err := apiClient.GroupAPI.GroupShopsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupAPI.GroupShopsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GroupShopsGet`: []GroupShop
	fmt.Fprintf(os.Stdout, "Response from `GroupAPI.GroupShopsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGroupShopsGetRequest struct via the builder pattern


### Return type

[**[]GroupShop**](GroupShop.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GroupSkinGet

> []GroupSkin GroupSkinGet(ctx).Execute()

Get Group Skin Data

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
	resp, r, err := apiClient.GroupAPI.GroupSkinGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupAPI.GroupSkinGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GroupSkinGet`: []GroupSkin
	fmt.Fprintf(os.Stdout, "Response from `GroupAPI.GroupSkinGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGroupSkinGetRequest struct via the builder pattern


### Return type

[**[]GroupSkin**](GroupSkin.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GroupSpraiesGet

> []GroupSpray GroupSpraiesGet(ctx).Execute()

Get Group Spraies Data

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
	resp, r, err := apiClient.GroupAPI.GroupSpraiesGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupAPI.GroupSpraiesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GroupSpraiesGet`: []GroupSpray
	fmt.Fprintf(os.Stdout, "Response from `GroupAPI.GroupSpraiesGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGroupSpraiesGetRequest struct via the builder pattern


### Return type

[**[]GroupSpray**](GroupSpray.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GroupStorageGet

> []InventoryItem GroupStorageGet(ctx).Execute()

Get Group Storage

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
	resp, r, err := apiClient.GroupAPI.GroupStorageGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupAPI.GroupStorageGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GroupStorageGet`: []InventoryItem
	fmt.Fprintf(os.Stdout, "Response from `GroupAPI.GroupStorageGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGroupStorageGetRequest struct via the builder pattern


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


## GroupStorageLogsGet

> []GroupStorageLog GroupStorageLogsGet(ctx).Execute()

Get Group Storage Logs

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
	resp, r, err := apiClient.GroupAPI.GroupStorageLogsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupAPI.GroupStorageLogsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GroupStorageLogsGet`: []GroupStorageLog
	fmt.Fprintf(os.Stdout, "Response from `GroupAPI.GroupStorageLogsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGroupStorageLogsGetRequest struct via the builder pattern


### Return type

[**[]GroupStorageLog**](GroupStorageLog.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GroupVehiclesGet

> []GroupVehicle GroupVehiclesGet(ctx).Execute()

Get Group Vehicles Data

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
	resp, r, err := apiClient.GroupAPI.GroupVehiclesGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GroupAPI.GroupVehiclesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GroupVehiclesGet`: []GroupVehicle
	fmt.Fprintf(os.Stdout, "Response from `GroupAPI.GroupVehiclesGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGroupVehiclesGetRequest struct via the builder pattern


### Return type

[**[]GroupVehicle**](GroupVehicle.md)

### Authorization

[vio_auth](../README.md#vio_auth), [vio_auth](../README.md#vio_auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

