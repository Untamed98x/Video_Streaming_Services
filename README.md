# Video_Streaming_Services

# Streaming Site Project - PacFlix

PacFlix is a streaming service offering various subscription plans with features tailored to meet the needs of its users.

## A. Case Description

### Available Plans
PacFlix offers three subscription plans:
- **Basic Plan**
- **Standard Plan**
- **Premium Plan**

| Basic Plan                | Standard Plan             | Premium Plan                 | Service                                          |
|---------------------------|---------------------------|------------------------------|--------------------------------------------------|
| Yes                       | Yes                       | Yes                          | Can Stream                                       |
| Yes                       | Yes                       | Yes                          | Can Download                                     |
| Yes                       | Yes                       | Yes                          | Has SD                                           |
|                           | Yes                       | Yes                          | Has HD                                           |
|                           |                           | Yes                          | Has UHD                                          |
| 1                         | 2                         | 4                            | Number of Devices                                |
| 3rd Party Movies Only    | Basic Plan + Sports (F1, Football, Basketball) | Basic Plan + Standard Plan + PacFlix Original Series or Movie | Content                                         |
| 120,000                   | 160,000                   | 200,000                      | Price                                            |

### User Upgrade Rules
- Users can only select one plan from those offered.
- Users can only upgrade their plan; downgrades are not permitted.
- Users may upgrade from their current plan to the next available plan.

### Discount Plan
- Users with a subscription duration greater than 12 months who wish to upgrade will receive a 5% discount.

**Example**:
- Yudha currently has a subscription.
- He has been subscribed for 13 months.
- He plans to upgrade to the "Standard Plan."
- The total amount he has to pay is:

```
Total = 160,000 - (160,000 * 0.05) = 152,000
```

### Referral Plan
If a new user wishes to subscribe and has a valid referral code, they will receive a 4% discount on their payment.

**Example**:
- Anoton is a new user who wants to subscribe to PacFlix.
- He intends to subscribe to the "Premium Plan."
- He uses a referral code from a friend.
- The final total amount he has to pay is:

```
Total = 200,000 - (200,000 * 0.04) = 192,000
```

## B. Objective
As Python programmers, we will develop a simple program for PacFlix that includes the following features:
- Check all available plans on PacFlix.
- Check the plan currently used by existing users.
- Allow current users to upgrade their plan and apply discounts if their subscription duration exceeds 12 months.
- Enable new users to subscribe to PacFlix and receive discounts if they use a referral code.

### User Data
The user data will include:
- Username
- Active Plan
- Duration of the Plan
- Referral Code

## C. Case Study

### Case 1 - Check User Plans
- **User**: Cahya wants to check which plans are available on PacFlix.
- **Input**: 
- **Output**: Available plans as per the table above.

### Case 2 - Check Active Plan
- **User**: Shandy wants to check which plan is currently active on PacFlix.
- **Input**: 
  - username
- **Output**: 
  - username, active plan, duration of plan.

### Case 3 - Upgrade User
- **User**: Ana wants to upgrade from her current plan and has been subscribed for more than 12 months.
- **Input**: 
  - username, current plan, new plan.
- **Output**: 
  - total amount to be paid.

### Case 4 - Referral Code Member
- **User**: Faizal wants to register for PacFlix, choosing the Standard Plan and using a referral code from user Bagus.
- **Input**: 
  - username, selected plan, referral code.
- **Output**: 
  - total amount to be paid.
