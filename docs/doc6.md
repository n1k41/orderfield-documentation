---
id: doc6
title: XML - Xlenz ESB
sidebar_label: XML - Xlenz
---

Voorbeeld XML tbv Xlenz ESB standaard

```
<Orders>
<OrderHeader>
<WebOrderNr>ORDER_12345</WebOrderNr>
<ProviderCode>Testcustomer</ProviderCode>
<Company_obj>374.33961000</Company_obj>
<OrderDate>2019-05-07</OrderDate>
<CustomerCode>00703</CustomerCode>
<WarehouseCode>1</WarehouseCode>
<OrderOriginCode>09</OrderOriginCode>
<OrderTypeCode>8</OrderTypeCode>
<CustomerReference>823027</CustomerReference>
<AdditionalInformation/>
<OrderLines>
<OrderLine>
<WebOrderLineSeq>1</WebOrderLineSeq>
<CustomerItemOrder>823027:1</CustomerItemOrder>
<ItemDimension_obj>35695.33961000</ItemDimension_obj>
<ItemDimensionSize_obj>35698.33961000</ItemDimensionSize_obj>
<ItemCode>21</ItemCode>
<OrderedQty>100</OrderedQty>
<SalesPriceAmt>0.59</SalesPriceAmt>
<SalesPriceAmtFromWebsite>0.59</SalesPriceAmtFromWebsite>
<SalesPricePer>1</SalesPricePer>
<EarliestDeliveryDate>2019-05-07</EarliestDeliveryDate>
<OrderLineTexts/>
<OrderLineCustomFields/>
</OrderLine>
<OrderLine>
<WebOrderLineSeq>2</WebOrderLineSeq>
<CustomerItemOrder>823027:2</CustomerItemOrder>
<ItemDimension_obj>186881502.33961000</ItemDimension_obj>
<ItemDimensionSize_obj>186889517.33961000</ItemDimensionSize_obj>
<ItemCode>31343</ItemCode>
<OrderedQty>1</OrderedQty>
<SalesPriceAmt>49.95</SalesPriceAmt>
<SalesPriceAmtFromWebsite>49.95</SalesPriceAmtFromWebsite>
<SalesPricePer>1</SalesPricePer>
<EarliestDeliveryDate>2019-05-07</EarliestDeliveryDate>
<OrderLineTexts/>
<OrderLineCustomFields/>
</OrderLine>
</OrderLines>
<DeliveryAddresses>
<DeliveryAddress>
<DeliveryAddress_obj>26723.33961000</DeliveryAddress_obj>
</DeliveryAddress>
</DeliveryAddresses>
<CustomerAddress>
<Name>Test Customer</Name>
<Street>Test street</Street>
<HouseNr>32</HouseNr>
<HouseNrExt/>
<ZipCode>1000 AA</ZipCode>
<City>TESTCITY</City>
<CountryIsoCode>NL</CountryIsoCode>
<Phone>0201234567</Phone>
<Email>test@testcustomer.nl</Email>
</CustomerAddress>
<OrderHeaderTexts/>
<OrderHeaderCustomFields/>
</OrderHeader>
</Orders>
```