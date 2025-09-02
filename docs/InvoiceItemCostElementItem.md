# InvoiceItemCostElementItem


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**ref_name** | **str** |  | [optional] 
**external_id** | **str** |  | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 
**is_inactive** | **bool** | Check this box to inactivate this record. Inactive records do not show on transactions and records for selection in lists. | [optional] 
**custrecord_4110_no_tax_invoice** | **bool** |  | [optional] 
**custrecord_4110_non_taxable** | **bool** |  | [optional] 
**custrecord_for_digital_services** | **bool** |  | [optional] 
**custrecord_4110_reduced_rate** | **bool** |  | [optional] 
**custrecord_4110_partial_credit** | **bool** |  | [optional] 
**description** | **str** | Enter a description for this record. | [optional] 
**custrecord_4110_outside_customs** | **bool** |  | [optional] 
**custrecord_4110_other_tax_evidence** | **bool** |  | [optional] 
**custrecord_4110_capital_goods** | **bool** |  | [optional] 
**custrecord_4110_non_deductible** | **bool** |  | [optional] 
**custrecord_4110_no_tax_credit** | **bool** |  | [optional] 
**custrecord_4110_suspended** | **bool** |  | [optional] 
**custrecord_4110_reverse_charge_alt** | **bool** |  | [optional] 
**custrecord_4110_duty** | **bool** |  | [optional] 
**custrecord_4110_government** | **bool** |  | [optional] 
**custrecord_4110_non_recoverable** | **bool** |  | [optional] 
**custrecord_4110_import** | **bool** |  | [optional] 
**custrecord_4110_paid** | **bool** |  | [optional] 
**custrecord_4110_triplicate** | **bool** |  | [optional] 
**custrecord_4110_electronic** | **bool** |  | [optional] 
**custrecord_4110_purchaser_issued** | **bool** |  | [optional] 
**custrecord_4110_surcharge** | **bool** |  | [optional] 
**custrecord_4110_category** | **str** |  | [optional] 
**custrecord_4110_non_operation** | **bool** |  | [optional] 
**custrecord_deemed_supply** | **bool** |  | [optional] 
**custrecord_4110_super_reduced** | **bool** |  | [optional] 
**custrecord_gcc_state** | **bool** |  | [optional] 
**custrecord_is_direct_cost_service** | **bool** |  | [optional] 
**item_type** | **str** |  | [optional] 
**custrecord_4110_duplicate** | **bool** |  | [optional] 
**custom_form** | [**SalesTaxItemCustomForm**](SalesTaxItemCustomForm.md) |  | [optional] 
**custrecord_4110_special_territory** | **bool** |  | [optional] 
**custrecord_4110_cash_register** | **bool** |  | [optional] 
**custrecord_4110_non_resident** | **bool** |  | [optional] 
**custrecord_4110_unknown_tax_credit** | **bool** |  | [optional] 
**rate** | **float** |  | [optional] 
**custrecord_4110_nondeductible_parent** | [**SalesTaxItem**](SalesTaxItem.md) |  | [optional] 
**tax_type** | [**TaxType**](TaxType.md) |  | [optional] 
**custrecord_deferred_on** | [**NsResource**](NsResource.md) |  | [optional] 
**custrecord_4110_nondeductible_account** | [**Account**](Account.md) |  | [optional] 
**custrecord_tax_exemption_reason** | [**NsResource**](NsResource.md) |  | [optional] 
**custrecord_4110_parent_alt** | [**SalesTaxItem**](SalesTaxItem.md) |  | [optional] 

## Example

```python
from pynetsuite.models.invoice_item_cost_element_item import InvoiceItemCostElementItem

# TODO update the JSON string below
json = "{}"
# create an instance of InvoiceItemCostElementItem from a JSON string
invoice_item_cost_element_item_instance = InvoiceItemCostElementItem.from_json(json)
# print the JSON string representation of the object
print(InvoiceItemCostElementItem.to_json())

# convert the object into a dict
invoice_item_cost_element_item_dict = invoice_item_cost_element_item_instance.to_dict()
# create an instance of InvoiceItemCostElementItem from a dict
invoice_item_cost_element_item_from_dict = InvoiceItemCostElementItem.from_dict(invoice_item_cost_element_item_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


