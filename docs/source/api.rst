.. _api:

Developer Interface
===================

.. module:: schwifty

IBAN
----

.. autoclass:: IBAN
   :members: account_code, bank_code, bban, bic, branch_code, checksum_digits, compact, country_code, formatted, generate, length, numeric, spec, validate


BIC
---

.. autoclass:: BIC
   :members: bank_code, branch_code, country_bank_code, country_code, compact, exists, formatted, from_bank_code, location_code, length, type, validate
