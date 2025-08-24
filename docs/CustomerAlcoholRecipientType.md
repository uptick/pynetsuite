# CustomerAlcoholRecipientType


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.customer_alcohol_recipient_type import CustomerAlcoholRecipientType

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerAlcoholRecipientType from a JSON string
customer_alcohol_recipient_type_instance = CustomerAlcoholRecipientType.from_json(json)
# print the JSON string representation of the object
print(CustomerAlcoholRecipientType.to_json())

# convert the object into a dict
customer_alcohol_recipient_type_dict = customer_alcohol_recipient_type_instance.to_dict()
# create an instance of CustomerAlcoholRecipientType from a dict
customer_alcohol_recipient_type_from_dict = CustomerAlcoholRecipientType.from_dict(customer_alcohol_recipient_type_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


