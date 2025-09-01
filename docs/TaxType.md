# TaxType


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**country** | [**TaxTypeCountry**](TaxTypeCountry.md) |  | [optional] 
**custom_form** | [**TaxTypeCustomForm**](TaxTypeCustomForm.md) |  | [optional] 
**name** | **str** | Enter a name for this record. | [optional] 
**external_id** | **str** |  | [optional] 
**description** | **str** | Enter a description for this record. | [optional] 
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.tax_type import TaxType

# TODO update the JSON string below
json = "{}"
# create an instance of TaxType from a JSON string
tax_type_instance = TaxType.from_json(json)
# print the JSON string representation of the object
print(TaxType.to_json())

# convert the object into a dict
tax_type_dict = tax_type_instance.to_dict()
# create an instance of TaxType from a dict
tax_type_from_dict = TaxType.from_dict(tax_type_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


