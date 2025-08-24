# InvoiceCustomForm


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.invoice_custom_form import InvoiceCustomForm

# TODO update the JSON string below
json = "{}"
# create an instance of InvoiceCustomForm from a JSON string
invoice_custom_form_instance = InvoiceCustomForm.from_json(json)
# print the JSON string representation of the object
print(InvoiceCustomForm.to_json())

# convert the object into a dict
invoice_custom_form_dict = invoice_custom_form_instance.to_dict()
# create an instance of InvoiceCustomForm from a dict
invoice_custom_form_from_dict = InvoiceCustomForm.from_dict(invoice_custom_form_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


