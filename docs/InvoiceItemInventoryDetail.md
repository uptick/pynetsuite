# InvoiceItemInventoryDetail


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**item_description** | **str** | A more complete Description of the item. | [optional] 
**unit** | **str** | If the assembly uses Units of Measure, the base units are displayed in the Units field. | [optional] 
**quantity** | **float** | In the Quantity to Build field, enter the number of assembly items you want to build. You cannot enter a quantity that exceeds the amount displayed in the Buildable Quantity field. | [optional] 
**custom_form** | [**InvoiceItemInventoryDetailCustomForm**](InvoiceItemInventoryDetailCustomForm.md) |  | [optional] 
**external_id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**location** | [**NsResource**](NsResource.md) |  | [optional] 
**item** | [**NsResource**](NsResource.md) |  | [optional] 
**inventory_assignment** | [**InvoiceItemInventoryDetailInventoryAssignmentCollection**](InvoiceItemInventoryDetailInventoryAssignmentCollection.md) |  | [optional] 
**to_location** | [**NsResource**](NsResource.md) |  | [optional] 

## Example

```python
from pynetsuite.models.invoice_item_inventory_detail import InvoiceItemInventoryDetail

# TODO update the JSON string below
json = "{}"
# create an instance of InvoiceItemInventoryDetail from a JSON string
invoice_item_inventory_detail_instance = InvoiceItemInventoryDetail.from_json(json)
# print the JSON string representation of the object
print(InvoiceItemInventoryDetail.to_json())

# convert the object into a dict
invoice_item_inventory_detail_dict = invoice_item_inventory_detail_instance.to_dict()
# create an instance of InvoiceItemInventoryDetail from a dict
invoice_item_inventory_detail_from_dict = InvoiceItemInventoryDetail.from_dict(invoice_item_inventory_detail_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


