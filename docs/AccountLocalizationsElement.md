# AccountLocalizationsElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**legal_name** | **str** |  | [optional] 
**acctnumber** | **str** |  | [optional] 
**acctname** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**accountingcontext** | [**NsResource**](NsResource.md) |  | [optional] 

## Example

```python
from pynetsuite.models.account_localizations_element import AccountLocalizationsElement

# TODO update the JSON string below
json = "{}"
# create an instance of AccountLocalizationsElement from a JSON string
account_localizations_element_instance = AccountLocalizationsElement.from_json(json)
# print the JSON string representation of the object
print(AccountLocalizationsElement.to_json())

# convert the object into a dict
account_localizations_element_dict = account_localizations_element_instance.to_dict()
# create an instance of AccountLocalizationsElement from a dict
account_localizations_element_from_dict = AccountLocalizationsElement.from_dict(account_localizations_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


