# CustomerGroupPricingCollection


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**total_results** | **int** |  | [optional] [readonly] 
**count** | **int** |  | [optional] [readonly] 
**has_more** | **bool** |  | [optional] [readonly] 
**offset** | **int** |  | [optional] [readonly] 
**items** | [**List[CustomerGroupPricingElement]**](CustomerGroupPricingElement.md) |  | [optional] 

## Example

```python
from pynetsuite.models.customer_group_pricing_collection import CustomerGroupPricingCollection

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerGroupPricingCollection from a JSON string
customer_group_pricing_collection_instance = CustomerGroupPricingCollection.from_json(json)
# print the JSON string representation of the object
print(CustomerGroupPricingCollection.to_json())

# convert the object into a dict
customer_group_pricing_collection_dict = customer_group_pricing_collection_instance.to_dict()
# create an instance of CustomerGroupPricingCollection from a dict
customer_group_pricing_collection_from_dict = CustomerGroupPricingCollection.from_dict(customer_group_pricing_collection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


