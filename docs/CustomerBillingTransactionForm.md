# CustomerBillingTransactionForm


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.customer_billing_transaction_form import CustomerBillingTransactionForm

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerBillingTransactionForm from a JSON string
customer_billing_transaction_form_instance = CustomerBillingTransactionForm.from_json(json)
# print the JSON string representation of the object
print(CustomerBillingTransactionForm.to_json())

# convert the object into a dict
customer_billing_transaction_form_dict = customer_billing_transaction_form_instance.to_dict()
# create an instance of CustomerBillingTransactionForm from a dict
customer_billing_transaction_form_from_dict = CustomerBillingTransactionForm.from_dict(customer_billing_transaction_form_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


