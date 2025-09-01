# CurrencySymbolPlacement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.currency_symbol_placement import CurrencySymbolPlacement

# TODO update the JSON string below
json = "{}"
# create an instance of CurrencySymbolPlacement from a JSON string
currency_symbol_placement_instance = CurrencySymbolPlacement.from_json(json)
# print the JSON string representation of the object
print(CurrencySymbolPlacement.to_json())

# convert the object into a dict
currency_symbol_placement_dict = currency_symbol_placement_instance.to_dict()
# create an instance of CurrencySymbolPlacement from a dict
currency_symbol_placement_from_dict = CurrencySymbolPlacement.from_dict(currency_symbol_placement_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


