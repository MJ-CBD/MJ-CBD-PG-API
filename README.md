

# MJ-CBD-PG-API
MJ-CBD PG APIs Source
Public MJ-CBD API ver1.0 

API (Application Program Interface) is a protocol that is provided to disclose information to information users. 
It is an interface that enables developers to utilize PG (Payment Gate) data in other systems. 
MJ-CBD Wallet developers provide APIs such as API that Secret key can be confirmed with ID and Password and 
API that can how to view order details through user ID and order number.


In addition to providing web search results and user interface (UI), 
We help users that they will be able to develop creative and diverse contents by utilizing published data.



STEP1. USE MJ CBD PG by affiliates

Create affiliate and obtain the code below and use it in PG.
1) no : affiliate unique code
2) shop_id : affiliate unique ID
3) shop_name : affiliate name
4) site_url : affiliate site url 


STEP2. Applying PG source
Explanation
Apply the source using the card values generated by STEP1 and the key values generated by STEP2.

Main request variable
- no : affiliate unique code
- shop_id : affiliate unique ID
- shop_name : affiliate name
- site_url : affiliate site url 

- order_name : order item name
- item_price : item price
- delivery : delivery fee
- pay_krw : pay information(KRW)
- card_num : card number
- currency_type : currency type(KRW:won USD : dollors)
- shop_oder_no : affiliate’s item unique number
- return_url : After completing PG pay, Link to parent page when PG window off

Related Source

<!--버튼 html -->
<div class=”table-responsive text-center” style=’padding:40px;><span style=’color:#ff0000;font-weight:700;margin-right:15px;padding:10px;’>Please enter MJ-CBD</span>
<input type=”text” name=”od_cbd_email” id=”od_cbd_email” clasee=”peps_input” required placeholder="MJ-CBD ID" onchange="insert_form_data(this.value);" required > 
<input type="button" value="MJ-CBD  Payment" id="btn_order2" onclick="windowSize()" class="peps_btn" style="display:''"></div>



