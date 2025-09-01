# CustomerCurrencyListElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**override_currency_format** | **bool** |  | [optional] 
**balance** | **float** |  | [optional] 
**deposit_balance** | **float** |  | [optional] 
**unbilled_orders** | **float** |  | [optional] 
**symbol_placement** | [**CurrencySymbolPlacement**](CurrencySymbolPlacement.md) |  | [optional] 
**overdue_balance** | **float** |  | [optional] 
**display_symbol** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**currency** | [**Currency**](Currency.md) |  | [optional] 

## Example

```python
from pynetsuite.models.customer_currency_list_element import CustomerCurrencyListElement

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerCurrencyListElement from a JSON string
customer_currency_list_element_instance = CustomerCurrencyListElement.from_json(json)
# print the JSON string representation of the object
print(CustomerCurrencyListElement.to_json())

# convert the object into a dict
customer_currency_list_element_dict = customer_currency_list_element_instance.to_dict()
# create an instance of CustomerCurrencyListElement from a dict
customer_currency_list_element_from_dict = CustomerCurrencyListElement.from_dict(customer_currency_list_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


