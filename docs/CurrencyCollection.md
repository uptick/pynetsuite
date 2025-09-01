# CurrencyCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_results** | **int** |  | [optional] [readonly] 
**items** | [**List[Currency]**](Currency.md) | An array field that represents a collection of elements, for example, sublist lines, multiselect items, or search results. | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.currency_collection import CurrencyCollection

# TODO update the JSON string below
json = "{}"
# create an instance of CurrencyCollection from a JSON string
currency_collection_instance = CurrencyCollection.from_json(json)
# print the JSON string representation of the object
print(CurrencyCollection.to_json())

# convert the object into a dict
currency_collection_dict = currency_collection_instance.to_dict()
# create an instance of CurrencyCollection from a dict
currency_collection_from_dict = CurrencyCollection.from_dict(currency_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


