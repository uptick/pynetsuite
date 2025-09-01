# AccountCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_results** | **int** |  | [optional] [readonly] 
**items** | [**List[Account]**](Account.md) | An array field that represents a collection of elements, for example, sublist lines, multiselect items, or search results. | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.account_collection import AccountCollection

# TODO update the JSON string below
json = "{}"
# create an instance of AccountCollection from a JSON string
account_collection_instance = AccountCollection.from_json(json)
# print the JSON string representation of the object
print(AccountCollection.to_json())

# convert the object into a dict
account_collection_dict = account_collection_instance.to_dict()
# create an instance of AccountCollection from a dict
account_collection_from_dict = AccountCollection.from_dict(account_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


