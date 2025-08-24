# CustomerNumberFormat


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.customer_number_format import CustomerNumberFormat

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerNumberFormat from a JSON string
customer_number_format_instance = CustomerNumberFormat.from_json(json)
# print the JSON string representation of the object
print(CustomerNumberFormat.to_json())

# convert the object into a dict
customer_number_format_dict = customer_number_format_instance.to_dict()
# create an instance of CustomerNumberFormat from a dict
customer_number_format_from_dict = CustomerNumberFormat.from_dict(customer_number_format_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


