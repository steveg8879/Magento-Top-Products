# Magento-Top-Products
Top product module for Magento

This nifty little add-on allows you to import a product by ID anywhere into your Magento store. The items associated with the product can be interchanged.  For the purposes of this demo I'm importng 

1. The product image
2. The price/special price
3. The product name
4. A link to the product
5. The reviews (if applicable)


To use the module place the .phtml file inside your template to catalog/product/view/.  Call the module by placing the the below code block in a CMS page or static block with the products ID.  And Thats It!!!

you can see a working demo by visiting http://www.clevertraining.com/running and scrolling down to the "OUR TOP PICKS" section


 {{block type="catalog/product_new" product_id="123456"
                    template="catalog/product/view/topPickProduct.phtml"}}

