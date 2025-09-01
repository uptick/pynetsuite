# TaxTypeCountry


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.tax_type_country import TaxTypeCountry

# TODO update the JSON string below
json = "{}"
# create an instance of TaxTypeCountry from a JSON string
tax_type_country_instance = TaxTypeCountry.from_json(json)
# print the JSON string representation of the object
print(TaxTypeCountry.to_json())

# convert the object into a dict
tax_type_country_dict = tax_type_country_instance.to_dict()
# create an instance of TaxTypeCountry from a dict
tax_type_country_from_dict = TaxTypeCountry.from_dict(tax_type_country_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


