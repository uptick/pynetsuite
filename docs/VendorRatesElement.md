# VendorRatesElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**rate** | **float** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**entity_currency** | [**Currency**](Currency.md) |  | [optional] 

## Example

```python
from pynetsuite.models.vendor_rates_element import VendorRatesElement

# TODO update the JSON string below
json = "{}"
# create an instance of VendorRatesElement from a JSON string
vendor_rates_element_instance = VendorRatesElement.from_json(json)
# print the JSON string representation of the object
print(VendorRatesElement.to_json())

# convert the object into a dict
vendor_rates_element_dict = vendor_rates_element_instance.to_dict()
# create an instance of VendorRatesElement from a dict
vendor_rates_element_from_dict = VendorRatesElement.from_dict(vendor_rates_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


