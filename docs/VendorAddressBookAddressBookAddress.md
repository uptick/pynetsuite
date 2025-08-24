# VendorAddressBookAddressBookAddress


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**zip** | **str** |  | [optional] 
**country** | [**InvoiceBillingAddressCountry**](InvoiceBillingAddressCountry.md) |  | [optional] 
**addr2** | **str** |  | [optional] 
**city** | **str** |  | [optional] 
**addr1** | **str** |  | [optional] 
**last_modified_date** | **datetime** |  | [optional] 
**addr3** | **str** |  | [optional] 
**external_id** | **str** |  | [optional] 
**addr_phone** | **str** |  | [optional] 
**addressee** | **str** |  | [optional] 
**attention** | **str** |  | [optional] 
**override** | **bool** |  | [optional] 
**state** | **str** |  | [optional] 
**addr_text** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.vendor_address_book_address_book_address import VendorAddressBookAddressBookAddress

# TODO update the JSON string below
json = "{}"
# create an instance of VendorAddressBookAddressBookAddress from a JSON string
vendor_address_book_address_book_address_instance = VendorAddressBookAddressBookAddress.from_json(json)
# print the JSON string representation of the object
print(VendorAddressBookAddressBookAddress.to_json())

# convert the object into a dict
vendor_address_book_address_book_address_dict = vendor_address_book_address_book_address_instance.to_dict()
# create an instance of VendorAddressBookAddressBookAddress from a dict
vendor_address_book_address_book_address_from_dict = VendorAddressBookAddressBookAddress.from_dict(vendor_address_book_address_book_address_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


