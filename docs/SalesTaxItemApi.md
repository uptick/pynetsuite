# pynetsuite.SalesTaxItemApi

All URIs are relative to *https://account_id.suitetalk.api.netsuite.com/services/rest/record/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**sales_tax_item_get**](SalesTaxItemApi.md#sales_tax_item_get) | **GET** /salesTaxItem | Get list of records.
[**sales_tax_item_id_delete**](SalesTaxItemApi.md#sales_tax_item_id_delete) | **DELETE** /salesTaxItem/{id} | Remove record.
[**sales_tax_item_id_get**](SalesTaxItemApi.md#sales_tax_item_id_get) | **GET** /salesTaxItem/{id} | Get record.
[**sales_tax_item_id_patch**](SalesTaxItemApi.md#sales_tax_item_id_patch) | **PATCH** /salesTaxItem/{id} | Update record.
[**sales_tax_item_id_put**](SalesTaxItemApi.md#sales_tax_item_id_put) | **PUT** /salesTaxItem/{id} | Insert or update record.
[**sales_tax_item_post**](SalesTaxItemApi.md#sales_tax_item_post) | **POST** /salesTaxItem | Insert record.


# **sales_tax_item_get**
> SalesTaxItemCollection sales_tax_item_get(prefer=prefer, x_net_suite_idempotency_key=x_net_suite_idempotency_key, q=q, fields=fields, limit=limit, offset=offset)

Get list of records.

### Example

* Api Key Authentication (OAuth_1.0_authorization):

```python
import pynetsuite
from pynetsuite.models.sales_tax_item_collection import SalesTaxItemCollection
from pynetsuite.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://account_id.suitetalk.api.netsuite.com/services/rest/record/v1
# See configuration.py for a list of all supported configuration parameters.
configuration = pynetsuite.Configuration(
    host = "https://account_id.suitetalk.api.netsuite.com/services/rest/record/v1"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: OAuth_1.0_authorization
configuration.api_key['OAuth_1.0_authorization'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['OAuth_1.0_authorization'] = 'Bearer'

# Enter a context with an instance of the API client
with pynetsuite.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = pynetsuite.SalesTaxItemApi(api_client)
    prefer = 'prefer_example' # str | The server behavior requested by the client. Use 'respond-async' to execute the request asynchronously. If the request is executed asynchronously, 'Preference-applied: respond-async' is returned in the response. (optional)
    x_net_suite_idempotency_key = 'x_net_suite_idempotency_key_example' # str | A user-defined unique idempotency key that is applied to every asynchronous requests to ensure that the request is executed only once. Only one request can be executed with every unique idempotency key. Use UUID in string format as defined by RFC 4122. If the request is executed synchronously, this value is ignored. (optional)
    q = 'q_example' # str | The search query that is used to filter results. (optional)
    fields = 'fields_example' # str | The fields to select. (optional)
    limit = 1000 # int | The limit used to specify the number of results on a single page. (optional) (default to 1000)
    offset = 0 # int | The offset used for selecting a specific page of results. (optional) (default to 0)

    try:
        # Get list of records.
        api_response = api_instance.sales_tax_item_get(prefer=prefer, x_net_suite_idempotency_key=x_net_suite_idempotency_key, q=q, fields=fields, limit=limit, offset=offset)
        print("The response of SalesTaxItemApi->sales_tax_item_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SalesTaxItemApi->sales_tax_item_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **prefer** | **str**| The server behavior requested by the client. Use &#39;respond-async&#39; to execute the request asynchronously. If the request is executed asynchronously, &#39;Preference-applied: respond-async&#39; is returned in the response. | [optional] 
 **x_net_suite_idempotency_key** | **str**| A user-defined unique idempotency key that is applied to every asynchronous requests to ensure that the request is executed only once. Only one request can be executed with every unique idempotency key. Use UUID in string format as defined by RFC 4122. If the request is executed synchronously, this value is ignored. | [optional] 
 **q** | **str**| The search query that is used to filter results. | [optional] 
 **fields** | **str**| The fields to select. | [optional] 
 **limit** | **int**| The limit used to specify the number of results on a single page. | [optional] [default to 1000]
 **offset** | **int**| The offset used for selecting a specific page of results. | [optional] [default to 0]

### Return type

[**SalesTaxItemCollection**](SalesTaxItemCollection.md)

### Authorization

[OAuth_1.0_authorization](../README.md#OAuth_1.0_authorization)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/vnd.oracle.resource+json; type=collection, application/vnd.oracle.resource+json; type=error

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | List of records. |  -  |
**0** | Error response. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sales_tax_item_id_delete**
> sales_tax_item_id_delete(id, prefer=prefer, x_net_suite_idempotency_key=x_net_suite_idempotency_key)

Remove record.

### Example

* Api Key Authentication (OAuth_1.0_authorization):

```python
import pynetsuite
from pynetsuite.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://account_id.suitetalk.api.netsuite.com/services/rest/record/v1
# See configuration.py for a list of all supported configuration parameters.
configuration = pynetsuite.Configuration(
    host = "https://account_id.suitetalk.api.netsuite.com/services/rest/record/v1"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: OAuth_1.0_authorization
configuration.api_key['OAuth_1.0_authorization'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['OAuth_1.0_authorization'] = 'Bearer'

# Enter a context with an instance of the API client
with pynetsuite.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = pynetsuite.SalesTaxItemApi(api_client)
    id = 56 # int | Internal identifier.
    prefer = 'prefer_example' # str | The server behavior requested by the client. Use 'respond-async' to execute the request asynchronously. If the request is executed asynchronously, 'Preference-applied: respond-async' is returned in the response. (optional)
    x_net_suite_idempotency_key = 'x_net_suite_idempotency_key_example' # str | A user-defined unique idempotency key that is applied to every asynchronous requests to ensure that the request is executed only once. Only one request can be executed with every unique idempotency key. Use UUID in string format as defined by RFC 4122. If the request is executed synchronously, this value is ignored. (optional)

    try:
        # Remove record.
        api_instance.sales_tax_item_id_delete(id, prefer=prefer, x_net_suite_idempotency_key=x_net_suite_idempotency_key)
    except Exception as e:
        print("Exception when calling SalesTaxItemApi->sales_tax_item_id_delete: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**| Internal identifier. | 
 **prefer** | **str**| The server behavior requested by the client. Use &#39;respond-async&#39; to execute the request asynchronously. If the request is executed asynchronously, &#39;Preference-applied: respond-async&#39; is returned in the response. | [optional] 
 **x_net_suite_idempotency_key** | **str**| A user-defined unique idempotency key that is applied to every asynchronous requests to ensure that the request is executed only once. Only one request can be executed with every unique idempotency key. Use UUID in string format as defined by RFC 4122. If the request is executed synchronously, this value is ignored. | [optional] 

### Return type

void (empty response body)

### Authorization

[OAuth_1.0_authorization](../README.md#OAuth_1.0_authorization)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/vnd.oracle.resource+json; type=error

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Removed record. |  -  |
**0** | Error response. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sales_tax_item_id_get**
> SalesTaxItem sales_tax_item_id_get(id, prefer=prefer, x_net_suite_idempotency_key=x_net_suite_idempotency_key, expand_sub_resources=expand_sub_resources, simple_enum_format=simple_enum_format, fields=fields)

Get record.

### Example

* Api Key Authentication (OAuth_1.0_authorization):

```python
import pynetsuite
from pynetsuite.models.sales_tax_item import SalesTaxItem
from pynetsuite.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://account_id.suitetalk.api.netsuite.com/services/rest/record/v1
# See configuration.py for a list of all supported configuration parameters.
configuration = pynetsuite.Configuration(
    host = "https://account_id.suitetalk.api.netsuite.com/services/rest/record/v1"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: OAuth_1.0_authorization
configuration.api_key['OAuth_1.0_authorization'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['OAuth_1.0_authorization'] = 'Bearer'

# Enter a context with an instance of the API client
with pynetsuite.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = pynetsuite.SalesTaxItemApi(api_client)
    id = 56 # int | Internal identifier.
    prefer = 'prefer_example' # str | The server behavior requested by the client. Use 'respond-async' to execute the request asynchronously. If the request is executed asynchronously, 'Preference-applied: respond-async' is returned in the response. (optional)
    x_net_suite_idempotency_key = 'x_net_suite_idempotency_key_example' # str | A user-defined unique idempotency key that is applied to every asynchronous requests to ensure that the request is executed only once. Only one request can be executed with every unique idempotency key. Use UUID in string format as defined by RFC 4122. If the request is executed synchronously, this value is ignored. (optional)
    expand_sub_resources = False # bool | Set to 'true' to automatically expand all sublists, sublist lines, and subrecords on this record. (optional) (default to False)
    simple_enum_format = False # bool | Set to true to return enumeration values in a format that only shows the internal ID value. (optional) (default to False)
    fields = 'field1,field2' # str | The names of the fields and sublists on the record. Only the selected fields and sublists will be returned in the response. (optional)

    try:
        # Get record.
        api_response = api_instance.sales_tax_item_id_get(id, prefer=prefer, x_net_suite_idempotency_key=x_net_suite_idempotency_key, expand_sub_resources=expand_sub_resources, simple_enum_format=simple_enum_format, fields=fields)
        print("The response of SalesTaxItemApi->sales_tax_item_id_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SalesTaxItemApi->sales_tax_item_id_get: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**| Internal identifier. | 
 **prefer** | **str**| The server behavior requested by the client. Use &#39;respond-async&#39; to execute the request asynchronously. If the request is executed asynchronously, &#39;Preference-applied: respond-async&#39; is returned in the response. | [optional] 
 **x_net_suite_idempotency_key** | **str**| A user-defined unique idempotency key that is applied to every asynchronous requests to ensure that the request is executed only once. Only one request can be executed with every unique idempotency key. Use UUID in string format as defined by RFC 4122. If the request is executed synchronously, this value is ignored. | [optional] 
 **expand_sub_resources** | **bool**| Set to &#39;true&#39; to automatically expand all sublists, sublist lines, and subrecords on this record. | [optional] [default to False]
 **simple_enum_format** | **bool**| Set to true to return enumeration values in a format that only shows the internal ID value. | [optional] [default to False]
 **fields** | **str**| The names of the fields and sublists on the record. Only the selected fields and sublists will be returned in the response. | [optional] 

### Return type

[**SalesTaxItem**](SalesTaxItem.md)

### Authorization

[OAuth_1.0_authorization](../README.md#OAuth_1.0_authorization)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/vnd.oracle.resource+json; type=singular, application/vnd.oracle.resource+json; type=error

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Retrieved record. |  * X-NetSuite-Warning - Warning messages that occurred during processing. <br>  |
**0** | Error response. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sales_tax_item_id_patch**
> sales_tax_item_id_patch(id, sales_tax_item, prefer=prefer, x_net_suite_idempotency_key=x_net_suite_idempotency_key, x_net_suite_property_name_validation=x_net_suite_property_name_validation, x_net_suite_property_value_validation=x_net_suite_property_value_validation, replace=replace, replace_selected_fields=replace_selected_fields)

Update record.

### Example

* Api Key Authentication (OAuth_1.0_authorization):

```python
import pynetsuite
from pynetsuite.models.sales_tax_item import SalesTaxItem
from pynetsuite.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://account_id.suitetalk.api.netsuite.com/services/rest/record/v1
# See configuration.py for a list of all supported configuration parameters.
configuration = pynetsuite.Configuration(
    host = "https://account_id.suitetalk.api.netsuite.com/services/rest/record/v1"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: OAuth_1.0_authorization
configuration.api_key['OAuth_1.0_authorization'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['OAuth_1.0_authorization'] = 'Bearer'

# Enter a context with an instance of the API client
with pynetsuite.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = pynetsuite.SalesTaxItemApi(api_client)
    id = 56 # int | Internal identifier.
    sales_tax_item = pynetsuite.SalesTaxItem() # SalesTaxItem | Request body.
    prefer = 'prefer_example' # str | The server behavior requested by the client. Use 'respond-async' to execute the request asynchronously. If the request is executed asynchronously, 'Preference-applied: respond-async' is returned in the response. (optional)
    x_net_suite_idempotency_key = 'x_net_suite_idempotency_key_example' # str | A user-defined unique idempotency key that is applied to every asynchronous requests to ensure that the request is executed only once. Only one request can be executed with every unique idempotency key. Use UUID in string format as defined by RFC 4122. If the request is executed synchronously, this value is ignored. (optional)
    x_net_suite_property_name_validation = Warning # str | Sets the strictness of property name validation. (optional) (default to Warning)
    x_net_suite_property_value_validation = Error # str | Sets the strictness of property value validation. (optional) (default to Error)
    replace = 'sublist1,subrecord.sublist2' # str | The names of sublists on this record. All sublist lines will be replaced with lines specified in the request. The names are delimited by comma. (optional)
    replace_selected_fields = False # bool | If set to 'true', all fields that should be deleted in the update request, including body fields, must be included in the 'replace' query parameter. (optional) (default to False)

    try:
        # Update record.
        api_instance.sales_tax_item_id_patch(id, sales_tax_item, prefer=prefer, x_net_suite_idempotency_key=x_net_suite_idempotency_key, x_net_suite_property_name_validation=x_net_suite_property_name_validation, x_net_suite_property_value_validation=x_net_suite_property_value_validation, replace=replace, replace_selected_fields=replace_selected_fields)
    except Exception as e:
        print("Exception when calling SalesTaxItemApi->sales_tax_item_id_patch: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **int**| Internal identifier. | 
 **sales_tax_item** | [**SalesTaxItem**](SalesTaxItem.md)| Request body. | 
 **prefer** | **str**| The server behavior requested by the client. Use &#39;respond-async&#39; to execute the request asynchronously. If the request is executed asynchronously, &#39;Preference-applied: respond-async&#39; is returned in the response. | [optional] 
 **x_net_suite_idempotency_key** | **str**| A user-defined unique idempotency key that is applied to every asynchronous requests to ensure that the request is executed only once. Only one request can be executed with every unique idempotency key. Use UUID in string format as defined by RFC 4122. If the request is executed synchronously, this value is ignored. | [optional] 
 **x_net_suite_property_name_validation** | **str**| Sets the strictness of property name validation. | [optional] [default to Warning]
 **x_net_suite_property_value_validation** | **str**| Sets the strictness of property value validation. | [optional] [default to Error]
 **replace** | **str**| The names of sublists on this record. All sublist lines will be replaced with lines specified in the request. The names are delimited by comma. | [optional] 
 **replace_selected_fields** | **bool**| If set to &#39;true&#39;, all fields that should be deleted in the update request, including body fields, must be included in the &#39;replace&#39; query parameter. | [optional] [default to False]

### Return type

void (empty response body)

### Authorization

[OAuth_1.0_authorization](../README.md#OAuth_1.0_authorization)

### HTTP request headers

 - **Content-Type**: application/vnd.oracle.resource+json; type=singular
 - **Accept**: application/vnd.oracle.resource+json; type=error

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Updated record. |  * X-NetSuite-PropertyValidation - The description of a property validation failure. <br>  * X-NetSuite-Warning - Warning messages that occurred during processing. <br>  |
**0** | Error response. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sales_tax_item_id_put**
> sales_tax_item_id_put(id, sales_tax_item, prefer=prefer, x_net_suite_idempotency_key=x_net_suite_idempotency_key, x_net_suite_property_name_validation=x_net_suite_property_name_validation, x_net_suite_property_value_validation=x_net_suite_property_value_validation, replace=replace, replace_selected_fields=replace_selected_fields)

Insert or update record.

### Example

* Api Key Authentication (OAuth_1.0_authorization):

```python
import pynetsuite
from pynetsuite.models.sales_tax_item import SalesTaxItem
from pynetsuite.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://account_id.suitetalk.api.netsuite.com/services/rest/record/v1
# See configuration.py for a list of all supported configuration parameters.
configuration = pynetsuite.Configuration(
    host = "https://account_id.suitetalk.api.netsuite.com/services/rest/record/v1"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: OAuth_1.0_authorization
configuration.api_key['OAuth_1.0_authorization'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['OAuth_1.0_authorization'] = 'Bearer'

# Enter a context with an instance of the API client
with pynetsuite.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = pynetsuite.SalesTaxItemApi(api_client)
    id = 'id_example' # str | External identifier.
    sales_tax_item = pynetsuite.SalesTaxItem() # SalesTaxItem | Request body.
    prefer = 'prefer_example' # str | The server behavior requested by the client. Use 'respond-async' to execute the request asynchronously. If the request is executed asynchronously, 'Preference-applied: respond-async' is returned in the response. (optional)
    x_net_suite_idempotency_key = 'x_net_suite_idempotency_key_example' # str | A user-defined unique idempotency key that is applied to every asynchronous requests to ensure that the request is executed only once. Only one request can be executed with every unique idempotency key. Use UUID in string format as defined by RFC 4122. If the request is executed synchronously, this value is ignored. (optional)
    x_net_suite_property_name_validation = Warning # str | Sets the strictness of property name validation. (optional) (default to Warning)
    x_net_suite_property_value_validation = Error # str | Sets the strictness of property value validation. (optional) (default to Error)
    replace = 'sublist1,subrecord.sublist2' # str | The names of sublists on this record. All sublist lines will be replaced with lines specified in the request. The names are delimited by comma. (optional)
    replace_selected_fields = False # bool | If set to 'true', all fields that should be deleted in the update request, including body fields, must be included in the 'replace' query parameter. (optional) (default to False)

    try:
        # Insert or update record.
        api_instance.sales_tax_item_id_put(id, sales_tax_item, prefer=prefer, x_net_suite_idempotency_key=x_net_suite_idempotency_key, x_net_suite_property_name_validation=x_net_suite_property_name_validation, x_net_suite_property_value_validation=x_net_suite_property_value_validation, replace=replace, replace_selected_fields=replace_selected_fields)
    except Exception as e:
        print("Exception when calling SalesTaxItemApi->sales_tax_item_id_put: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| External identifier. | 
 **sales_tax_item** | [**SalesTaxItem**](SalesTaxItem.md)| Request body. | 
 **prefer** | **str**| The server behavior requested by the client. Use &#39;respond-async&#39; to execute the request asynchronously. If the request is executed asynchronously, &#39;Preference-applied: respond-async&#39; is returned in the response. | [optional] 
 **x_net_suite_idempotency_key** | **str**| A user-defined unique idempotency key that is applied to every asynchronous requests to ensure that the request is executed only once. Only one request can be executed with every unique idempotency key. Use UUID in string format as defined by RFC 4122. If the request is executed synchronously, this value is ignored. | [optional] 
 **x_net_suite_property_name_validation** | **str**| Sets the strictness of property name validation. | [optional] [default to Warning]
 **x_net_suite_property_value_validation** | **str**| Sets the strictness of property value validation. | [optional] [default to Error]
 **replace** | **str**| The names of sublists on this record. All sublist lines will be replaced with lines specified in the request. The names are delimited by comma. | [optional] 
 **replace_selected_fields** | **bool**| If set to &#39;true&#39;, all fields that should be deleted in the update request, including body fields, must be included in the &#39;replace&#39; query parameter. | [optional] [default to False]

### Return type

void (empty response body)

### Authorization

[OAuth_1.0_authorization](../README.md#OAuth_1.0_authorization)

### HTTP request headers

 - **Content-Type**: application/vnd.oracle.resource+json; type=singular
 - **Accept**: application/vnd.oracle.resource+json; type=error

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Upserted record. |  * X-NetSuite-PropertyValidation - The description of a property validation failure. <br>  * X-NetSuite-Warning - Warning messages that occurred during processing. <br>  |
**0** | Error response. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sales_tax_item_post**
> sales_tax_item_post(sales_tax_item, prefer=prefer, x_net_suite_idempotency_key=x_net_suite_idempotency_key, replace=replace, x_net_suite_property_name_validation=x_net_suite_property_name_validation, x_net_suite_property_value_validation=x_net_suite_property_value_validation)

Insert record.

### Example

* Api Key Authentication (OAuth_1.0_authorization):

```python
import pynetsuite
from pynetsuite.models.sales_tax_item import SalesTaxItem
from pynetsuite.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://account_id.suitetalk.api.netsuite.com/services/rest/record/v1
# See configuration.py for a list of all supported configuration parameters.
configuration = pynetsuite.Configuration(
    host = "https://account_id.suitetalk.api.netsuite.com/services/rest/record/v1"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: OAuth_1.0_authorization
configuration.api_key['OAuth_1.0_authorization'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['OAuth_1.0_authorization'] = 'Bearer'

# Enter a context with an instance of the API client
with pynetsuite.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = pynetsuite.SalesTaxItemApi(api_client)
    sales_tax_item = pynetsuite.SalesTaxItem() # SalesTaxItem | Request body.
    prefer = 'prefer_example' # str | The server behavior requested by the client. Use 'respond-async' to execute the request asynchronously. If the request is executed asynchronously, 'Preference-applied: respond-async' is returned in the response. (optional)
    x_net_suite_idempotency_key = 'x_net_suite_idempotency_key_example' # str | A user-defined unique idempotency key that is applied to every asynchronous requests to ensure that the request is executed only once. Only one request can be executed with every unique idempotency key. Use UUID in string format as defined by RFC 4122. If the request is executed synchronously, this value is ignored. (optional)
    replace = 'sublist1,subrecord.sublist2' # str | The names of sublists on this record. All sublist lines will be replaced with lines specified in the request. The names are delimited by comma. (optional)
    x_net_suite_property_name_validation = Warning # str | Sets the strictness of property name validation. (optional) (default to Warning)
    x_net_suite_property_value_validation = Error # str | Sets the strictness of property value validation. (optional) (default to Error)

    try:
        # Insert record.
        api_instance.sales_tax_item_post(sales_tax_item, prefer=prefer, x_net_suite_idempotency_key=x_net_suite_idempotency_key, replace=replace, x_net_suite_property_name_validation=x_net_suite_property_name_validation, x_net_suite_property_value_validation=x_net_suite_property_value_validation)
    except Exception as e:
        print("Exception when calling SalesTaxItemApi->sales_tax_item_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sales_tax_item** | [**SalesTaxItem**](SalesTaxItem.md)| Request body. | 
 **prefer** | **str**| The server behavior requested by the client. Use &#39;respond-async&#39; to execute the request asynchronously. If the request is executed asynchronously, &#39;Preference-applied: respond-async&#39; is returned in the response. | [optional] 
 **x_net_suite_idempotency_key** | **str**| A user-defined unique idempotency key that is applied to every asynchronous requests to ensure that the request is executed only once. Only one request can be executed with every unique idempotency key. Use UUID in string format as defined by RFC 4122. If the request is executed synchronously, this value is ignored. | [optional] 
 **replace** | **str**| The names of sublists on this record. All sublist lines will be replaced with lines specified in the request. The names are delimited by comma. | [optional] 
 **x_net_suite_property_name_validation** | **str**| Sets the strictness of property name validation. | [optional] [default to Warning]
 **x_net_suite_property_value_validation** | **str**| Sets the strictness of property value validation. | [optional] [default to Error]

### Return type

void (empty response body)

### Authorization

[OAuth_1.0_authorization](../README.md#OAuth_1.0_authorization)

### HTTP request headers

 - **Content-Type**: application/vnd.oracle.resource+json; type=singular
 - **Accept**: application/vnd.oracle.resource+json; type=error

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Inserted record. |  * X-NetSuite-PropertyValidation - The description of a property validation failure. <br>  * X-NetSuite-Warning - Warning messages that occurred during processing. <br>  |
**0** | Error response. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

