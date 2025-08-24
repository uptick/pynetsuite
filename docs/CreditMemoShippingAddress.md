# CreditMemoShippingAddress


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**zip** | **str** | Enter the postal code the way it should appear on all forms except checks. | [optional] 
**country** | [**InvoiceBillingAddressCountry**](InvoiceBillingAddressCountry.md) |  | [optional] 
**addr2** | **str** | Enter an optional second address line the way it should appear on forms. For employees, customers, partners, and vendors, what you enter here autofills on forms if this address is marked default for Shipping or Billing. Enter up to 50 characters. | [optional] 
**city** | **str** | Enter the city the way it should appear on all forms except checks. | [optional] 
**addr1** | **str** | Enter the address the way it should appear on forms. For employees, customers, partners, and vendors, what you enter here autofills on forms if this address is marked default for Shipping or Billing. Enter up to 50 characters. This field is required for the Online Bill Pay feature. | [optional] 
**last_modified_date** | **datetime** |  | [optional] 
**addr3** | **str** |  | [optional] 
**external_id** | **str** |  | [optional] 
**addr_phone** | **str** | Enter the phone number. | [optional] 
**addressee** | **str** | Enter the name of the entity that should appear on the shipping label here. This name appears on the shipping label below what you enter in the Attention field. | [optional] 
**attention** | **str** | Enter the name of the person to whom a shipment is addressed, as it should appear on shipping labels. This field is required for UPS Integration. | [optional] 
**override** | **bool** | Check this box to disable the free-form address text field. When this field is disabled, text entered in the other address fields does not display in the Address text field. Clear this box to allow text entered in the address component fields to appear in the free-form address text field. | [optional] 
**state** | **str** | Enter your company&amp;apos;s state or province the way it should appear on all forms except checks. | [optional] 
**addr_text** | **str** | The values entered in the other address fields are displayed here. | [optional] 
**ref_name** | **str** |  | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.credit_memo_shipping_address import CreditMemoShippingAddress

# TODO update the JSON string below
json = "{}"
# create an instance of CreditMemoShippingAddress from a JSON string
credit_memo_shipping_address_instance = CreditMemoShippingAddress.from_json(json)
# print the JSON string representation of the object
print(CreditMemoShippingAddress.to_json())

# convert the object into a dict
credit_memo_shipping_address_dict = credit_memo_shipping_address_instance.to_dict()
# create an instance of CreditMemoShippingAddress from a dict
credit_memo_shipping_address_from_dict = CreditMemoShippingAddress.from_dict(credit_memo_shipping_address_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


