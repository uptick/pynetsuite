# VendorCurrencyListElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**balance** | **float** |  | [optional] 
**unbilled_orders** | **float** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**currency** | [**Currency**](Currency.md) |  | [optional] 

## Example

```python
from pynetsuite.models.vendor_currency_list_element import VendorCurrencyListElement

# TODO update the JSON string below
json = "{}"
# create an instance of VendorCurrencyListElement from a JSON string
vendor_currency_list_element_instance = VendorCurrencyListElement.from_json(json)
# print the JSON string representation of the object
print(VendorCurrencyListElement.to_json())

# convert the object into a dict
vendor_currency_list_element_dict = vendor_currency_list_element_instance.to_dict()
# create an instance of VendorCurrencyListElement from a dict
vendor_currency_list_element_from_dict = VendorCurrencyListElement.from_dict(vendor_currency_list_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


