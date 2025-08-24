# InvoiceItemInventoryDetailCustomForm


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.invoice_item_inventory_detail_custom_form import InvoiceItemInventoryDetailCustomForm

# TODO update the JSON string below
json = "{}"
# create an instance of InvoiceItemInventoryDetailCustomForm from a JSON string
invoice_item_inventory_detail_custom_form_instance = InvoiceItemInventoryDetailCustomForm.from_json(json)
# print the JSON string representation of the object
print(InvoiceItemInventoryDetailCustomForm.to_json())

# convert the object into a dict
invoice_item_inventory_detail_custom_form_dict = invoice_item_inventory_detail_custom_form_instance.to_dict()
# create an instance of InvoiceItemInventoryDetailCustomForm from a dict
invoice_item_inventory_detail_custom_form_from_dict = InvoiceItemInventoryDetailCustomForm.from_dict(invoice_item_inventory_detail_custom_form_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


