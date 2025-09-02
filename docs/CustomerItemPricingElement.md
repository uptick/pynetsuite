# CustomerItemPricingElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**price** | **float** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**currency** | [**Currency**](Currency.md) |  | [optional] 
**level** | [**NsResource**](NsResource.md) |  | [optional] 
**item** | [**InvoiceItemCostElementItem**](InvoiceItemCostElementItem.md) |  | [optional] 

## Example

```python
from pynetsuite.models.customer_item_pricing_element import CustomerItemPricingElement

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerItemPricingElement from a JSON string
customer_item_pricing_element_instance = CustomerItemPricingElement.from_json(json)
# print the JSON string representation of the object
print(CustomerItemPricingElement.to_json())

# convert the object into a dict
customer_item_pricing_element_dict = customer_item_pricing_element_instance.to_dict()
# create an instance of CustomerItemPricingElement from a dict
customer_item_pricing_element_from_dict = CustomerItemPricingElement.from_dict(customer_item_pricing_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


