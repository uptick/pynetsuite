# VendorBillItemInventoryDetailInventoryAssignmentCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[VendorBillItemInventoryDetailInventoryAssignmentElement]**](VendorBillItemInventoryDetailInventoryAssignmentElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.vendor_bill_item_inventory_detail_inventory_assignment_collection import VendorBillItemInventoryDetailInventoryAssignmentCollection

# TODO update the JSON string below
json = "{}"
# create an instance of VendorBillItemInventoryDetailInventoryAssignmentCollection from a JSON string
vendor_bill_item_inventory_detail_inventory_assignment_collection_instance = VendorBillItemInventoryDetailInventoryAssignmentCollection.from_json(json)
# print the JSON string representation of the object
print(VendorBillItemInventoryDetailInventoryAssignmentCollection.to_json())

# convert the object into a dict
vendor_bill_item_inventory_detail_inventory_assignment_collection_dict = vendor_bill_item_inventory_detail_inventory_assignment_collection_instance.to_dict()
# create an instance of VendorBillItemInventoryDetailInventoryAssignmentCollection from a dict
vendor_bill_item_inventory_detail_inventory_assignment_collection_from_dict = VendorBillItemInventoryDetailInventoryAssignmentCollection.from_dict(vendor_bill_item_inventory_detail_inventory_assignment_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


