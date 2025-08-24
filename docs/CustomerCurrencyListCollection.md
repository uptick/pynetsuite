# CustomerCurrencyListCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[CustomerCurrencyListElement]**](CustomerCurrencyListElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.customer_currency_list_collection import CustomerCurrencyListCollection

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerCurrencyListCollection from a JSON string
customer_currency_list_collection_instance = CustomerCurrencyListCollection.from_json(json)
# print the JSON string representation of the object
print(CustomerCurrencyListCollection.to_json())

# convert the object into a dict
customer_currency_list_collection_dict = customer_currency_list_collection_instance.to_dict()
# create an instance of CustomerCurrencyListCollection from a dict
customer_currency_list_collection_from_dict = CustomerCurrencyListCollection.from_dict(customer_currency_list_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


