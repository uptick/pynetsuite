# NsResourceCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**items** | [**List[NsResource]**](NsResource.md) |  | [optional] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.ns_resource_collection import NsResourceCollection

# TODO update the JSON string below
json = "{}"
# create an instance of NsResourceCollection from a JSON string
ns_resource_collection_instance = NsResourceCollection.from_json(json)
# print the JSON string representation of the object
print(NsResourceCollection.to_json())

# convert the object into a dict
ns_resource_collection_dict = ns_resource_collection_instance.to_dict()
# create an instance of NsResourceCollection from a dict
ns_resource_collection_from_dict = NsResourceCollection.from_dict(ns_resource_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


