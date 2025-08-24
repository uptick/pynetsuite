# CustomerCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_results** | **int** |  | [optional] [readonly] 
**items** | [**List[Customer]**](Customer.md) | An array field that represents a collection of elements, for example, sublist lines, multiselect items, or search results. | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.customer_collection import CustomerCollection

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerCollection from a JSON string
customer_collection_instance = CustomerCollection.from_json(json)
# print the JSON string representation of the object
print(CustomerCollection.to_json())

# convert the object into a dict
customer_collection_dict = customer_collection_instance.to_dict()
# create an instance of CustomerCollection from a dict
customer_collection_from_dict = CustomerCollection.from_dict(customer_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


