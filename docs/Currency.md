# Currency


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**is_inactive** | **bool** | Check this box to make the currency record is inactive, or clear it to make the record active. You cannot make a currency inactive if any open transactions exist in that currency. | [optional] 
**symbol** | **str** | Enter the three-letter International Standards Organization (ISO) code for this currency. For example, you would use PHP for Philippines pesos, UYU for Uruguayan pesos, and MXN for Mexican pesos. | [optional] 
**is_anchor_currency** | **bool** | A check in this box indicates that the currency has been selected as an anchor currency in the accounting preferences. To clear the box, change the selection in the accounting preference under Use Triangulation Calculation by NetSuite. If this currency is a designated anchor currency and has been used in an exchange rate calculation, you cannot delete this currency. For more information about triangulation and anchor currencies, see the help topics Methods for Obtaining Exchange Rates andAnchor Currencies. | [optional] 
**include_in_fx_rate_updates** | **bool** | Check this box to update currency exchange rates daily. | [optional] 
**last_modified_date** | **datetime** |  | [optional] 
**exchange_rate** | **float** | Enter an exchange rate for this currency against the base currency of this company, or if you use OneWorld, for this currency against the base currency of the root parent subsidiary. The exchange rate is equal to the base currency amount divided by the foreign currency amount. For example, if your company is located in Canada (base currency) and you are defining the U.S. dollar (foreign currency), and the current exchange rate is 1.02 Canadian dollars to 1.00 U.S. dollar, the Default Exchange Rate for the U.S. dollar is 1.02/1.00, or 1.02. This rate is the basis for rates in the Currency Exchange Rates table that are used in foreign currency transactions. If you use OneWorld, this rate also is the basis for rates in the Consolidated Exchange Rates table that are used in consolidated financials. For more information, see the help topic Currency Exchange Rates. | [optional] 
**external_id** | **str** |  | [optional] 
**is_base_currency** | **bool** | Indicates that this currency is the company&amp;apos;s base currency or in OneWorld accounts, the base currency for a subsidiary. Note: After you have entered transactions in foreign currencies, you cannot change a base currency. | [optional] 
**locale** | [**CurrencyLocale**](CurrencyLocale.md) |  | [optional] 
**fx_rate_update_timezone** | [**CurrencyFxRateUpdateTimezone**](CurrencyFxRateUpdateTimezone.md) |  | [optional] 
**override_currency_format** | **bool** | Check this box to customize the currency format. | [optional] 
**format_sample** | **str** | This field displays a sample of how currency amounts display for the selected format. The decimal precision shown cannot be changed. Note: The decimal precision shown is the precision used for both inventory reporting and for costing calculations. | [optional] 
**currency_precision** | **int** | Displays the precision of the currency, which designates the number of digits to the right of the decimal point used in currency transactions. Precision can be zero or two. The level of decimal precision indicated is used for inventory costing calculations to maintains consistency between inventory costing and reporting. Values in report results are rounded to the base currency precision. This rounding applies to currency values and non-currency values, including formula column values. To change this read-only field to a dropdown list through which you can change the precision from zero or two, contact NetSuite Technical Support. | [optional] 
**name** | **str** | Enter a unique name for the currency. Because many countries use the same name for their currencies, you should use a combined name that includes the country name or abbreviation as well as the name of the currency. For example, pesos are the currency in the Philippines, Uruguay, and Mexico. In the Name field, you might enter “Mexican peso.” This name appears in the Currency field on records and transactions. | [optional] 
**id** | **str** |  | [optional] 
**symbol_placement** | [**CurrencySymbolPlacement**](CurrencySymbolPlacement.md) |  | [optional] 
**display_symbol** | **str** | Enter the currency symbol and text to use for this currency. Include spaces if you want to separate the symbol from the currency value. For example, $ USD or $CAD. | [optional] 
**ref_name** | **str** |  | [optional] 
**links** | [**List[NsLink]**](NsLink.md) |  | [optional] [readonly] 

## Example

```python
from pynetsuite.models.currency import Currency

# TODO update the JSON string below
json = "{}"
# create an instance of Currency from a JSON string
currency_instance = Currency.from_json(json)
# print the JSON string representation of the object
print(Currency.to_json())

# convert the object into a dict
currency_dict = currency_instance.to_dict()
# create an instance of Currency from a dict
currency_from_dict = Currency.from_dict(currency_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


