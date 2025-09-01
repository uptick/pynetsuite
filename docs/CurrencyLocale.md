# CurrencyLocale


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.currency_locale import CurrencyLocale

# TODO update the JSON string below
json = "{}"
# create an instance of CurrencyLocale from a JSON string
currency_locale_instance = CurrencyLocale.from_json(json)
# print the JSON string representation of the object
print(CurrencyLocale.to_json())

# convert the object into a dict
currency_locale_dict = currency_locale_instance.to_dict()
# create an instance of CurrencyLocale from a dict
currency_locale_from_dict = CurrencyLocale.from_dict(currency_locale_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


