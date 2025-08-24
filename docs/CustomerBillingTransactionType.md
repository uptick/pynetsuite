# CustomerBillingTransactionType


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.customer_billing_transaction_type import CustomerBillingTransactionType

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerBillingTransactionType from a JSON string
customer_billing_transaction_type_instance = CustomerBillingTransactionType.from_json(json)
# print the JSON string representation of the object
print(CustomerBillingTransactionType.to_json())

# convert the object into a dict
customer_billing_transaction_type_dict = customer_billing_transaction_type_instance.to_dict()
# create an instance of CustomerBillingTransactionType from a dict
customer_billing_transaction_type_from_dict = CustomerBillingTransactionType.from_dict(customer_billing_transaction_type_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


