# NsLink


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rel** | **str** |  | [optional] [readonly] 
**href** | **str** |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.ns_link import NsLink

# TODO update the JSON string below
json = "{}"
# create an instance of NsLink from a JSON string
ns_link_instance = NsLink.from_json(json)
# print the JSON string representation of the object
print(NsLink.to_json())

# convert the object into a dict
ns_link_dict = ns_link_instance.to_dict()
# create an instance of NsLink from a dict
ns_link_from_dict = NsLink.from_dict(ns_link_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


