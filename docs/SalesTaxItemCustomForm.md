# SalesTaxItemCustomForm


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.sales_tax_item_custom_form import SalesTaxItemCustomForm

# TODO update the JSON string below
json = "{}"
# create an instance of SalesTaxItemCustomForm from a JSON string
sales_tax_item_custom_form_instance = SalesTaxItemCustomForm.from_json(json)
# print the JSON string representation of the object
print(SalesTaxItemCustomForm.to_json())

# convert the object into a dict
sales_tax_item_custom_form_dict = sales_tax_item_custom_form_instance.to_dict()
# create an instance of SalesTaxItemCustomForm from a dict
sales_tax_item_custom_form_from_dict = SalesTaxItemCustomForm.from_dict(sales_tax_item_custom_form_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


