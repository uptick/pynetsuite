# InvoiceItemInventoryDetailInventoryAssignmentCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[InvoiceItemInventoryDetailInventoryAssignmentElement]**](InvoiceItemInventoryDetailInventoryAssignmentElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.invoice_item_inventory_detail_inventory_assignment_collection import InvoiceItemInventoryDetailInventoryAssignmentCollection

# TODO update the JSON string below
json = "{}"
# create an instance of InvoiceItemInventoryDetailInventoryAssignmentCollection from a JSON string
invoice_item_inventory_detail_inventory_assignment_collection_instance = InvoiceItemInventoryDetailInventoryAssignmentCollection.from_json(json)
# print the JSON string representation of the object
print(InvoiceItemInventoryDetailInventoryAssignmentCollection.to_json())

# convert the object into a dict
invoice_item_inventory_detail_inventory_assignment_collection_dict = invoice_item_inventory_detail_inventory_assignment_collection_instance.to_dict()
# create an instance of InvoiceItemInventoryDetailInventoryAssignmentCollection from a dict
invoice_item_inventory_detail_inventory_assignment_collection_from_dict = InvoiceItemInventoryDetailInventoryAssignmentCollection.from_dict(invoice_item_inventory_detail_inventory_assignment_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


