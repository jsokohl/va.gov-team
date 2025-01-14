# Direct deposit

### Relevant links

- Invision prototype [Desktop](https://vsateams.invisionapp.com/share/FJW9OGY2B9A#/410216937_DD_1) | [Mobile](https://vsateams.invisionapp.com/share/34WJ8JOCMAB)  
- Github design issue: [#5266](https://github.com/department-of-veterans-affairs/va.gov-team/issues/5266)
- Github front-end issue: [#5355](https://github.com/department-of-veterans-affairs/va.gov-team/issues/5355)

### Description

This section of the profile will show people's direct deposit information that we pull from EVSS/BGS. 

## Direct deposit: Desktop read-only view

### Design

[Most up-to-date version on InVision](https://vsateams.invisionapp.com/share/FJW9OGY2B9A#/410216937_DD_1)

- **Tressa** will need to provide design specs since read-only view styling is new.

![Direct deposit](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/profile/Combine%20Profile%20and%20Account/Design/design-specs/profile-images/direct-deposit/Direct%20deposit.jpg)

Here's specs for the table.

![Table Specs](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/profile/Combine%20Profile%20and%20Account/Design/design-specs/profile-images/feature-specs/table-specs.jpg)


### Copy

To the best of my knowledge, all existing copy is the same as what we currently have in the direct deposit section on VA.gov.

**Main section**

- **Page title**: Direct deposit information for disability compensation and pension benefits
- **First section title**: Bank information
  - **Field label**: Account
    - **Field data**: (Bank name, routing number, and account type will load dynamically)
  - **Edit label**: Edit
- **Second section title**: Payment history
  - **Field label**: View your payment history
    - This will link out to this page on eBenefits: https://www.ebenefits.va.gov/ebenefits/about/feature?feature=payment-history

**Note below main section**

**Note**: If you think you’ve been the victim of bank fraud, please call us at 800-827-1000 (TTY: 800-829-4833). We’re here Monday through Friday, 8:00 a.m. to 9:00 p.m.

**FAQs**

These will use our current collapsible FAQ state. Also, copy is the same as what we have now.

**How do I change my direct deposit information for GI Bill and other education benefits?**

(Need to get body copy, but it's the same as what's in prod now)

**What’s my bank routing number?**

(Need to get body copy, but it's the same as what's in prod now)

## Direct deposit: Edit in place

### Design

[Most up-to-date version on InVision](https://vsateams.invisionapp.com/share/FJW9OGY2B9A#/410216938_DD_2)

![Direct deposit_Edit in place](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/profile/Combine%20Profile%20and%20Account/Design/design-specs/profile-images/direct-deposit/Direct%20deposit_edit%20in%20place.jpg)

Here are specs for the edit-in-place.

![Expanded Table Specs](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/profile/Combine%20Profile%20and%20Account/Design/design-specs/profile-images/feature-specs/edit-in-place-specs.jpg)

### Copy

I believe this is all the same as what we have in prod now.

- **Directions**: Please provide your bank’s routing number as well as your current account and type. 
- **Field labels**:
  - Routing number (Your 9-digit routing number will update your bank's name)(Required)
  - Account number (No more than 17 digits) (Required)
  - Account type (Required)
- **Button labels**
  - Update
  - Cancel

## Direct deposit: Edit in place_FAQ open

### Design

This uses the same "check" image we have now in production.

[Most up-to-date version on InVision](https://vsateams.invisionapp.com/share/FJW9OGY2B9A#/410514592_DD_2_Dropdown)

![Direct deposit_Edit in place](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/profile/Combine%20Profile%20and%20Account/Design/design-specs/profile-images/direct-deposit/Direct%20deposit_edit%20in%20place_FAQ%20open.jpg)

### Copy

- **FAQ**: Where can I find these numbers?

## Direct deposit: Edit in place_Required error state

### Design

Re: interaction design — these function the same as the existing required error states in production.

[Most up-to-date version on InVision](https://vsateams.invisionapp.com/share/FJW9OGY2B9A#/410216939_DD_3)

![Direct deposit_Edit in place_Required errors](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/profile/Combine%20Profile%20and%20Account/Design/design-specs/profile-images/direct-deposit/Direct%20deposit_edit%20in%20place_errors.jpg)

### Copy

These should be the same as what we have in prod now.

- **Routing number**: Please enter the bank's 9-digit routing number.
- **Account number**: Please enter your account number.
- **Account type**: Please select the type that best describes the account.


## Direct deposit: Save state

### Design

I believe this state already exists in the design system, but Tressa should confirm.

[Most up-to-date version on InVision]()

![Direct deposit_Successful save](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/profile/Combine%20Profile%20and%20Account/Design/design-specs/profile-images/direct-deposit/Direct%20deposit_Save%20successful.jpg)

### Copy

We've saved your direct deposit information.

## Direct deposit: Save/update errors

### Design

We can use the existing "red" error state for the various errors we have for direct deposit.

[Most up-to-date version on InVision](https://vsateams.invisionapp.com/share/FJW9OGY2B9A#/410216940_DD_4)

![Direct deposit_Edit in place](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/profile/Combine%20Profile%20and%20Account/Design/design-specs/profile-images/direct-deposit/Direct%20deposit_error.jpg)

### Copy

We should use the same copy for all the errors we have now. No updates here.

## Direct deposit: Section won't load

### Design

We can use the existing "yellow" alert state we have for direct deposit. This would be used if we can't load this section for whatever reason.

[Most up-to-date version on InVision](https://vsateams.invisionapp.com/share/FJW9OGY2B9A#/410216941_DD_5)

![Direct deposit_Section won't load](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/profile/Combine%20Profile%20and%20Account/Design/design-specs/profile-images/direct-deposit/Direct%20deposit_Can't%20load%20DD%20info.jpg)

### Copy

We’re sorry.  Something went wrong on our end.  Please refresh this page or try again later.

## Direct deposit: Mobile view

### Design

[Most up-to-date version on InVision](https://vsateams.invisionapp.com/share/34WJ8JOCMAB)

![Direct deposit_Mobile view](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/profile/Combine%20Profile%20and%20Account/Design/design-specs/profile-images/direct-deposit/Direct%20deposit_Mobile%20view.jpg)
