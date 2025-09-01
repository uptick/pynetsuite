# AccountAccountContextSearchElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**acctnumber** | **str** |  | [optional] 
**acctname** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**accountingcontext** | [**NsResource**](NsResource.md) |  | [optional] 

## Example

```python
from pynetsuite.models.account_account_context_search_element import AccountAccountContextSearchElement

# TODO update the JSON string below
json = "{}"
# create an instance of AccountAccountContextSearchElement from a JSON string
account_account_context_search_element_instance = AccountAccountContextSearchElement.from_json(json)
# print the JSON string representation of the object
print(AccountAccountContextSearchElement.to_json())

# convert the object into a dict
account_account_context_search_element_dict = account_account_context_search_element_instance.to_dict()
# create an instance of AccountAccountContextSearchElement from a dict
account_account_context_search_element_from_dict = AccountAccountContextSearchElement.from_dict(account_account_context_search_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


