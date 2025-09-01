# AccountLocalizationsCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[AccountLocalizationsElement]**](AccountLocalizationsElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.account_localizations_collection import AccountLocalizationsCollection

# TODO update the JSON string below
json = "{}"
# create an instance of AccountLocalizationsCollection from a JSON string
account_localizations_collection_instance = AccountLocalizationsCollection.from_json(json)
# print the JSON string representation of the object
print(AccountLocalizationsCollection.to_json())

# convert the object into a dict
account_localizations_collection_dict = account_localizations_collection_instance.to_dict()
# create an instance of AccountLocalizationsCollection from a dict
account_localizations_collection_from_dict = AccountLocalizationsCollection.from_dict(account_localizations_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


