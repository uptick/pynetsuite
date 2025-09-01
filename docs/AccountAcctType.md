# AccountAcctType


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.account_acct_type import AccountAcctType

# TODO update the JSON string below
json = "{}"
# create an instance of AccountAcctType from a JSON string
account_acct_type_instance = AccountAcctType.from_json(json)
# print the JSON string representation of the object
print(AccountAcctType.to_json())

# convert the object into a dict
account_acct_type_dict = account_acct_type_instance.to_dict()
# create an instance of AccountAcctType from a dict
account_acct_type_from_dict = AccountAcctType.from_dict(account_acct_type_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


