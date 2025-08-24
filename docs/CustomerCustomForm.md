# CustomerCustomForm


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.customer_custom_form import CustomerCustomForm

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerCustomForm from a JSON string
customer_custom_form_instance = CustomerCustomForm.from_json(json)
# print the JSON string representation of the object
print(CustomerCustomForm.to_json())

# convert the object into a dict
customer_custom_form_dict = customer_custom_form_instance.to_dict()
# create an instance of CustomerCustomForm from a dict
customer_custom_form_from_dict = CustomerCustomForm.from_dict(customer_custom_form_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


