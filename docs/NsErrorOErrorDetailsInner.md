# NsErrorOErrorDetailsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**detail** | **str** | A detailed, human-readable description of the problem occurrence. | [optional] [readonly] 
**o_error_path** | **str** | The JSON path that indicates where the problem occurs within the request body. | [optional] [readonly] 
**o_error_url** | **str** | The URI of the first element in the request URL where the problem occurs. | [optional] [readonly] 
**o_error_header** | **str** | The name of the HTTP header where the problem occurs. | [optional] [readonly] 
**o_error_query_param** | **str** | The name of the query parameter where the problem occurs. | [optional] [readonly] 
**o_error_code** | **str** | The application-specific error code. Similar problem types are grouped together. | [optional] [readonly] 

## Example

```python
from pynetsuite.models.ns_error_o_error_details_inner import NsErrorOErrorDetailsInner

# TODO update the JSON string below
json = "{}"
# create an instance of NsErrorOErrorDetailsInner from a JSON string
ns_error_o_error_details_inner_instance = NsErrorOErrorDetailsInner.from_json(json)
# print the JSON string representation of the object
print(NsErrorOErrorDetailsInner.to_json())

# convert the object into a dict
ns_error_o_error_details_inner_dict = ns_error_o_error_details_inner_instance.to_dict()
# create an instance of NsErrorOErrorDetailsInner from a dict
ns_error_o_error_details_inner_from_dict = NsErrorOErrorDetailsInner.from_dict(ns_error_o_error_details_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


