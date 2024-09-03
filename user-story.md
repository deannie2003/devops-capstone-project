**As a** customer support agent  
**I need** to be able to update customer addresses  
**So that** I can ensure their orders are delivered to the correct location  

### Details and Assumptions
   * The customer support agent should have permission to edit customer data.
   * The system should validate the new address before updating.
   * This functionality should be accessible via the user interface.

### Acceptance Criteria
```gherkin
Given the customer support agent is logged into the system
When they select a customer and update the address information
Then the system should save the new address and confirm the update
