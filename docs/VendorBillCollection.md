# VendorBillCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_results** | **int** |  | [optional] [readonly] 
**items** | [**List[VendorBill]**](VendorBill.md) | An array field that represents a collection of elements, for example, sublist lines, multiselect items, or search results. | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.vendor_bill_collection import VendorBillCollection

# TODO update the JSON string below
json = "{}"
# create an instance of VendorBillCollection from a JSON string
vendor_bill_collection_instance = VendorBillCollection.from_json(json)
# print the JSON string representation of the object
print(VendorBillCollection.to_json())

# convert the object into a dict
vendor_bill_collection_dict = vendor_bill_collection_instance.to_dict()
# create an instance of VendorBillCollection from a dict
vendor_bill_collection_from_dict = VendorBillCollection.from_dict(vendor_bill_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


