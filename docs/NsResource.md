# NsResource


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**external_id** | **str** |  | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.ns_resource import NsResource

# TODO update the JSON string below
json = "{}"
# create an instance of NsResource from a JSON string
ns_resource_instance = NsResource.from_json(json)
# print the JSON string representation of the object
print(NsResource.to_json())

# convert the object into a dict
ns_resource_dict = ns_resource_instance.to_dict()
# create an instance of NsResource from a dict
ns_resource_from_dict = NsResource.from_dict(ns_resource_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


