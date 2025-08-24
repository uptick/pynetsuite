# VendorCurrencyListCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[VendorCurrencyListElement]**](VendorCurrencyListElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.vendor_currency_list_collection import VendorCurrencyListCollection

# TODO update the JSON string below
json = "{}"
# create an instance of VendorCurrencyListCollection from a JSON string
vendor_currency_list_collection_instance = VendorCurrencyListCollection.from_json(json)
# print the JSON string representation of the object
print(VendorCurrencyListCollection.to_json())

# convert the object into a dict
vendor_currency_list_collection_dict = vendor_currency_list_collection_instance.to_dict()
# create an instance of VendorCurrencyListCollection from a dict
vendor_currency_list_collection_from_dict = VendorCurrencyListCollection.from_dict(vendor_currency_list_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


