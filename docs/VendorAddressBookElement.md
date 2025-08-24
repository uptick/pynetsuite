# VendorAddressBookElement


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**internal_id** | **int** |  | [optional] 
**default_billing** | **bool** |  | [optional] 
**last_modified_date** | **datetime** |  | [optional] 
**address_book_address_text** | **str** |  | [optional] 
**default_shipping** | **bool** |  | [optional] 
**label** | **str** |  | [optional] 
**id** | **int** |  | [optional] 
**address_id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**address_book_address** | [**VendorAddressBookAddressBookAddress**](VendorAddressBookAddressBookAddress.md) |  | [optional] 

## Example

```python
from pynetsuite.models.vendor_address_book_element import VendorAddressBookElement

# TODO update the JSON string below
json = "{}"
# create an instance of VendorAddressBookElement from a JSON string
vendor_address_book_element_instance = VendorAddressBookElement.from_json(json)
# print the JSON string representation of the object
print(VendorAddressBookElement.to_json())

# convert the object into a dict
vendor_address_book_element_dict = vendor_address_book_element_instance.to_dict()
# create an instance of VendorAddressBookElement from a dict
vendor_address_book_element_from_dict = VendorAddressBookElement.from_dict(vendor_address_book_element_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


