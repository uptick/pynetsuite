# InvoiceItemCostInventoryDetailInventoryAssignmentCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[InvoiceItemCostInventoryDetailInventoryAssignmentElement]**](InvoiceItemCostInventoryDetailInventoryAssignmentElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.invoice_item_cost_inventory_detail_inventory_assignment_collection import InvoiceItemCostInventoryDetailInventoryAssignmentCollection

# TODO update the JSON string below
json = "{}"
# create an instance of InvoiceItemCostInventoryDetailInventoryAssignmentCollection from a JSON string
invoice_item_cost_inventory_detail_inventory_assignment_collection_instance = InvoiceItemCostInventoryDetailInventoryAssignmentCollection.from_json(json)
# print the JSON string representation of the object
print(InvoiceItemCostInventoryDetailInventoryAssignmentCollection.to_json())

# convert the object into a dict
invoice_item_cost_inventory_detail_inventory_assignment_collection_dict = invoice_item_cost_inventory_detail_inventory_assignment_collection_instance.to_dict()
# create an instance of InvoiceItemCostInventoryDetailInventoryAssignmentCollection from a dict
invoice_item_cost_inventory_detail_inventory_assignment_collection_from_dict = InvoiceItemCostInventoryDetailInventoryAssignmentCollection.from_dict(invoice_item_cost_inventory_detail_inventory_assignment_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


