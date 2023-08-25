# Test Plan for Personalized Coupon Emails

## Test Scenarios & Expected Results:

1. **Scenario**: New customer with no purchase history.
   - **Test Case**: Ensure a unique coupon code is generated.
   - **Expected Result**: Email received with a generic offer and a unique coupon code.
   
2. **Scenario**: Returning customer with purchase history.
   - **Test Case**: Personalize the offer based on their last purchased item.
   - **Expected Result**: Email received referencing the last purchased item and providing a unique coupon code.

3. **Scenario**: Coupon expiration date.
   - **Test Case**: Check the expiration date on the coupon.
   - **Expected Result**: The expiration date should be 30 days from the current date.
