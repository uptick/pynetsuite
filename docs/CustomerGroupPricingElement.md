# CustomerGroupPricingElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**ref_name** | **str** |  | [optional] 
**group** | [**NsResource**](NsResource.md) |  | [optional] 
**level** | [**NsResource**](NsResource.md) |  | [optional] 

## Example

```python
from pynetsuite.models.customer_group_pricing_element import CustomerGroupPricingElement

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerGroupPricingElement from a JSON string
customer_group_pricing_element_instance = CustomerGroupPricingElement.from_json(json)
# print the JSON string representation of the object
print(CustomerGroupPricingElement.to_json())

# convert the object into a dict
customer_group_pricing_element_dict = customer_group_pricing_element_instance.to_dict()
# create an instance of CustomerGroupPricingElement from a dict
customer_group_pricing_element_from_dict = CustomerGroupPricingElement.from_dict(customer_group_pricing_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


