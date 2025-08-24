# CustomerAddressBookElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**internal_id** | **int** |  | [optional] 
**default_billing** | **bool** |  | [optional] 
**last_modified_date** | **datetime** |  | [optional] 
**address_book_address_text** | **str** |  | [optional] 
**default_shipping** | **bool** |  | [optional] 
**is_residential** | **bool** |  | [optional] 
**label** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**address_id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**address_book_address** | [**CustomerAddressBookAddressBookAddress**](CustomerAddressBookAddressBookAddress.md) |  | [optional] 

## Example

```python
from pynetsuite.models.customer_address_book_element import CustomerAddressBookElement

# TODO update the JSON string below
json = "{}"
# create an instance of CustomerAddressBookElement from a JSON string
customer_address_book_element_instance = CustomerAddressBookElement.from_json(json)
# print the JSON string representation of the object
print(CustomerAddressBookElement.to_json())

# convert the object into a dict
customer_address_book_element_dict = customer_address_book_element_instance.to_dict()
# create an instance of CustomerAddressBookElement from a dict
customer_address_book_element_from_dict = CustomerAddressBookElement.from_dict(customer_address_book_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


