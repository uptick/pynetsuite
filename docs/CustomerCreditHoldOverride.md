# CustomerCreditHoldOverride


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.customer_credit_hold_override import CustomerCreditHoldOverride

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerCreditHoldOverride from a JSON string
customer_credit_hold_override_instance = CustomerCreditHoldOverride.from_json(json)
# print the JSON string representation of the object
print(CustomerCreditHoldOverride.to_json())

# convert the object into a dict
customer_credit_hold_override_dict = customer_credit_hold_override_instance.to_dict()
# create an instance of CustomerCreditHoldOverride from a dict
customer_credit_hold_override_from_dict = CustomerCreditHoldOverride.from_dict(customer_credit_hold_override_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


