# Test cases

****Preconditions:****

- App: [https://www.lacoste.pl/en/](https://www.lacoste.pl/en/)

## **Test case 1: Add product to cart**

1. Open link of the product
2. Choose size 
3. Select “Add to bag”
4. Click on bag icon

**Expected result:** The chosen product with necessary size is in the bag.

## **Test case 2: Searching for an item**

1. Click on search field
2. Type keyword 

**Expected result:** Possible variants of products with this keyword are displayed

## **Test case 3: Add product to cart without size**

1. Open link of the product
2. Choose size 
3. Select “Add to bag”
4. Choose different size
5. Select “Add to bag”
6. Click on bag icon

**Expected result:** Two selected products are added separately to a package of different sizes.

## **Test case 4: Remove product from the cart**

1. Open link of the product
2. Choose size
3. Select "Add to bag"
4. Click on bag icon
5. Click on icon "cross" near product

**Expected result:** The chosen product is removed from the bag.

## **Test case 5: Changing amount of products in the cart**

1. Open link of the product
2. Choose size
3. Select "Add to bag"
4. Click on bag icon
5. Click on icon picker
6. Select amount

**Expected result:** Amount of products in the bag is 2.

## **Test case 6: Viewing empty cart**

1. Click on icon "bag"

**Expected result:** Show message "Your bag is empty"

## Test case 7: Checking the availability product of chosen size

1. Open link of the product category
2. Click on the "Sort and Filter"
3. Select "44"
4. Check whether the size of the products matches the filter condition

**Expected result:** Show page with products only with size “44" in stock.

## **Test case 8: Price changing after adding the same item in cart**

1. Open link of the product
2. Choose size
3. Click "Add to bag"
4. Click on bag icon
5. Check the price opposite the item
6. Click on icon picker
7. Select amount

**Expected result:** The price is twice as much.

## **Test case 9:** Using an invalid promo code

1. Open link of the product
2. Choose size 
3. Select “Add to bag”
4. Click on bag icon
5. Write “qwerty” in promo code section
6. Click “Send”

**Expected result:** The error message: "The voucher code is invalid”.

## **Test case 10:** Using an invalid promo code

1. Open link of the product with green colour 
2. Click on selected colour
3. Choose grey

**Expected result:** The product page changes to a page with the product grayed out. The selected product color will be gray.