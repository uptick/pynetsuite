# VendorRolesCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[VendorRolesElement]**](VendorRolesElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.vendor_roles_collection import VendorRolesCollection

# TODO update the JSON string below
json = "{}"
# create an instance of VendorRolesCollection from a JSON string
vendor_roles_collection_instance = VendorRolesCollection.from_json(json)
# print the JSON string representation of the object
print(VendorRolesCollection.to_json())

# convert the object into a dict
vendor_roles_collection_dict = vendor_roles_collection_instance.to_dict()
# create an instance of VendorRolesCollection from a dict
vendor_roles_collection_from_dict = VendorRolesCollection.from_dict(vendor_roles_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


