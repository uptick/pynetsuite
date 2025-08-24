# CustomerShippingCarrier


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 

## Example

```python
from pynetsuite.models.customer_shipping_carrier import CustomerShippingCarrier

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerShippingCarrier from a JSON string
customer_shipping_carrier_instance = CustomerShippingCarrier.from_json(json)
# print the JSON string representation of the object
print(CustomerShippingCarrier.to_json())

# convert the object into a dict
customer_shipping_carrier_dict = customer_shipping_carrier_instance.to_dict()
# create an instance of CustomerShippingCarrier from a dict
customer_shipping_carrier_from_dict = CustomerShippingCarrier.from_dict(customer_shipping_carrier_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


