# AccountAccountContextSearchCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[AccountAccountContextSearchElement]**](AccountAccountContextSearchElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.account_account_context_search_collection import AccountAccountContextSearchCollection

# TODO update the JSON string below
json = "{}"
# create an instance of AccountAccountContextSearchCollection from a JSON string
account_account_context_search_collection_instance = AccountAccountContextSearchCollection.from_json(json)
# print the JSON string representation of the object
print(AccountAccountContextSearchCollection.to_json())

# convert the object into a dict
account_account_context_search_collection_dict = account_account_context_search_collection_instance.to_dict()
# create an instance of AccountAccountContextSearchCollection from a dict
account_account_context_search_collection_from_dict = AccountAccountContextSearchCollection.from_dict(account_account_context_search_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


