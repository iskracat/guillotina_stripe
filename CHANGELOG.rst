CHANGELOG
=========

1.0.0a13 (unreleased)
---------------------

- Nothing changed yet.


1.0.0a12 (2022-01-18)
---------------------

- Not delete consumer after cancel subscription [rboixaderg]
- Add cards behavior. Create a new behavior to save all customer cards in object. [rboixaderg]
- Not cancelled all subscriptions from the same customer when created a new subscription or delete it [rboixaderg]
- Add PATCH subscription endpoint, and avoid activate trial subscription if last subscription is cancelled


1.0.0a11 (2021-11-25)
---------------------

- Fixing amount in coupons when paying products. Adding tests.
  [nilbacardit26]
- When amount to pay using coupons is below 50cts, the total
  payment would be 50cts, due to slack does not admit payment below 50cts.
  [nilbacardit26]

1.0.0a10 (2021-11-24)
---------------------

- Be able to update customer when calling @register-card, customer_id
  can be passed as a parameter
  [nilbacardit26]


1.0.0a9 (2021-11-24)
--------------------

- Fixing API response in subscriptions
  [nilbacardit26]


1.0.0a8 (2021-11-19)
--------------------

- Adding support for coupons in subscripions and products
  [nilbacardit26]


1.0.0a7 (2021-03-12)
--------------------

- Adding registry to keep price - id x content type
  [bloodbare]


1.0.0a6 (2020-12-23)
--------------------

- Fixing subscription bug


1.0.0a5 (2020-12-22)
--------------------

- Fixing trial big


1.0.0a4 (2020-12-22)
--------------------

- Fixing subscription bug


1.0.0a3 (2020-12-22)
--------------------

- Support trail subscription


1.0.0a2 (2020-12-21)
--------------------

- Nothing changed yet.


1.0.0a1 (2020-12-21)
--------------------

- Initial version
