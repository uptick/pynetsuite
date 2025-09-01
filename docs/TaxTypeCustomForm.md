# TaxTypeCustomForm


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.tax_type_custom_form import TaxTypeCustomForm

# TODO update the JSON string below
json = "{}"
# create an instance of TaxTypeCustomForm from a JSON string
tax_type_custom_form_instance = TaxTypeCustomForm.from_json(json)
# print the JSON string representation of the object
print(TaxTypeCustomForm.to_json())

# convert the object into a dict
tax_type_custom_form_dict = tax_type_custom_form_instance.to_dict()
# create an instance of TaxTypeCustomForm from a dict
tax_type_custom_form_from_dict = TaxTypeCustomForm.from_dict(tax_type_custom_form_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


