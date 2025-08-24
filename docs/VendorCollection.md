# VendorCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_results** | **int** |  | [optional] [readonly] 
**items** | [**List[Vendor]**](Vendor.md) | An array field that represents a collection of elements, for example, sublist lines, multiselect items, or search results. | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.vendor_collection import VendorCollection

# TODO update the JSON string below
json = "{}"
# create an instance of VendorCollection from a JSON string
vendor_collection_instance = VendorCollection.from_json(json)
# print the JSON string representation of the object
print(VendorCollection.to_json())

# convert the object into a dict
vendor_collection_dict = vendor_collection_instance.to_dict()
# create an instance of VendorCollection from a dict
vendor_collection_from_dict = VendorCollection.from_dict(vendor_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


